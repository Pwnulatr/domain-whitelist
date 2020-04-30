# Pwnulatr's Domain Whitelist
This is a domain-only list that I personally use on my Pi-hole. I found that sometimes my blocklists were a bit
overzealous, so this list aims to fix this.

In this repo there will be a [domains](domains) file, accompanied by a [reasons](reasons) file. The domains file is
what you're looking for most likely, but if you want to understand the purpose of each domain in the whitelist, you're
free to browse the reasons file.
## Installation
**DO NOT** use the raw GitHub link to fetch and update the domains list. Instead use this
[jsDelivr link](https://cdn.jsdelivr.net/gh/pwnulatr/domain-whitelist/domains).
## Note
It is not recommended to use this list for element blockers, i.e. uBlock Origin, because some domains here do serve
tracking content in addition to functional content. For example, the `d21gpk1vhmjuf5.cloudfront.net` domain serves both
content for providing search functionality on Monoprice's website, but it also serves an analytics `js` file. Block
lists made for these element blockers do a better job at sorting out the difference, provided you have a good blacklist
source.
