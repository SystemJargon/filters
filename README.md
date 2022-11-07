## About

Powered by [Github actions](https://github.com/features/actions) and [@adguard/hostlist-compiler](https://github.com/AdguardTeam/FiltersCompiler)

Automate/schedule (cron) a workflow of the many adlists, security lists, telemetry, annoyance lists etc. via Aggregation.

Lists are defined in this repo in the source directory. Each list then defined in a JSON file.


### Status

[![Update File](https://github.com/SystemJargon/filters/actions/workflows/main.yml/badge.svg)](https://github.com/SystemJargon/filters/actions/workflows/main.yml)

<!-- [![GitHub stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/forks/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/issues/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) -->


[![last commit](https://img.shields.io/github/last-commit/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master)

<!--
[![commit activity](https://img.shields.io/github/commit-activity/y/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master) -->

----

## Using the files in your Adblock solution.

Use the RAW files linked below of this repo's [README.md](README.md) file in your AdGuard/Adblock solution. 

All lists (so the lines within) will have comments stripped, compression, syntax validated and deduplicated. 

This is mostly to ensure file sizes (plus download/update times) are managable and future scalable.

Most of the lists are aggregated across various sources. Some are from my [blocklists](https://github.com/systemjargon/blocklists) repo.


----

## RAW lists links - (add to your Adblocker)

[Lite list](https://raw.githubusercontent.com/systemjargon/filters/main/lite.txt)

[Porn list](https://raw.githubusercontent.com//systemjargon/filters/main/porn.txt)

[Security list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt) - Anti phishing/scam/coinminer/malware/bad reputation

[Security list 2](https://raw.githubusercontent.com/systemjargon/filters/main/security2.txt) - replaced by [Security list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt)

[Extra list](https://raw.githubusercontent.com/systemjargon/filters/main/extra.txt)

[Telemetry list](https://raw.githubusercontent.com/systemjargon/filters/main/telemetry.txt)

[Other list](https://raw.githubusercontent.com/systemjargon/filters/main/other.txt)

[FireBog Ticklist](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt) - mostly adblocking

----

### Recommended combination of lists

Use the [FireBog Ticklist](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt + [Telemetry list](https://raw.githubusercontent.com/systemjargon/filters/main/telemetry.txt) + [Security list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt) 

----

## Notes

I have other repos around blocklists, allowlists, pi-hole, adguardhome and more if you're interested.

<i>There maybe some crossover duplicates on the Firebog ticklist and the lists above, that is due to Firebog sometimes changes what is on the ticklists.</i>

Star the repo if you like it!
