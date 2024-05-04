![GitHub last commit](https://img.shields.io/github/last-commit/systemjargon/filters)![GitHub issues](https://img.shields.io/github/issues/systemjargon/filters)![GitHub closed issues](https://img.shields.io/github/issues-closed/systemjargon/filters)![GitHub repo size](https://img.shields.io/github/repo-size/systemjargon/filters)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsystemjargon%2Ffilters&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/systemjargon/filters)[![shields.io Stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers)
----

## DNS Blocklists & Allowlist/s

Because Ads, Telemetry and some content and/or domains are just out right **** that should be blocked.

Lists are to be used with something alike Pi-Hole, AdGuard, AdGuardHome or similar. These lists may also work in browser based adblockers, but would need to interpret adblock/hosts formats.

I provide adblock and hosts formats currently. I can make lists in other formats on request if you create an issue (request).

Info about formats using [Pi-Hole](https://pi-hole.net/blog/2023/03/22/pi-hole-ftl-v5-22-web-v5-19-and-core-v5-16-1-released#page-content) [Adblock](https://easylist.to/) and [AdGuard](https://adguard.com/kb/general/ad-filtering/create-own-filters/)

This Repo is scheduled to automatically update (and it's lists) on a schedule regularly.

Leaving a :star: is much appreciated

----


Use the RAW files [linked](#the-lists) below this [README](https://github.com/SystemJargon/filters/blob/main/README.md) file in your AdGuard/Adblock solution. 

Notes:

* Some lists are defined as a 🚫 blocklist or some an ✅ allowlist. Each list has a description or purpose for what it does, i.e allow, block telemetry.

* All lists will have syntax validated and be de-duplicated. Some may have comments stripped. This is mostly to ensure file sizes and length are usable and scalable.

* The aggregation of lists are either my own lists, repositories and other well curated lists.

<!--* If you want my big Social Media Blocklist, see [here](https://github.com/SystemJargon/blocklists/blob/main/lists/categories/social-media/SystemJargon_Block_SocialMedia_AG.txt) or look in my blocklists repo under the Category of Social Media [here](https://github.com/SystemJargon/blocklists/blob/main/lists/categories/social-media) Add the no-social-media list -->

* Again feel free to 🌟/star the repo.

* Raise any issues or requests [here](https://github.com/SystemJargon/filters/issues/new/choose) 

----

## The Lists

| List Type | File | Raw Link | Description |
|--------|------|----------|-------------|
| ✅ | [Allowlist](allowlist.txt) | [Raw Link](https://raw.githubusercontent.com/SystemJargon/filters/main/allowlist.txt) | Allow list for common services and sites |
| 🚫 | [Core list](core.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/core.txt) | Blocklist core aggregated lists of StevenBlack Hosts, Adguard DNS Filter, Hagezi Multi Normal list, Firebog tick list |
| 🚫 | [Porn list](porn.txt) | [Raw Link](https://raw.githubusercontent.com//systemjargon/filters/main/porn.txt) | Blocklist well beyond 1 million entries across several lists for porn |
| 🚫 | [Security list](security.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt) | Blocklist aggregated from other well-curated lists which do not appear in phishing.txt nor firebog-ticklist.txt as of the time of commit |
| 🚫 | [Phishing list](phishing.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/phishing.txt) | Blocklist aggregated from other well-curated lists exclusively for phishing |
| 🚫 | [Threats list](threats.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/threats.txt) | Blocklist aggregated from my own multiple blocklists, anti-phishing/scam/coinminer/malware/bad reputation categories |
| 🚫 | [Telemetry list](telemetry.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/telemetry.txt) | Big custom blocklist for Telemetry via SmartTV, Amazon, Windows, Android, iOS, and additional Firebog telemetry lists |
| 🚫 | [Advertising list](ads.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/ads.txt) | Blocklist which is some of my own and aggregated popular adlists across Github and other places |
| 🚫 | [FireBog Ticklist](firebog-ticklist.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt) | The blocklists which feature on the [Firebog ticklist here](https://v.firebog.net/hosts/lists.php?type=tick) |
| 🚫 | [Restrict-ByPass list](restrict-bypass.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/restrict-bypass.txt) | My own curated list with supplement lists aggregated. The Blocklist is to prevent using other DNS or bypass methods like Tor, proxy, Apple Relay, etc. |
| 🚫 | [Restrict-ByPass User_Child list](restrict-bypass-user_child.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/restrict-bypass-user_child.txt) | My own curated list with supplement lists aggregated. This differs from restrict-bypass.txt to add <b>user_child</b> to the end of domains. This is a feature in AdGuardHome where you tag devices accordingly with this. The overall list of domains is the same as restrict-bypass.txt. Blocklist is to prevent using other DNS or bypass methods like Tor, proxy, Apple Relay, etc. |
| 🚫 | [NRDs list](nrds-30days.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/nrds-30days.txt) | Blocklist aggregated from Newly Registered Domains lists. These are NRDs registered in the last 30 days. |
| 🚫 | [No Social Media list](no-social-media.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/no-social-media.txt) | Blocklist aggregated of known domains of social media. This covers Facebook, Insta, Snapchat, TikTok and more. |

----


