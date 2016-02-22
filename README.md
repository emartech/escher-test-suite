# escher-test-suite
Centralized test suite for the [Escher](https://escherauth.io/) lib.

You can export these tests easily to the test folder using SVN. This works on Travis CI.
`svn export https://github.com/emartech/escher-test-suite/trunk/test_cases DESTINATION_FOLDER`

Usage example can be found in [Escher-Ruby](https://github.com/emartech/escher-ruby).

Don't forget to create a test that checks whether all test cases have been run from the test suite. Otherwise we lose the purpose of this centralization.
