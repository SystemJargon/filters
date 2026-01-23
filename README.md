![GitHub last commit](https://img.shields.io/github/last-commit/systemjargon/filters)![GitHub issues](https://img.shields.io/github/issues/systemjargon/filters)![GitHub closed issues](https://img.shields.io/github/issues-closed/systemjargon/filters)![GitHub repo size](https://img.shields.io/github/repo-size/systemjargon/filters)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsystemjargon%2Ffilters&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/systemjargon/filters)[![shields.io Stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers)
----

## Filters

Because Ads, Telemetry and some content and/or domains are just out right **** that should be blocked. 

Lists are to be used with something alike Pi-Hole, AdGuard, AdGuardHome or similar. These lists may also work in browser based adblockers, but would need to interpret adblock/hosts formats.

This Repo should automatically update lists on a regular basis.

Some content may require an allowlist though to not break parts of the internet you use.


Leaving a :star: is much appreciated

Stats click [here](https://github.com/SystemJargon/filters/blob/main/stats/list-entries-stats.txt)

----


Help and other info about this repo beyond this README maybe available in the [wiki](https://github.com/SystemJargon/filters/wiki)

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

| List Type | File | Description |
|--------|------|-------------|
| ✅ | [Allowlist](allowlist.txt) | Allow list for common services and sites |
| 🚫 | [Core list](core.txt) | A Normal blocklist, but without much risk of False positives or things being blocked |
| 🚫 | [Core Light list](core_light.txt) | Lighter than the normal blocklist. Much less risk of False positives or things being blocked |
| 🚫 | [Core Heavy list](core_heavy.txt) | Heavy list. More sources aggregated from Ads, Phishing, Telemetry, Threats, Scams, Malware and more. More risk of False positives or things being blocked and needing an allowlist. This also uses my Ads, Security, Threats, Phishing lists. |
| 🚫 | [Porn list](porn.txt) | Blocklist well beyond 1 million entries across several lists for porn |
| 🚫 | [Threats list](threats.txt) | Blocklist aggregated from multiple blocklists. Covers phishing, spam, scam, coinminer, malware, bad reputation categories and general security. This list also combines lists known as compromised domains, phishing and security. |
| 🚫 | [Telemetry list](telemetry.txt) | Big custom blocklist for Telemetry via SmartTV, Amazon, Windows, Android, iOS, and additional Firebog telemetry lists |
| 🚫 | [Advertising list](ads.txt) | Blocklist which is some of my own and aggregated popular adlists across Github and other places |
| 🚫 | [FireBog Ticklist](firebog-ticklist.txt) | The blocklists which feature on the [Firebog ticklist here](https://v.firebog.net/hosts/lists.php?type=tick) |
| 🚫 | [Restrict-ByPass list](restrict-bypass.txt) | My own curated list with supplement lists aggregated. The Blocklist is to prevent using other DNS or bypass methods like Tor, proxy, Apple Relay, etc. |
| 🚫 | [Restrict-ByPass User_Child list](restrict-bypass-user_child.txt) | My own curated list with supplement lists aggregated. This differs from restrict-bypass.txt to add <b>user_child</b> to the end of domains. This is a feature in AdGuardHome where you tag devices accordingly with this. The overall list of domains is the same as restrict-bypass.txt. Blocklist is to prevent using other DNS or bypass methods like Tor, proxy, Apple Relay, etc. |
| 🚫 | [No Social Media list](no-social-media.txt) | Blocklist aggregated of known domains of social media. This covers Facebook, Insta, Snapchat, TikTok and more. |
| 🚫 | [No Social Media list User_Child list](no-social-media-user_child.txt) | Blocklist aggregated of known domains of social media. This covers Facebook, Insta, Snapchat, TikTok and more. This differs from no-social-media.txt to add <b>user_child</b> to the end of domains. This is a feature in AdGuardHome where you tag devices accordingly with this. The overall list of domains is the same as no-social-media.txt |

----

### M$ potential charging for GitHub actions

This repo (and some other repos by other users) relies on GitHub actions.

M$ aka Microsoft want to introduce and start charging for Github actions. 

This repo and many others which operate as self-hosted runners or likewise via Github actions, may cease to be up-to-date or exist if Microsoft (Github as a company) charge for Actions.


[One of probably many Reddit Links discussing this](https://www.reddit.com/r/devops/comments/1po8hj5/github_actions_introducing_a_perminute_fee_for/)
