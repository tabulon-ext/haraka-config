
## NEXT - 202Y-MM-DD

## 1.0.20 - 2021-09-01

- update YAML dep to v4


## 1.0.19 - 2021-06-10

- configfile: disable watch dir when platform not mac or win
- configfile: convert to es6 class
- configfile.read_dir: promisify
- configfile: use simpler es6 `for..in` and `for..of`
- getDir tests, use os.EOL for comparison


## 1.0.18 - 2019-10-11

- add support for loading `.js` configurations


## 1.0.17 - 2018-12-19

- refactor ./config.js as an es6 class
- update README syntax and improve formatting
- use path.resolve instead of ./dir/file (2x)
- watch: recursive=true
- permit retrieval of fully qualified path


## 1.0.16 - 2018-11-02

- remove trailing ; from function declarations
- add config.getInt(filename, default_value)


## 1.0.15 - 2017-09-21

- additional test for 'missing json loads yaml'
- modify get_path_to_config_dir regex to also match windows paths
- add tests for get_path_to_config_dir
- configs w/o .ext or declared type default to flat
- add test for json/yaml !filename overloads


## 1.0.14 - 2017-09-19

- add __dirname/../../config to config_dir_candidates for haraka/Haraka/tests/*
- sync process.env.HARAKA_TEST_DIR from haraka/Haraka/config
- eslint no-var updates #25


## 1.0.13 - 2017-06-16

- lint updates for eslint 4


## 1.0.12 - 2017-05-21

- unref() the setInterval so that Haraka can gracefully exit


## 1.0.11 - 2017-03-04

- add config.getDir, loads all files in a directory


## 1.0.10 - 2017-02-05

- log error vs throw on bad YAML
- fix appveyor badge URL


## 1.0.9 - 2017-01-27

- config cache fix (see haraka/Haraka#1738)
- config: add overrides handling (sync with Haraka)
- configfile: add win64 watching (sync with Haraka)
- remove grunt
- use haraka-eslint plugin (vs local copy of .eslintrc)
- lint updates


## 1.0.8 - 2017-01-02

- version bump, lint updates & sync
- lint fixes


## 1.0.7 - 2016-11-17

- update tests for appveyor (Windows) compatibility #9


## 1.0.6 - 2016-11-10

- handle invalid .ini lines properly (skip them)


## 1.0.5 - 2016-10-25

- do not leave behind a `*` section in config (due to wildcard boolean)


## 1.0.3

- added wildcard boolean support
- reduce node required 4.3 -> 0.10.43
