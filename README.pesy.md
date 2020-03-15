# reason-native-boilerplate


[![CircleCI](https://circleci.com/gh/yourgithubhandle/reason-native-boilerplate/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/reason-native-boilerplate/tree/master)


**Contains the following libraries and executables:**

```
reason-native-boilerplate@0.0.0
│
├─test/
│   name:    TestReasonNativeBoilerplate.exe
│   main:    TestReasonNativeBoilerplate
│   require: reason-native-boilerplate.lib
│
├─library/
│   library name: reason-native-boilerplate.lib
│   namespace:    ReasonNativeBoilerplate
│   require:
│
└─executable/
    name:    ReasonNativeBoilerplateApp.exe
    main:    ReasonNativeBoilerplateApp
    require: reason-native-boilerplate.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x ReasonNativeBoilerplateApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
