+++
title = "Colophon"
date = "2026-07-12"
aliases = ["colophon","about-website"]
author = "JulHCam"
+++

## Favicon

The icon for the website was designed using [Inkscape](https://inkscape.org/) with the same colour palette as the website. The inspiration is to use dots and lines to represent the letters JHC in morse code, arranged in three lines. I then used [RealFaviconGenerator](https://realfavicongenerator.net/) to ensure that I had the right files placed on my website.

{{< imgresize src="/favicon.svg" width="30%" alt="Website Icon" >}}

## Website generator

I use the static website generator [Hugo](https://gohugo.io/) with the [Archie](https://github.com/athul/archie) theme, although I have my own [fork](https://github.com/JulioHC00/archie) since I had to make some changes for it to fit my website.

## Hosting and domain

My website is hosted in [infomaniak](https://www.infomaniak.com/en), from which I also got my domain. That means the server is served from European servers. I keep my sourcecode in github and the VPS where I host the website regularly checks for new commits and rebuilds the website.

## Analytics, Security and Privacy

I use [GoAccess](https://goaccess.io/), self-hosted on the same VPS as this website, to see basic visitor statistics. IP addresses are anonymized before being included in reports using GoAccess' IP anonymization feature (`--anonymize-ip --anonymize-level=2`). These reports are private and only accessible by me.

This site uses [CrowdSec](https://www.crowdsec.net/) to help protect against malicious traffic. Normal browsing activity is not shared with the CrowdSec community. If CrowdSec detects activity that appears to be malicious or abusive, a security alert and related technical information may be shared with the CrowdSec community to help improve protection for everyone. You can read more in the [CrowdSec Privacy Policy](https://www.crowdsec.net/privacy-policy).

Comments are powered by [Isso](https://isso-comments.de/), which runs on the same VPS as this website. Comments are stored here and are visible publicly after posting. Some technical information may be processed for moderation and abuse prevention. If you leave a comment, Isso may use a necessary cookie to let you manage your own comment. It is not used for tracking.

I do not use advertising trackers, tracking cookies, or third-party analytics.
