# <img src="Logotype.png" title="Omni-Link" alt="Omni-Link"/>

![Draft](https://img.shields.io/badge/Draft-In%20progress-yellow.svg) ![Not implemented](https://img.shields.io/badge/Status-Not%20implemented-red.svg)

The spec that the Web 3.0 is needing.
Same content, linked in any place, also integrated with Plugzle.

# Principles

## Omni-Presence

Same post/issue/content, linked in any network with JSON's "omni" array.

Sites/content/social networks that doesn't natively supports omni-link, can also link: for example, posting omni-links as a comment on your Instagram photo, which also links to same DeviantArt one.

Namecoin is already a begin of Omni-Link: a .bit domain can link to multiple sources (www, zeronet, ipfs, dat, ssb). Same for Emercoin and ENS (Ethereum Name Service).

## Omni-Adapt

Pages are rendered differently depending on platform (thanks to FrameworkJS).
Instead of common elements, the ones you want to display only case on a specific platform (WWW, Dat, IPFS) you put into platform-specific tags.

It also enables to point different links depending on platform (on IPFS, point only to specific social networks).

A lot of use-cases can be applyed; it is platform-related localization of content and its links.

## Omni-Recite

Instead of duplicating the same text on same network (Omni-Link's purpose is to duplicate content only on different platforms), it gets text from sources.

With the Recite principle, you can get text in a Markdown doc or HTML site directly from a JSON file.

## To implement in:

- GoHugo and all site pages
- Omni-Recite in Hugo profile page (includes photo URLs with Omni-Presence)

## It also supports:

* [IPLD](https://ipld.io/)

## Contributing

This is a open-source and accessible spec, so you're welcome to open a issue (with criticism/suggestions) and open pull requests with improvements.
Please follow our <a href="http://www.contributor-covenant.org/" target="_blank">Code of Conduct</a> before interacting or contributing.

## Todo

- "omni" external scheme for Dat's Unwalled Garden spec
- Depends upon FrameworkJS modularization/components and its platform-aware rendering
- Support QRL
- bridges: deviantart+instagram+downloadedarchive+datphotoalbum
- bridges: any post in peepeth is considered peepeth when "via" is empty or begins with "peepeth", read other "via" values / peepeth profiles stored in OrbitDB
- browser extension for URL fallback (show if URL is available on other networks, rechognize fallback option in URL)

## Related links

