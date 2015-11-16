# eZPublish Version Tester

The purpose of this repository is to verify which versions of eZPublish5 and eZPlatform can be successfully installed
using composer, if possible including execution of the behat-based test suite(s).

The tests are run on [Travis](https://travis-ci.org/kaliop-uk/ezpublish-version-tester)

## Notes

* a lot of the versions tested do require that the top-level composer.json has set "minimum-stability": "dev"

* 2014.5 and 2014.7 state that minimum php version is 5.3, but their kernels really require 5.4

* versions 2012.9 to 2013.1 have a tag which does not respect semantic versioning and as such can not be easily installed
  using composer (it might be doable with a lot of aliasing though)
