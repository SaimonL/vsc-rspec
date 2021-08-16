# Rspec snippets for Ruby and Rails

A simple rspec snippets to make life easier.

**Enjoy!**

### New file/context/blocks

* `rspec-new-rails-file` : Rails standard new spec file template.
* `rspec-new-file` : New spec file template.
* `rspec-new-shared-example` : New rspec shared example file
* `rspec-new-shared-context` : New rspec shared context file
* `rspec-include_context` : include_context shared context
* `rspec-describe-block` : Describe block
* `rspec-context-block` : Context block
* `rspec-it-block` : Rspec it block
* `rspec-it_behaves_like` : it_behaves_like shared examples
* `rspec-it-inline` : One liner it that uses subject

### Let declares

* `rspec-let` : Let declaration
* `rspec-let-instance-double` : Let declaration of instance double
* `rspec-let-class-double` : Let declaration of class double
* `rspec-let-job-peform` : Let declaration that triggers the ActiveJob
* `rspec-let-module` : Let you test methods in module by calling them directly

### Matchers

* `rspec-string` : Test string
* `rspec-array` : Test Array
* `rspec-hash` : Test Hash
* `rspec-numeric` : Test Numbers
* `rspec-exception` : Test Exceptions

### Boolean

* `rspec-truthy` : be_truthy shortcut
* `rspec-truthy-subject` : Inline test using subject
* `rspec-falsy` : be_falsy shortcut
* `rspec-falsy-subject` : Inline test using subject

### Mock/Stub/Allow

* `rspec-expect:mock-return` : Rspec expectition with mock
* `rspec-expect:mock` : Rspec expectition
* `rspec-expect:execution-inline` : Rspec expect execution inline with "expect {}.to"
* `rspec-expect:mock-minimum` : Rspec expectition minimum
* `rspec-mock-rails-logger` : Mocks Rails logger to check if a message was sent
* `rspec-allow-receive-return` : Allow to receive and return value

### Active Jobs

* `rspec-job-enqueued` : Check it see if a ActiveJob was enqueued after a code is executed

## [RSPEC ITS](https://github.com/rspec/rspec-its)

* `rspec-its(:size)` : Check the size of the hash
* `rspec-its(:keys)` : Check all key names only
* `rspec-its([:key])` : Check hash key value
* `rspec-its([:key1, :key2])` : subject { {key1: {key2: 3} } } | its([:key1, :key2]) { is_expected.to eq(3) }

## [Shoulda Matchers](https://github.com/thoughtbot/shoulda-matchers)

### Active Model

* `rspec-allow_value` : Test usage of `allow_value` inline
* `rspec-allow_value-qualifiers` : Test usage of `allow_value` with qualifiers
* `rspec-have_secure_password` : Test usage of `have_secure_password`
* `rspec-validate_absence_of` : Test usage of validates_absence_of
* `rspec-validate_acceptance_of` : Test usage of validates_acceptance_of
* `rspec-validate_confirmation_of` : Test usage of validates_confirmation_of
* `rspec-validate_exclusion_of` : Test usage of `validate_exclusion_of`
* `rspec-validate_inclusion_of` : Test usage of validates_inclusion_of
* `rspec-validate_length_of` : Test usage of validates_length_of
* `rspec-validate_length_of:minimum` : Test usage of `validate_length_of` inline
* `rspec-validate_numericality_of` : Test usage of validates_numericality_of
* `rspec-validate_presence_of` : Test usage of validates_presence_of

### Active Record

* `rspec-accepts_nested_attributes_for` : Tests usage of `accepts_nested_attributes_for` inline
* `rspec-accepts_nested_attributes_for-qualifiers` : Tests usage of `accepts_nested_attributes_for` with qualifiers
* `rspec-belongs_to` : Test usage of belongs_to
* `rspec-has_many` : Test usage of has_many
* `rspec-have_one` : Test usage of have_one
* `rspec-validate_uniqueness_of` : Tests usage of `validate_uniqueness_of`

### Controller & Route

* `rspec-permit` : Test controller params
* `rspec-redirect` : Test redirect
* `rspec-route` : Test routing
* `rspec-render-template` : Test render template
* `rspec-render-partial` : Test partial template
* `rspec-respond-with` : Test http status code
* `rspec-check-session` : Test session

<br />

## Release Notes

For changelog see [CHANGELOG.md](https://github.com/SaimonL/vsc-rspec/blob/master/CHANGELOG.md)
