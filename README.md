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

24.06.2020

</td>

<td style="text-align:right;">

3083301

</td>

<td style="text-align:right;">

191657

</td>

<td style="text-align:right;">

5025

</td>

<td style="text-align:right;">

914

</td>

<td style="text-align:right;">

356

</td>

<td style="text-align:right;">

164234

</td>

<td style="text-align:right;">

24

</td>

<td style="text-align:right;">

1492

</td>

</tr>

<tr>

<td style="text-align:left;">

25.06.2020

</td>

<td style="text-align:right;">

3135424

</td>

<td style="text-align:right;">

193115

</td>

<td style="text-align:right;">

5046

</td>

<td style="text-align:right;">

941

</td>

<td style="text-align:right;">

369

</td>

<td style="text-align:right;">

165706

</td>

<td style="text-align:right;">

21

</td>

<td style="text-align:right;">

1458

</td>

</tr>

<tr>

<td style="text-align:left;">

26.06.2020

</td>

<td style="text-align:right;">

3186622

</td>

<td style="text-align:right;">

194511

</td>

<td style="text-align:right;">

5065

</td>

<td style="text-align:right;">

963

</td>

<td style="text-align:right;">

382

</td>

<td style="text-align:right;">

167198

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

1396

</td>

</tr>

<tr>

<td style="text-align:left;">

27.06.2020

</td>

<td style="text-align:right;">

3231835

</td>

<td style="text-align:right;">

195883

</td>

<td style="text-align:right;">

5082

</td>

<td style="text-align:right;">

984

</td>

<td style="text-align:right;">

366

</td>

<td style="text-align:right;">

169182

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

1372

</td>

</tr>

<tr>

<td style="text-align:left;">

28.06.2020

</td>

<td style="text-align:right;">

3280144

</td>

<td style="text-align:right;">

197239

</td>

<td style="text-align:right;">

5097

</td>

<td style="text-align:right;">

996

</td>

<td style="text-align:right;">

381

</td>

<td style="text-align:right;">

170595

</td>

<td style="text-align:right;">

15

</td>

<td style="text-align:right;">

1356

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

24.06.2020

</td>

<td style="text-align:right;">

3083301

</td>

<td style="text-align:right;">

191657

</td>

<td style="text-align:right;">

5025

</td>

<td style="text-align:right;">

914

</td>

<td style="text-align:right;">

356

</td>

<td style="text-align:right;">

164234

</td>

<td style="text-align:right;">

24

</td>

<td style="text-align:right;">

1492

</td>

</tr>

<tr>

<td style="text-align:left;">

25.06.2020

</td>

<td style="text-align:right;">

3135424

</td>

<td style="text-align:right;">

193115

</td>

<td style="text-align:right;">

5046

</td>

<td style="text-align:right;">

941

</td>

<td style="text-align:right;">

369

</td>

<td style="text-align:right;">

165706

</td>

<td style="text-align:right;">

21

</td>

<td style="text-align:right;">

1458

</td>

</tr>

<tr>

<td style="text-align:left;">

26.06.2020

</td>

<td style="text-align:right;">

3186622

</td>

<td style="text-align:right;">

194511

</td>

<td style="text-align:right;">

5065

</td>

<td style="text-align:right;">

963

</td>

<td style="text-align:right;">

382

</td>

<td style="text-align:right;">

167198

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

1396

</td>

</tr>

<tr>

<td style="text-align:left;">

27.06.2020

</td>

<td style="text-align:right;">

3231835

</td>

<td style="text-align:right;">

195883

</td>

<td style="text-align:right;">

5082

</td>

<td style="text-align:right;">

984

</td>

<td style="text-align:right;">

366

</td>

<td style="text-align:right;">

169182

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

1372

</td>

</tr>

<tr>

<td style="text-align:left;">

28.06.2020

</td>

<td style="text-align:right;">

3280144

</td>

<td style="text-align:right;">

197239

</td>

<td style="text-align:right;">

5097

</td>

<td style="text-align:right;">

996

</td>

<td style="text-align:right;">

381

</td>

<td style="text-align:right;">

170595

</td>

<td style="text-align:right;">

15

</td>

<td style="text-align:right;">

1356

</td>

</tr>

</tbody>

</table>

**100 Vaka sonrası günlük vefat sayısı - Daily number of deaths after
100th case** ![](README_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

**100 Vaka sonrası günlük vaka sayısı - Daily number of cases after
100th case** ![](README_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->
