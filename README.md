
# remon


[![CircleCI](https://circleci.com/gh/yourgithubhandle/remon/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/remon/tree/master)


**Contains the following libraries and executables:**

```
remon@0.0.0
│
├─test/
│   name:    TestRemon.exe
│   require: remon/library
│
├─library/
│   library name: remon/library
│   require:
│
└─executable/
    name:    RemonApp.exe
    require: remon/library
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
esy x RemonApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
