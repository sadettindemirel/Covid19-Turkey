COVID-19 Türkiye Verileri | COVID-19 Turkey Data
================

[![License: CC
BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/deed.es)

**Veriseti Hakkında**

  - Covid19 verisi Sağlık Bakanlığının [Covid19 takip
    sayfasından](https://covid19.saglik.gov.tr/) alınmıştır.
  - Verilere data klasöründen **CSV ve RDS** formatlarında
    ulaşabilirsiniz
  - Veriseti bünyesinde bulunduğum **[Veri Okuryazarlığı
    Derneği](https://twitter.com/voydorg)** tarafından derlenmiştir.
  - Ayrıca derlenen veri ile **[Koronavirüs Takip
    Sayfası](https://veribulteni.voyd.org.tr/koronavirus-takip/)**
    oluşturulmuştur
  - Verisetinde kümülatif ve günlük vaka, vefat ve iyileşme sayılarının
    dahil olduğu 13 değişken yer almaktadır.

**About Dataset**

  - Covid-19 data is retrieved from Turkey’s Health Ministry [Covid-19
    update page](https://covid19.saglik.gov.tr/) daily (by hand)
  - Please find the datasets in English and Turkish from `Data` folder
  - Datasets contains cumulative and daily number of cases, deaths and
    recoveries along with icu patients.

<!-- end list -->

    ## [1] "Turkish_Turkey.1254"

#### Vaka, Vefat ve İyileşme

Aşağıdaki tablo verideki bazı değişkenleri ve son 5 günün verilerini
göstermektedir. Daha detaylı veriler için data klasörüne bakınız.

<table>

<thead>

<tr>

<th style="text-align:left;">

tarih

</th>

<th style="text-align:right;">

test

</th>

<th style="text-align:right;">

vaka

</th>

<th style="text-align:right;">

vefat

</th>

<th style="text-align:right;">

yogun\_bakim\_hasta

</th>

<th style="text-align:right;">

entube\_hasta

</th>

<th style="text-align:right;">

iyilesme

</th>

<th style="text-align:right;">

gunluk\_vefat

</th>

<th style="text-align:right;">

gunluk\_vaka

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

13.06.2020

</td>

<td style="text-align:right;">

2586995

</td>

<td style="text-align:right;">

176677

</td>

<td style="text-align:right;">

4792

</td>

<td style="text-align:right;">

684

</td>

<td style="text-align:right;">

284

</td>

<td style="text-align:right;">

150087

</td>

<td style="text-align:right;">

14

</td>

<td style="text-align:right;">

1459

</td>

</tr>

<tr>

<td style="text-align:left;">

14.06.2020

</td>

<td style="text-align:right;">

2632171

</td>

<td style="text-align:right;">

178239

</td>

<td style="text-align:right;">

4807

</td>

<td style="text-align:right;">

717

</td>

<td style="text-align:right;">

290

</td>

<td style="text-align:right;">

151417

</td>

<td style="text-align:right;">

15

</td>

<td style="text-align:right;">

1562

</td>

</tr>

<tr>

<td style="text-align:left;">

15.06.2020

</td>

<td style="text-align:right;">

2674203

</td>

<td style="text-align:right;">

179831

</td>

<td style="text-align:right;">

4825

</td>

<td style="text-align:right;">

722

</td>

<td style="text-align:right;">

291

</td>

<td style="text-align:right;">

152364

</td>

<td style="text-align:right;">

18

</td>

<td style="text-align:right;">

1592

</td>

</tr>

<tr>

<td style="text-align:left;">

16.06.2020

</td>

<td style="text-align:right;">

2721003

</td>

<td style="text-align:right;">

181298

</td>

<td style="text-align:right;">

4842

</td>

<td style="text-align:right;">

732

</td>

<td style="text-align:right;">

303

</td>

<td style="text-align:right;">

153379

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

1467

</td>

</tr>

<tr>

<td style="text-align:left;">

17.06.2020

</td>

<td style="text-align:right;">

2773904

</td>

<td style="text-align:right;">

182727

</td>

<td style="text-align:right;">

4861

</td>

<td style="text-align:right;">

745

</td>

<td style="text-align:right;">

306

</td>

<td style="text-align:right;">

154640

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

1429

</td>

</tr>

</tbody>

</table>

#### Covid-19 cases, deaths and recoveries

Only the fraction of variables and last five days’ figures are shown
below. Please find the data folder and `rds` or `csv` data file for more
details.

<table>

<thead>

<tr>

<th style="text-align:left;">

date

</th>

<th style="text-align:right;">

tests

</th>

<th style="text-align:right;">

cases

</th>

<th style="text-align:right;">

deaths

</th>

<th style="text-align:right;">

ic\_patients

</th>

<th style="text-align:right;">

intubated\_patients

</th>

<th style="text-align:right;">

recovered

</th>

<th style="text-align:right;">

daily\_death

</th>

<th style="text-align:right;">

daily\_case

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

13.06.2020

</td>

<td style="text-align:right;">

2586995

</td>

<td style="text-align:right;">

176677

</td>

<td style="text-align:right;">

4792

</td>

<td style="text-align:right;">

684

</td>

<td style="text-align:right;">

284

</td>

<td style="text-align:right;">

150087

</td>

<td style="text-align:right;">

14

</td>

<td style="text-align:right;">

1459

</td>

</tr>

<tr>

<td style="text-align:left;">

14.06.2020

</td>

<td style="text-align:right;">

2632171

</td>

<td style="text-align:right;">

178239

</td>

<td style="text-align:right;">

4807

</td>

<td style="text-align:right;">

717

</td>

<td style="text-align:right;">

290

</td>

<td style="text-align:right;">

151417

</td>

<td style="text-align:right;">

15

</td>

<td style="text-align:right;">

1562

</td>

</tr>

<tr>

<td style="text-align:left;">

15.06.2020

</td>

<td style="text-align:right;">

2674203

</td>

<td style="text-align:right;">

179831

</td>

<td style="text-align:right;">

4825

</td>

<td style="text-align:right;">

722

</td>

<td style="text-align:right;">

291

</td>

<td style="text-align:right;">

152364

</td>

<td style="text-align:right;">

18

</td>

<td style="text-align:right;">

1592

</td>

</tr>

<tr>

<td style="text-align:left;">

16.06.2020

</td>

<td style="text-align:right;">

2721003

</td>

<td style="text-align:right;">

181298

</td>

<td style="text-align:right;">

4842

</td>

<td style="text-align:right;">

732

</td>

<td style="text-align:right;">

303

</td>

<td style="text-align:right;">

153379

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

1467

</td>

</tr>

<tr>

<td style="text-align:left;">

17.06.2020

</td>

<td style="text-align:right;">

2773904

</td>

<td style="text-align:right;">

182727

</td>

<td style="text-align:right;">

4861

</td>

<td style="text-align:right;">

745

</td>

<td style="text-align:right;">

306

</td>

<td style="text-align:right;">

154640

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

1429

</td>

</tr>

</tbody>

</table>

**100 Vaka sonrası günlük vefat sayısı - Daily number of deaths after
100th case** ![](README_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

**100 Vaka sonrası günlük vaka sayısı - Daily number of cases after
100th case** ![](README_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->
