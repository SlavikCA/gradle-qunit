<h3>Trying to get Gradle + Karma + qUnit to work</h3>

Currently, I'm getting this error:

```
Executing task 'karmaRun'...

:karmaInit UP-TO-DATE
:nodeSetup
:karmaDependencies
:karmaGenerateConfig
:karmaRun
Chrome 63.0.3239 (Mac OS X 10.13.3) ERROR
  {
    "message": "Uncaught ReferenceError: test is not defined\nat src/main/js/test.js:1:1\n\nReferenceError: test is not defined\n    at src/main/js/test.js:1:1",
    "str": "Uncaught ReferenceError: test is not defined\nat src/main/js/test.js:1:1\n\nReferenceError: test is not defined\n    at src/main/js/test.js:1:1"
  }


:karmaRun FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':karmaRun'.
> Process 'command '/Users/sfursov/.gradle/nodejs/node-v4.2.3-darwin-x64/bin/node'' finished with non-zero exit value 1

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

* Get more help at https://help.gradle.org

BUILD FAILED in 4m 24s
4 actionable tasks: 4 executed
Process 'command '/Users/sfursov/.gradle/nodejs/node-v4.2.3-darwin-x64/bin/node'' finished with non-zero exit value 1
Task execution finished 'karmaRun'.
```

Environment:
- Mac OS 10.13.3
- Gradle 4.2.1
