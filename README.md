# VSC Rspec

A simple rspec snippets to make life easier.

## Snippets

### Core
`rspec-new-rails-file` : Rails standard new spec file template.  
`rspec-new-file` : New spec file template.  
`rspec-new-shared-example` : New rspec shared example file  
`rspec-new-shared-context` : New rspec shared context file  
`rspec-it_behaves_like` : it_behaves_like shared examples  
`rspec-include_context` : include_context shared context  
  
`rspec-describe-block` : Describe block  
`rspec-context-block` : Context block  
`rspec-it-block` : Rspec it block  
`rspec-it-inline` : One liner it that uses subject  
  
`rspec-expect:mock-return` : Rspec expectition with mock.  
`rspec-expect:mock` : Rspec expectition.  
`rspec-expect:execution-inline` : Rspec expect execution inline with "expect {}.to"  
`rspec-expect:mock-minimum` : Rspec expectition minimum.  

`rspec-let` : Let declaration.  
`rspec-truthy` : be_truthy shortcut  
`rspec-falsy` : be_falsy shortcut  

`rspec-string` : Test string
`rspec-array` : Test Array
`rspec-hash` : Test Hash
`rspec-numeric` : Test Numbers
`rspec-exception` : Test Exceptions

### ITS

`rspec-its(:size)` : Check the size of the hash  
`rspec-its(:keys)` : Check all key names only  
`rspec-its([:key])` : Check hash key value  
`rspec-its([:key1, :key2])` : subject { {key1: {key2: 3} } } | its([:key1, :key2]) { is_expected.to eq(3) }  

### Shoulda Matchers

#### Active Model

`rspec-validate_absence_of` : Test usage of validates_absence_of  
`rspec-validate_acceptance_of` : Test usage of validates_acceptance_of  
`rspec-validate_confirmation_of` : Test usage of validates_confirmation_of  
`rspec-validate_inclusion_of` : Test usage of validates_inclusion_of  
`rspec-validate_length_of` : Test usage of validates_length_of  
`rspec-validate_numericality_of` : Test usage of validates_numericality_of  
`rspec-validate_presence_of` : Test usage of validates_presence_of  

#### Active Record

`rspec-belongs_to` : Test usage of belongs_to  
`rspec-has_many` : Test usage of has_many  
`rspec-have_one` : Test usage of have_one  

#### Controller & Route

`rspec-permit` : Test controller params
`rspec-redirect` : Test redirect
`rspec-route` : Test routing
`rspec-render-template` : Test render template
`rspec-render-partial` : Test partial template
`rspec-respond-with` : Test http status code
`rspec-check-session` : Test session

## Release Notes

For changelog see [CHANGELOG.md](https://github.com/SaimonL/vsc-rspec/blob/master/CHANGELOG.md)

**Enjoy!**
