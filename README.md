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

### ITS

`rspec-its(:size)` : Check the size of the hash  
`rspec-its(:keys)` : Check all key names only  
`rspec-its([:key])` : Check hash key value  
`rspec-its([:key1, :key2])` : subject { {key1: {key2: 3} } } | its([:key1, :key2]) { is_expected.to eq(3) }  

### Shoulda Matchers

#### Active Model

`rspec-validate_absence_of` : Tests usage of validates_absence_of  
`rspec-validate_acceptance_of` : Tests usage of validates_acceptance_of  
`rspec-validate_confirmation_of` : Tests usage of validates_confirmation_of  
`rspec-validate_inclusion_of` : Tests usage of validates_inclusion_of  
`rspec-validate_length_of` : Tests usage of validates_length_of  
`rspec-validate_numericality_of` : Tests usage of validates_numericality_of  
`rspec-validate_presence_of` : Tests usage of validates_presence_of  

#### Active Record

`rspec-belongs_to` : Tests usage of belongs_to  


## Release Notes

For changelog see [CHANGELOG.md](https://github.com/SaimonL/vsc-rspec/blob/master/CHANGELOG.md)

**Enjoy!**
