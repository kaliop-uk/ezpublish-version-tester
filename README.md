# eZPublish Version Tester

The purpose of this repository is to verify which versions of eZPublish5 and eZPlatform can be successfully installed
using composer, if possible including execution of the behat-based test suite(s).

## Notes

* a lot of the versions tested do require that the top-level composer.json has set "minimum-stability": "dev"

* 2014.5 and 2014.7 state that minimum php version is 5.3, but their kernels really require 5.4
