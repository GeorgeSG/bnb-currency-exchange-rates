# Official exchange rates of the Bulgarian National Bank

[![Bulgarian National Bank - Official Currency Exchange Rates](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml/badge.svg?branch=main)](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml)

All exchange rates in the dataset are based on **Bulgarian Lev/BGN/Български лев** and are set as official rates by the [**Bulgarian National Bank**](https://www.bnb.bg/Statistics/StExternalSector/StExchangeRates/StERForeignCurrencies/index.htm?toLang=_EN).

This repository utilizes the [**schedule**](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) function of Github Actions in order to update the dataset through a continuously running cronjob.

# Available datasets

<!-- START LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->

Last Update: Sep 18, 2023, 5:07:01 PM GMT+0 (2023-09-18T17:07:01.887Z)

| Currency | URL                                                                                             | Number of records | Number of missing days that were filled in |
| :------: | ----------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------: |
|   AUD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/AUD.csv |       8978        |                    2767                    |
|   CAD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CAD.csv |       8978        |                    2767                    |
|   CHF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CHF.csv |       8978        |                    2767                    |
|   CZK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CZK.csv |       8978        |                    2767                    |
|   DKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/DKK.csv |       8978        |                    2767                    |
|   GBP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GBP.csv |       8978        |                    2767                    |
|   HUF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HUF.csv |       8978        |                    2767                    |
|   JPY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/JPY.csv |       8978        |                    2767                    |
|   NOK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NOK.csv |       8978        |                    2767                    |
|   NZD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NZD.csv |       8978        |                    2767                    |
|   PLN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PLN.csv |       8978        |                    2767                    |
|   SEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SEK.csv |       8978        |                    2767                    |
|   USD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/USD.csv |       8978        |                    2767                    |
|   XAU    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/XAU.csv |       8978        |                    2769                    |
|   HKD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HKD.csv |       8680        |                    2680                    |
|   KRW    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/KRW.csv |       8680        |                    2680                    |
|   SGD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SGD.csv |       8680        |                    2680                    |
|   ZAR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ZAR.csv |       8680        |                    2680                    |
|   TRY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRY.csv |       6805        |                    2107                    |
|   CNY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CNY.csv |       6687        |                    2073                    |
|   IDR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/IDR.csv |       6687        |                    2073                    |
|   MYR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MYR.csv |       6687        |                    2073                    |
|   PHP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PHP.csv |       6687        |                    2073                    |
|   THB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/THB.csv |       6687        |                    2073                    |
|   RON    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RON.csv |       6628        |                    2055                    |
|   HRK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HRK.csv |       6427        |                    1991                    |
|   RUB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RUB.csv |       6123        |                    1894                    |
|   ISK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ISK.csv |       5982        |                    1849                    |
|   BRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/BRL.csv |       5715        |                    1774                    |
|   MXN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MXN.csv |       5715        |                    1774                    |
|   LTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LTL.csv |       5510        |                    1685                    |
|   INR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/INR.csv |       5346        |                    1658                    |
|   LVL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LVL.csv |       5147        |                    1573                    |
|   ILS    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ILS.csv |       4622        |                    1439                    |
|   EEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/EEK.csv |       4353        |                    1325                    |
|   SKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SKK.csv |       3329        |                    1017                    |
|   CYP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CYP.csv |       3259        |                    989                     |
|   MTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MTL.csv |       2961        |                    902                     |
|   SIT    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SIT.csv |       2897        |                    879                     |
|   TRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRL.csv |       2171        |                    658                     |
|   ROL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ROL.csv |       2052        |                    625                     |
|   GRD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GRD.csv |        357        |                    105                     |

<!-- END LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->
