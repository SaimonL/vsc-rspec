# VSC Rspec

A simple rspec snippets to make life easier.

## Snippets

### Core
`!new-rails-rspec-file` : Rails standard new spec file template.  
`!new-rspec-file` : New spec file template.  
`!new-shared-example` : New rspec shared example file  
`!it_behaves_like` : it_behaves_like shared examples  
  
`!describe-block` : Describe block  
`!context-block` : Context block  
`!it-block` : Rspec it block  
`!it-inline` : One liner it that uses subject  
  
`!expect:execution-inline` : Rspec expect execution inline with "expect {}.to"  
`!expect:mock-return` : Rspec expectition with mock.  
`!expect:mock-minimum` : Rspec expectition minimum.  
`!expect:mock` : Rspec expectition.  

`!let` : Let declaration.  
`!truthy` : be_truthy shortcut  
`!falsy` : be_falsy shortcut  

### ITS

`!its(:size)` : Check the size of the hash  
`!its(:keys)` : Check all key names only  
`!its([:key])` : Check hash key value  
`its([:key1, :key2])` : subject { {key1: {key2: 3} } } | its([:key1, :key2]) { is_expected.to eq(3) }  

### Shoulda Matchers

#### Active Model

`!validate_absence_of` : Tests usage of validates_absence_of  
`!validate_acceptance_of` : Tests usage of validates_acceptance_of  
`!validate_confirmation_of` : Tests usage of validates_confirmation_of  
`!validate_inclusion_of` : Tests usage of validates_inclusion_of  
`!validate_length_of` : Tests usage of validates_length_of  
`!validate_length_of:minimum` : Tests usage of validates_length_of  
`!validate_numericality_of` : Tests usage of validates_numericality_of  
`!validate_presence_of` : Tests usage of validates_presence_of  

## Release Notes

For changelog see [CHANGELOG.md](https://github.com/SaimonL/vsc-rspec/blob/master/CHANGELOG.md)

**Enjoy!**
