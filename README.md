# Sweden [![awesome](https://awesome.re/badge-flat.svg)](https://github.com/buren/awesome-sweden) list

A curated list of awesome things to use when coding for the Swedish market.

## Content

- [People](#people)
- [Companies](#companies)
- [Finance](#finance)
- [Authentication](#authentication)
- [Job Market](#job-market)
- [Transportation](#transportation)
- [Regional](#regional)
- [Geographic](#geographic)
- [Media](#media)
- [Misc](#misc)
- :link: [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets)
- A __[wish list](#wish-list)__ of things we'd like to see libraries for

:information_source:
- Looking for datasets? See [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets).
- If you're looking to add a library please check the [contributing guide](#contributing).

## People

- Validate Swedish Personal Identity Number (personnummer / SSN)
  + [Ruby](https://github.com/c7/personnummer) (well tested)
  + [Ruby](https://github.com/personnummer/ruby)
  + [JavaScript](https://github.com/jonathanp/swedish-personal-identity-number-validator)
  + [JavaScript](https://github.com/arokor/pernr)
  + [JavaScript](https://github.com/personnummer/js)
  + [Python](https://github.com/personnummer/python)
  + [PHP](https://github.com/personnummer/php)
  + [PHP](https://github.com/byrokrat/id)
  + [Swift](https://github.com/personnummer/swift)
  + [Java](https://github.com/personnummer/java)
  + [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Identity) (Also parses and normalizes the Personal Identity Number)
  + [Go](https://github.com/personnummer/go)
  + Various other implementations are available under [this GitHub organization](https://github.com/personnummer), please note that some listed there are still WIP.
- Statens personadressregister
  + [JavaScript](https://github.com/Yepstr/node-statenspersonadressregister)
  + [Reference implementations (PHP/C#/Java)](https://github.com/Statenspersonadressregister)

## Companies

- Validate Swedish Company Registration Number (organisationsnummer)
  + [Ruby](https://github.com/mirendo/orgnummer)
  + [JavaScript](https://github.com/perarnborg/se-org-no)
  + [PHP](https://github.com/byrokrat/id)
  + [JavaScript](https://github.com/eckberg/se-orgnr-validator)

## Finance

- Swish Merchant API
  + [Go](https://github.com/frozzare/go-swish)
  + [Rust](https://github.com/drager/swish)
  + [JavaScript](https://github.com/carlbarrdahl/swish-payments) &mdash; Not actively [being maintained](https://github.com/buren/awesome-sweden/issues/15).
- Validate Swedish bank accounts
  + [Ruby](https://github.com/barsoom/banktools-se)
- Make BGC supplier payment files (a.k.a "leverantörsbetalningar")
  + [Ruby](https://github.com/barsoom/supplier_payments)
- Payments using DebiTech (DIBS)
  + [Ruby](https://github.com/barsoom/debitech)
- Parse and generate SIE-files (open format for accounting data)
  + [Ruby](https://github.com/barsoom/sie)
- Retrieve interest and exchange rates from the Swedish central bank
  + [Go](https://github.com/zeeraw/riksbank)

## Authentication

- Authentication using BankID
  + [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Authentication) (With authentication handler for ASP.NET)
  + [Android](https://github.com/spacecowboy/bankid-android-sample) (Sample implementation)
- Authentication using GrandID (Svensk E-Identitet)
  + [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Authentication) (With authentication handler for ASP.NET)

## Job market

- Build a feed for Metrojobb
  + [Ruby](https://github.com/buren/metrojobb)
- Arbetsförmedlingen API
  + [Ruby](https://github.com/buren/arbetsformedlingen)
- Post jobs to Arbetsförmedlingen
  + [JavaScript](https://github.com/othermachines/platsbanken-vacancy)
  + [Ruby](https://github.com/buren/arbetsformedlingen)

## Transportation

- SL API
  + [JavaScript](https://github.com/simon-johansson/SL-api)
  + [Go](https://github.com/frozzare/go-sl)
- Västtrafik API
  + [JavaScript](https://github.com/oskarhagberg/node-vasttrafik)
- Trafikverket API
  + [JavaScript](https://github.com/eduardoportilho/trafikverket)
- Bilvision API (car register service a.k.a "Bilregistertjänst")
  + [Ruby](https://github.com/sandelius/bilvision)

## Regional

:information_source: see the [transportation](#transportation) section for regional transportation.

- Stockholm API
  + [JavaScript](https://github.com/buren/stockholm-api)
- Göteborg (Gothenburg) API
  + [JavaScript](https://github.com/oskarhagberg/gbgcity)

## Geographic

- [SWEREF99 TM (EPSG:3006)](https://epsg.io/3006) projected coordinate system
  + [JavaScript](https://kartena.github.io/Proj4Leaflet)

## Media

- Sveriges Radio API
  + [JavaScript (CLI)](https://github.com/ollelauribostrom/sverigesradio)
- [MMS](http://mms.se/) API client (analyzes TV consumption in Sweden)
  + [Go](https://github.com/TV4/mms)
- Translates SAB (Swedish library classification system) codes to, human readable, Swedish subject
  + [Ruby](https://github.com/c7/ur-sab)

## Misc

- Kolada API - KPIs concerning Swedish municipalities and organizational units
  + [JavaScript](https://github.com/buren/kolada)
- Polisen API
  + [JavaScript](https://github.com/buren/polisen-api) - events and police stations
- SCB API (Statistiska Centralbyrån)
  + [JavaScript](https://www.npmjs.com/package/scb-api)
  + [Ruby](https://github.com/peterhellberg/scb)
- SMHI API
  + [C#](https://github.com/piksel/SMHISharp)
  + [JavaScript](https://github.com/thelinmichael/smhi-node)
  + [JavaScript](https://github.com/peterstark72/smhi-nodejs)
- Phone number formatter
  + [JavaScript](https://github.com/jonathanp/swedish-phone-number-formatter)
- Postal code validator
  + [JavaScript](https://github.com/jonathanp/swedish-postal-code-validator)
- Cardinal number converter
  + [JavaScript](https://github.com/jonathanp/swedish-cardinal-numbers)
- Booli API
  + [JavaScript](https://github.com/filipchr/node-booli)


## Wish list

Libraries and other things we wished existed or haven't heard of yet.

- Bank account validation in more languages than Ruby
- BankID tools in more languages
- [Swish](https://www.getswish.se/)
- Zip/Postnummer reverse lookup
- API Clients
  + [Statistikdatabasen](http://www.scb.se/om-scb/om-scb.se-och-anvandningsvillkor/oppna-data-api/api-for-statistikdatabasen/) (SCB)
  + APIs listed at https://www.trafiklab.se/api
- Hemnet
- PostNord API
- ... anything you'd like to add?

## Contributing

Contributions, feedback and suggestions are very welcome.

:information_source: Looking to add a dataset? See [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets).

__Before you start, make sure__

1. That it's directly related to building applications for the Swedish market (there are plenty of other awesome lists for other types of tools, [here](https://github.com/sindresorhus/awesome))
2. The library is not already added to this list
3. The library is somewhat stable

then

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
  - Make sure to clearly state what the library does and why its relevant (unless thats obvious)


## License

[Creative Commons CC0](LICENSE).

---

[![Build Status](https://travis-ci.com/buren/awesome-sweden.svg?branch=master)](https://travis-ci.com/buren/awesome-sweden) passing build means all URLs are 200.
