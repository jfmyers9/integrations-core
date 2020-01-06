# CHANGELOG - Envoy

## 1.11.0 / 2019-12-02

* [Added] Add new metrics for Redis. See [#4946](https://github.com/DataDog/integrations-core/pull/4946). Thanks [tony612](https://github.com/tony612).
* [Added] Add auth type to RequestsWrapper. See [#4708](https://github.com/DataDog/integrations-core/pull/4708).

## 1.10.0 / 2019-10-11

* [Added] Add xDS-related metrics. See [#4634](https://github.com/DataDog/integrations-core/pull/4634). Thanks [csssuf](https://github.com/csssuf).
* [Added] Add option to override KRB5CCNAME env var. See [#4578](https://github.com/DataDog/integrations-core/pull/4578).

## 1.9.0 / 2019-08-24

* [Added] Add RequestsWrapper to envoy. See [#4120](https://github.com/DataDog/integrations-core/pull/4120).

## 1.8.0 / 2019-07-04

* [Added] Add cluster.ssl metrics to Envoy integration. See [#3976](https://github.com/DataDog/integrations-core/pull/3976). Thanks [csssuf](https://github.com/csssuf).
* [Added] Add Envoy upstream_rq_completed cluster metrics. See [#3955](https://github.com/DataDog/integrations-core/pull/3955). Thanks [csssuf](https://github.com/csssuf).

## 1.7.0 / 2019-06-19

* [Added] Add more listener metrics. See [#3922](https://github.com/DataDog/integrations-core/pull/3922).

## 1.6.0 / 2019-06-18

* [Added] Add logs config to envoy. See [#3918](https://github.com/DataDog/integrations-core/pull/3918).

## 1.5.0 / 2019-03-29

* [Added] Adhere to style. See [#3366](https://github.com/DataDog/integrations-core/pull/3366).

## 1.4.0 / 2018-09-05

* [Changed] Change order of precedence of whitelist and blacklist for pattern filtering. See [#2174][1].

## 1.3.0 / 2018-08-06

* [Added] Add ability to whitelist/blacklist metrics. See [#1975][2].
* [Changed] Add data files to the wheel package. See [#1727][3].

## 1.2.1 / 2018-06-14

* [Fixed] properly send tags for histograms. See [#1741][4].

## 1.2.0 / 2018-06-07

* [Added] support histograms, fix count submission. See [#1616][5].

## 1.1.0 / 2018-05-11

* [FEATURE] add newly-documented metrics. See #1326
* [IMPROVEMENT] tags can now contain the dot metric delimiter itself. See #1404

## 1.0.0 / 2018-03-23

* [FEATURE] add Envoy integration. See #1156

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2174
[2]: https://github.com/DataDog/integrations-core/pull/1975
[3]: https://github.com/DataDog/integrations-core/pull/1727
[4]: https://github.com/DataDog/integrations-core/pull/1741
[5]: https://github.com/DataDog/integrations-core/pull/1616