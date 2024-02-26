# Examples of Ransomware Scams

Below are several well known ransomware attacks as per a blog post on [Cobalt.io](https://www.cobalt.io/blog/11-biggest-ransomware-attacks-in-history).

## ExPetr / NotPetya

A (suspected russion sponsored) attack that was designed to target Ukraine, it used an SMB (Server Message Block) called [EternalBlue](https://www.avast.com/c-eternalblue) that was originally developed by the [United States National Security Agency](https://blogs.microsoft.com/on-the-issues/2017/05/14/need-urgent-collective-action-keep-people-safe-online-lessons-last-weeks-cyberattack/). Once on a system, the master boot record (MBR) was encrytpted to make systems unbootable as it spread throught the infected network.

- **Type**: SMB Vulnerability
- **Occured**: 2017
- **Estimated Impacct**: ~ $10 Billion

## GrandCrab

GrandCrab was a ransomware attack that spread through "kits" that [licenced to affiliates](https://www.zdnet.com/article/ransomware-crooks-test-a-new-way-to-spread-their-malware/) and shared back a percentage of the profits from the RaaS. Primarily caused through phishing emails and [exploit kits](https://www.trendmicro.com/vinfo/us/security/definition/exploit-kit), the creators of GrandCrab were supposedly able to earn themselves retirement according to a [blog post](https://www.bleepingcomputer.com/news/security/gandcrab-ransomware-shutting-down-after-claiming-to-earn-2-billion/).

- **Type**: Ransomware-as-a-service (RaaS)
- **Occured**: 2018-2019
- **Estimated Impacct**: ~ $2 Billion

## Locky

Locky was a ransomware strain that tarketed various healthcare providers across the world, spreading their malicious word document through a [massivev phishing campaign](https://arstechnica.com/information-technology/2016/02/locky-crypto-ransomware-rides-in-on-malicious-word-document-macro/). Once on the system, it would encryped the data files and filenames of anything it had access to, including network shares.

- **Type**: Ransomware spread through Microsoft Word macros
- **Occured**: 2016-2018
- **Estimated Impacct**: ~ $1 Billion

## REvil/Sodinokibi

REvil was released by the `REvil Group` that started off slow in 2019 and took of in 2020. While their attack methods changed regularely, one of their main methods was to trick users into downloading the ransomware through phishing emails or exploits in remote desktop protocols. Once inside, the group would begin their work.

- **Type**: Ransomeware (zero day)
- **Occured**: 2019-2021
- **Estimated Impacct**: ~ $70 Million

<hr>

[What do you do to get help from ransomware](/get-help-ransom.md)?
