# Junit
At the command prompt > execute ->  mocha test --reporter mocha-junit-reporter to generate junit report
Then more test-results.xml to see result
oliver@W10254Y4Y2:/c/Users/Oliver_Chan/project/Junit/Junit/test$ mocha test --reporter mocha-junit-reporter
oliver@W10254Y4Y2:/c/Users/Oliver_Chan/project/Junit/Junit/test$ more test-results.xml
<?xml version="1.0" encoding="UTF-8"?>
<testsuites name="Mocha Tests" time="0.0000" tests="3" failures="0">
  <testsuite name="Root Suite" timestamp="2021-06-30T12:02:38" tests="0" time="0.0000" failures="0">
  </testsuite>
  <testsuite name="test suite 1" timestamp="2021-06-30T12:02:38" tests="1" file="/c/Users/Oliver_Chan/project/Junit/Junit/test/test/test.js" time="0.0000" failures="0">
    <testcase name="test suite 1 test case 1" time="0.0000" classname="test case 1">
    </testcase>
  </testsuite>
  <testsuite name="test suite 2" timestamp="2021-06-30T12:02:38" tests="1" file="/c/Users/Oliver_Chan/project/Junit/Junit/test/test/test.js" time="0.0000" failures="0">
    <testcase name="test suite 2 test case 2" time="0.0000" classname="test case 2">
    </testcase>
  </testsuite>
  <testsuite name="test suite 3" timestamp="2021-06-30T12:02:38" tests="1" file="/c/Users/Oliver_Chan/project/Junit/Junit/test/test/test.js" time="0.0000" failures="0">
    <testcase name="test suite 3 test case 6" time="0.0000" classname="test case 6">
    </testcase>
  </testsuite>
</testsuites>
oliver@W10254Y4Y2:/c/Users/Oliver_Chan/project/Junit/Junit/test$ npm test

> test@1.0.0 test /c/Users/Oliver_Chan/project/Junit/Junit/test
> mocha



  test suite 1
    ✔ test case 1

  test suite 2
    ✔ test case 2

  test suite 3
    ✔ test case 6


  3 passing (4ms)