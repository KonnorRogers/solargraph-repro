# A reproduction of not getting solargraph checking with CEM Parser.

## Setup

```bash
git clone https://github.com/konnorrogers/solargraph_test.git
cd solargraph_test
bundle install
bundle exec yard gems
```

## The issue

Go into `test.rb` and attempt to find documentation for the `.parse` command or anything in the
CustomElementsManifest module. Nothing is there except `VERSION` despite there being extensive Yard docs in the
repo.

<https://github.com/KonnorRogers/custom_elements_manifest_parser/blob/ec8a6dac42766004b7d7f5eda2fa792f85e13d32/lib/custom_elements_manifest_parser.rb#L13>

