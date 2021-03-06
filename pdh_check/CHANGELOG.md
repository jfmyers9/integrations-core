# CHANGELOG - pdh_check

## 1.12.0 / 2020-08-10

* [Added] Add config spec. See [#7153](https://github.com/DataDog/integrations-core/pull/7153).

## 1.11.0 / 2020-06-29

* [Added] Upgrade pywin32 to 228. See [#6980](https://github.com/DataDog/integrations-core/pull/6980).

## 1.10.0 / 2020-05-17

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.9.1 / 2020-04-04

* [Fixed] PDH check to use new agent signature. See [#6159](https://github.com/DataDog/integrations-core/pull/6159).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.9.0 / 2020-01-21

* [Added] Make the admin share configurable. See [#5485](https://github.com/DataDog/integrations-core/pull/5485).

## 1.8.0 / 2019-12-02

* [Added] Upgrade pywin32 to 227. See [#5036](https://github.com/DataDog/integrations-core/pull/5036).

## 1.7.0 / 2019-10-11

* [Added] Upgrade pywin32 to 225. See [#4563](https://github.com/DataDog/integrations-core/pull/4563).

## 1.6.1 / 2019-06-18

* [Fixed] Rename lower case manifest.in. See [#3858](https://github.com/DataDog/integrations-core/pull/3858).

## 1.6.0 / 2019-06-01

* [Added] Make PDHCheck use PDHBaseCHeck. See [#3818](https://github.com/DataDog/integrations-core/pull/3818).

## 1.5.0 / 2019-05-14

* [Added] Adhere to code style. See [#3553](https://github.com/DataDog/integrations-core/pull/3553).

## 1.4.0 / 2019-02-18

* [Fixed] Fix flake8. See [#3077](https://github.com/DataDog/integrations-core/pull/3077).
* [Added] Support Python 3. See [#3049](https://github.com/DataDog/integrations-core/pull/3049).

## 1.3.0 / 2018-10-12

* [Added] Pin pywin32 dependency. See [#2322][1].

## 1.2.1 / 2018-09-04

* [Fixed] Add data files to the wheel package. See [#1727][2].

## 1.2.0 / 2018-05-11

* [Update] Update to new wheels packaging and unit test framework
* [BUGFIX] Added resilience to failed import of `WinPDHCounter`. [#1183][3]
* [SANITY] Use `WinPDHCounter` shipped with `datadog-checks-base` wheel. [#1183][3]

## 1.1.0 / 2018-01-10

* [BUGFIX] Fix tag key-value separator. [#927][4]

## 1.0.0 / 2017-10-10

* [FEATURE] adds pdh_check integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2322
[2]: https://github.com/DataDog/integrations-core/pull/1727
[3]: https://github.com/DataDog/integrations-core/issues/1183
[4]: https://github.com/DataDog/integrations-core/issues/927
