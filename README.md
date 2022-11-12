## About

A repo in a series of filters from original and aggregated sources. To be used with an AdGuard or EasyList Adblocker.


Automate/schedule (cron) a workflow of the many adlists, security lists, telemetry, annoyance lists etc. via <b>Aggregation</b>.

Lists are defined in this repo in the source directory. Each list then defined in a JSON file.


### Status

[![Update File](https://github.com/SystemJargon/filters/actions/workflows/main.yml/badge.svg)](https://github.com/SystemJargon/filters/actions/workflows/main.yml) [![HitCount](https://hits.dwyl.com/systemjargon/filters.svg?style=flat&show=unique)](http://hits.dwyl.com/systemjargon/filters) [![GitHub stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/forks/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub stars](https://img.shields.io/github/issues/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![last commit](https://img.shields.io/github/last-commit/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master) [![commit activity](https://img.shields.io/github/commit-activity/y/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master)

----

## Using the files in your Adblock solution.

Use the RAW files linked below of this repo's [README.md](README.md) file in your AdGuard/Adblock solution. 

All lists (so the lines within) will have comments stripped, compression, syntax validated and deduplicated. 

This is mostly to ensure file sizes (plus download/update times) are managable and future scalable.

Most of the lists are aggregated across various sources. Some are from my [blocklists](https://github.com/systemjargon/blocklists) repo.


----

## RAW lists links - (add to your Adblocker)

[Core list](https://raw.githubusercontent.com/systemjargon/filters/main/core.txt) - RECOMMENDED - BIG - StevenBlackHosts, Adguard DNS Filter, OISD, Firebog ticklists

[Porn list](https://raw.githubusercontent.com//systemjargon/filters/main/porn.txt) - BIG - well beyond 1.5 million entries across several lists. * as of this commit - may change.

[Security list](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt) - Anti phishing/scam/coinminer/malware/bad reputation

[Telemetry list](https://raw.githubusercontent.com/systemjargon/filters/main/telemetry.txt) - SmartTV, Amazon, Windows, Android, iOS. Includes also Firebog telemetry lists and others.

[Advertising list](https://raw.githubusercontent.com/systemjargon/filters/main/ads.txt) - Popular adlists across Github and other places.

[FireBog Ticklist](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt) - Lists located [here](https://v.firebog.net/hosts/lists.php?type=tick)

----

## Notes

I have other repos around blocklists, allowlists, pi-hole, adguardhome and more if you're interested.

I won't re-aggregate ALL of StevenBlack's lists into one list - they are too big to combine.

<i>There maybe some crossover duplicates on the Firebog ticklist and the lists above, that is due to Firebog sometimes changes what is on the ticklists.</i>

Star the repo if you like it!
