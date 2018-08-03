# Sweden [![awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) list

A curated list of awesome things to use when coding for the Swedish market.

## Content

- [Finance](#finance)
- [People](#people)
- [Job Market](#job-market)
- [Misc](#misc)
- A __[wish list](#wish-list)__ of things we'd like to see libraries for

:information_source: If you're looking to add a library please check the [contributing guide](#contributing).

## People

- Validate Swedish SSN/personnummer
  + [Ruby](https://github.com/c7/personnummer) (well tested)
  + [Ruby](https://github.com/personnummer/ruby)
  + [JavaScript](https://github.com/arokor/pernr)
  + [JavaScript](https://github.com/personnummer/js)
  + [Python](https://github.com/personnummer/python)
  + [PHP](https://github.com/personnummer/php)
  + [Swift](https://github.com/personnummer/swift)
  + [Java](https://github.com/personnummer/java)
  + [C#](https://github.com/personnummer/csharp)
  + [Go](https://github.com/personnummer/go)
  + Various other implementations are available under [this GitHub organization](https://github.com/personnummer), please note that some listed there are still WIP.

## Finance

- Validate Swedish bank accounts
  + [Ruby](https://github.com/barsoom/banktools-se)
- Make BGC supplier payment files (a.k.a "leverantörsbetalningar")
  + [Ruby](https://github.com/barsoom/supplier_payments)
- Payments using DebiTech (DIBS)
  + [Ruby](https://github.com/barsoom/debitech)
- Parse and generate SIE-files (open format for accounting data)
  + [Ruby](https://github.com/barsoom/sie)

## Job market

- Build a feed for Metrojobb
  + [Ruby](https://github.com/buren/metrojobb)
- API client for Arbetsförmedlingen
  + [Ruby](https://github.com/buren/arbetsformedlingen)
- Post jobs to Arbetsförmedlingen
  + [JavaScript](https://github.com/othermachines/platsbanken-vacancy)
  + [Ruby](https://github.com/buren/arbetsformedlingen)

## Misc

- API client for Bilvision API (car register service a.k.a "Bilregistertjänst")
  + [Ruby](https://github.com/sandelius/bilvision)
- [MMS](http://mms.se/) API client (analyzes TV consumption in Sweden)
  + [Go](https://github.com/TV4/mms)
- Translates SAB (Swedish library classification system) codes to, human readable, Swedish subject
  + [Ruby](https://github.com/c7/ur-sab)

## Wish list

Libraries we wished existed.

- Bank account validation in more languages than Ruby
- BankID tools
- [Stockholm API](http://api.stockholm.se/dokumentation/)
- [Swedish Police events API](https://polisen.se/om-polisen/om-webbplatsen/oppna-data/api-over-polisens-handelser/)
- Zip/Postnummer reverse lookup
- ... anything you'd like to add?

## Contributing

Contributions, feedback and suggestions are very welcome.

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
