# Official exchange rates of the Bulgarian National Bank

[![Bulgarian National Bank - Official Currency Exchange Rates](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml/badge.svg?branch=main)](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml)

All exchange rates in the dataset are based on **Bulgarian Lev/BGN/Български лев** and are set as official rates by the [**Bulgarian National Bank**](https://www.bnb.bg/Statistics/StExternalSector/StExchangeRates/StERForeignCurrencies/index.htm?toLang=_EN).

This repository utilizes the [**schedule**](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) function of Github Actions in order to update the dataset through a continuously running cronjob.

# Available datasets

<!-- START LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->

Last Update: Mar 22, 2023, 5:06:27 PM GMT+0 (2023-03-22T17:06:27.695Z)

| Currency | URL                                                                                             | Number of records | Number of missing days that were filled in |
| :------: | ----------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------: |
|   AUD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/AUD.csv |       8570        |                    2648                    |
|   CAD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CAD.csv |       8570        |                    2648                    |
|   CHF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CHF.csv |       8570        |                    2648                    |
|   CZK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CZK.csv |       8570        |                    2648                    |
|   DKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/DKK.csv |       8570        |                    2648                    |
|   GBP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GBP.csv |       8570        |                    2648                    |
|   HUF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HUF.csv |       8570        |                    2648                    |
|   JPY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/JPY.csv |       8570        |                    2648                    |
|   NOK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NOK.csv |       8570        |                    2648                    |
|   NZD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NZD.csv |       8570        |                    2648                    |
|   PLN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PLN.csv |       8570        |                    2648                    |
|   SEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SEK.csv |       8570        |                    2648                    |
|   USD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/USD.csv |       8570        |                    2648                    |
|   XAU    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/XAU.csv |       8570        |                    2650                    |
|   HKD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HKD.csv |       8268        |                    2557                    |
|   KRW    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/KRW.csv |       8268        |                    2557                    |
|   SGD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SGD.csv |       8268        |                    2557                    |
|   ZAR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ZAR.csv |       8268        |                    2557                    |
|   TRY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRY.csv |       6750        |                    2087                    |
|   CNY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CNY.csv |       6630        |                    2051                    |
|   IDR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/IDR.csv |       6630        |                    2051                    |
|   MYR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MYR.csv |       6630        |                    2051                    |
|   PHP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PHP.csv |       6630        |                    2051                    |
|   THB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/THB.csv |       6630        |                    2051                    |
|   RON    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RON.csv |       6571        |                    2033                    |
|   HRK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HRK.csv |       6548        |                    2025                    |
|   RUB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RUB.csv |       6246        |                    1930                    |
|   BRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/BRL.csv |       5658        |                    1752                    |
|   MXN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MXN.csv |       5658        |                    1752                    |
|   ISK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ISK.csv |       5449        |                    1692                    |
|   INR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/INR.csv |       5293        |                    1640                    |
|   LTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LTL.csv |       5151        |                    1580                    |
|   LVL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LVL.csv |       4786        |                    1466                    |
|   ILS    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ILS.csv |       4567        |                    1419                    |
|   EEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/EEK.csv |       4000        |                    1226                    |
|   SKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SKK.csv |       2970        |                    912                     |
|   CYP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CYP.csv |       2908        |                    892                     |
|   MTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MTL.csv |       2606        |                    801                     |
|   SIT    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SIT.csv |       2544        |                    780                     |
|   TRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRL.csv |       1818        |                    559                     |
|   ROL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ROL.csv |       1697        |                    524                     |
|   GRD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GRD.csv |        361        |                    109                     |

<!-- END LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->
