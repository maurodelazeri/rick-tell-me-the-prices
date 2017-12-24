## Rick is here to help you

Get cryptocurrency prices on terminal.

Uses data from [CoinMarketCap API](https://coinmarketcap.com/api/).

### Obtaining

    go get github.com/maurodelazeri/rick-tell-me-the-prices

### Usage

```
Usage of ./rick-tell-me-the-prices:
  -currency string
        Currency for price and market cap data.
        Valid currencies are: USD, AUD, BRL, BGN, CAD, CHF, CLP, CNY, CZK, DKK, EUR, GBP, HKD, HUF, IDR, ILS, INR, JPY, KRW, MXN, MYR, NOK, NZD, PHP, PKR, PLN, RUB, SEK, SGD, THB, TRY, TWD, ZAR (default "USD")
  -limit uint
        Default number of currencies. (default 10)
```

By default, `rick-tell-me-the-prices` limits the number of currencies to 10 and displays the
currency data in USD.

The quotes are refreshed every 1 minutes.
