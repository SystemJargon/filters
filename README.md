## About

Powered by [Github actions](https://github.com/features/actions) and [@adguard/hostlist-compiler](https://github.com/AdguardTeam/FiltersCompiler)

Automate/schedule (cron) a workflow of the many adlists, security lists, annoyance lists etc.

Lists are defined in this repo in the [source](source) directory. Each list then defined in a JSON file.


### Status

[![Update File](https://github.com/SystemJargon/filters/actions/workflows/main.yml/badge.svg)](https://github.com/SystemJargon/filters/actions/workflows/main.yml)

<!-- [![GitHub stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/forks/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/issues/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) -->


[![last commit](https://img.shields.io/github/last-commit/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master)

<!--
[![commit activity](https://img.shields.io/github/commit-activity/y/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master) -->

----

## Using the files in your Adblock solution.

Use the text (txt) files in the root directory of this repo in your AdGuard/Adblock solution. 

All lists (so the lines within) will have comments stripped, compression, syntax validated and deduplicated. 

This is mostly to ensure file sizes (plus download/update times) are managable and future scalable.

Most of the lists are aggregated across various sources. Some are from my [blocklists](https://github.com/systemjargon/blocklists) repo.


----


[Main list](https://raw.githubusercontent.com/systemjargon/filters/main/filter.txt)

[Extra list](https://raw.githubusercontent.com/systemjargon/filters/main/extra.txt)

[Lite list](https://raw.githubusercontent.com/systemjargon/filters/main/lite.txt)

[Porn list](https://raw.githubusercontent.com//systemjargon/filters/main/porn.txt)

[Security list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt)

[Telemetry list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt)

[Other list](https://raw.githubusercontent.com/systemjargon/filters/main/other.txt)

[FireBog Ticklist](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt)
