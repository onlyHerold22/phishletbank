<p align="center">
  <img alt="Evilginx2 Logo" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-logo-512.png" height="160" />
  <p align="center">
    <img alt="Evilginx2 Title" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-title-black-512.png" height="60" />
  </p>
</p>
<p align="center">
<a href="https://github.com/Ignitetch/AdvPhishing/releases"><img title="GitHub version" src="https://img.shields.io/badge/version-2.3.0-blue" ></a>  
</p>
<p align="center">
<a href="https://github.com/Ignitetch/AdvPhishing/releases"><img title="GitHub version" src="https://img.shields.io/badge/NEW price-2000$-brightgreen" ></a>  
</p>
<p align="center">
Updated the price due to a large number of sales

![Twitter URL](https://img.shields.io/twitter/url?style=for-the-badge&url=https%3A%2F%2Ftwitter.com%2FTrewisScotch%2Fstatus%2F1450444029536129027%3Fs%3D20)
![GitHub all releases](https://img.shields.io/github/downloads/trewisscotch/PHISHLET-EVILGINX2-/total?label=TREWIS%20%5BHIRO%5D%20SCOTCH&logo=C&style=for-the-badge)

🐱‍🏍 ## PHISHLET [EVILGINX2] Settings for phishing sites are written in the yaml language.

## Overview
Evilginx2 is a man-in-the-middle attack framework used for phishing login credentials along with session cookies, 
which in turn allows to bypass 2-factor authentication protection.

This is a long development of my collection that I have been working on for the last 3 months due to changes in site security rules in particular scripts for bypassing the CloudFlare security.

🙌 I PRESENT to you my collection from the sites :

****1Password / Binance / Bitfinex / Bittrex / Bitwarden / Blockchain / Cex.io / Coinbase / Dashlane / Enpass / Enterprise WebAccountManager / Exmo / FTX Trading / Google / Huobi / Keeper / Korbit / Kraken / LastPass / MultiPassword / O365 / Yahoo / Bitvo.com / Canadianbitcoins.com / Liquid.com / Litebit.com / Mybtc.ca / Netcoins.com / opensea / Shakepay.co / Citibank / Deutsche Bank / Chase / BOA / Wells Fargo / Bank of New York Mellon / Capital One / Suntrust ****

## Usage

**IMPORTANT!** Make sure that there is no service listening on ports `TCP 443`, `TCP 80` and `UDP 53`. You may need to shutdown apache or nginx and any service used for resolving DNS that may be running. **evilginx2** will tell you on launch if it fails to open a listening socket on any of these ports.

By default, **evilginx2** will look for phishlets in `./phishlets/` directory and later in `/usr/share/evilginx/phishlets/`. If you want to specify a custom path to load phishlets from, use the `-p <phishlets_dir_path>` parameter when launching the tool.

By default, **evilginx2** will look for HTML temapltes in `./templates/` directory and later in `/usr/share/evilginx/templates/`. If you want to specify a custom path to load HTML templates from, use the `-t <templates_dir_path>` parameter when launching the tool.

```
Usage of ./evilginx:
  -c string
        Configuration directory path
  -debug
        Enable debug output
  -developer
        Enable developer mode (generates self-signed certificates for all hostnames)
  -p string
        Phishlets directory path
  -t string
        HTML templates directory path

```

## Contributing

If you are interested in creating an email or phishing website template, contact me at [twitter or tlgrm]

## DEVELOPER DO NOT SUPPORT ANY OF THE ILLEGAL ACTIVITIES.

## Contact Me on telegram or twitter: https://twitter.com/TrewisScotch / https://t.me/HiroSCOTCH#

