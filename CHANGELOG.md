# CHANGELOG for node-jmx

This file is used to list changes made in each version of `jmx` Node.js module.

## 0.8.0 (2020-03-20)

* Update NPM modules
* All APIs now return Promise, except the API inherited from EventEmitter
* Add new API "queryNamesWithObjectName" w.r.t. "queryNames" in "MBeanServerConnection", with only "ObjectName" is support.

## 0.7.0 (2018-03-25)

* Update `java` dependency to `~0.9.0` ([issue #16](https://github.com/zuazo/node-jmx/issues/16), thanks [DarkSorrow](https://github.com/DarkSorrow)).

## 0.6.1 (2016-11-12)

* Fix `java` dependency version to avoid installing *master* branch.

## 0.6.0 (2016-11-12)

* Update `java` dependency to `~0.7.0` (partially fixes [issue #13](https://github.com/zuazo/node-jmx/issues/13), thanks [Jason Brown](https://github.com/jbrownD3) and [Craig Otis](https://github.com/craigotis) for the help).
* *package.json*: Fix license field.

## 0.5.0 (2015-11-03)

* Update `java` dependency to `~0.6.0` (fixes [issue #11](https://github.com/zuazo/node-jmx/issues/11), thanks [Rick ChangRick Chang](https://github.com/redice) for the help).
 * Add Node.js `4` support.
* Update `async` dependency to `~1.5.0`.
* Update contact information and links after migration.
* Documentation improvements.
* Migrate to Travis CI container-based infrastructure.
* Makefile: Add test-java-classes task.

## 0.4.1 (2014-07-18)

* Fix badge links.

## 0.4.0 (2014-07-18)

* Add #getAttributes method ([issue #7](https://github.com/zuazo/node-jmx/pull/7), thanks [@ericbroda](https://github.com/ericbroda)).
* Update dependencies: `async@~1.3.0`, `java@~0.5.0`.
* Add node version `0.12` support.
* Remove node version `0.8` support.

## 0.3.1 (2014-11-16)

* Remove jshint dependency from *package.json*.

## 0.3.0 (2014-11-15)

* package.json: udpate package dependencies (fixes [issue #3](https://github.com/zuazo/node-jmx/issues/3)).
* MBeanServerConnection:
 * Define *credentials* and *instancesAr* variables.
 * Some code improvements.
* Allow premature disconnections (fixes [issue #2](https://github.com/zuazo/node-jmx/issues/2)).
* Fix all [JSHint](http://www.jshint.com/) errors and integrate in the Makefile.
* README: Add [Code Climate](https://codeclimate.com/) badge.
* Makefile: Use relative path for jscoverage.
* Avoid using *should* in tests.

## 0.2.1 (2013-11-04)

* Travis hostname errors fixed.
* Removed node `0.6` support: not supported by the last `node-java` version.
* Homepage changed to GitHub Pages.

## 0.2.0 (2013-05-21)

* Added #listMBeans method.

## 0.1.1 (2013-05-14)

* More tests added.
* Travis and Coveralls integration.
* JavaJmx#setAttribute className parameter bug fixed.
* JavaJmx#invoke and javaJmx#setAttribute function parameters management improved.

## 0.1.0 (2013-05-06)

* The first published version.
