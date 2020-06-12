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

07.06.2020

</td>

<td style="text-align:right;">

2338593

</td>

<td style="text-align:right;">

170132

</td>

<td style="text-align:right;">

4692

</td>

<td style="text-align:right;">

613

</td>

<td style="text-align:right;">

274

</td>

<td style="text-align:right;">

137969

</td>

<td style="text-align:right;">

23

</td>

<td style="text-align:right;">

914

</td>

</tr>

<tr>

<td style="text-align:left;">

08.06.2020

</td>

<td style="text-align:right;">

2377954

</td>

<td style="text-align:right;">

171121

</td>

<td style="text-align:right;">

4711

</td>

<td style="text-align:right;">

625

</td>

<td style="text-align:right;">

261

</td>

<td style="text-align:right;">

141380

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

989

</td>

</tr>

<tr>

<td style="text-align:left;">

09.06.2020

</td>

<td style="text-align:right;">

2415179

</td>

<td style="text-align:right;">

172114

</td>

<td style="text-align:right;">

4729

</td>

<td style="text-align:right;">

642

</td>

<td style="text-align:right;">

281

</td>

<td style="text-align:right;">

144598

</td>

<td style="text-align:right;">

18

</td>

<td style="text-align:right;">

993

</td>

</tr>

<tr>

<td style="text-align:left;">

10.06.2020

</td>

<td style="text-align:right;">

2451700

</td>

<td style="text-align:right;">

173036

</td>

<td style="text-align:right;">

4746

</td>

<td style="text-align:right;">

631

</td>

<td style="text-align:right;">

280

</td>

<td style="text-align:right;">

146839

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

922

</td>

</tr>

<tr>

<td style="text-align:left;">

11.06.2020

</td>

<td style="text-align:right;">

2500890

</td>

<td style="text-align:right;">

174023

</td>

<td style="text-align:right;">

4763

</td>

<td style="text-align:right;">

643

</td>

<td style="text-align:right;">

266

</td>

<td style="text-align:right;">

147860

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

987

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

07.06.2020

</td>

<td style="text-align:right;">

2338593

</td>

<td style="text-align:right;">

170132

</td>

<td style="text-align:right;">

4692

</td>

<td style="text-align:right;">

613

</td>

<td style="text-align:right;">

274

</td>

<td style="text-align:right;">

137969

</td>

<td style="text-align:right;">

23

</td>

<td style="text-align:right;">

914

</td>

</tr>

<tr>

<td style="text-align:left;">

08.06.2020

</td>

<td style="text-align:right;">

2377954

</td>

<td style="text-align:right;">

171121

</td>

<td style="text-align:right;">

4711

</td>

<td style="text-align:right;">

625

</td>

<td style="text-align:right;">

261

</td>

<td style="text-align:right;">

141380

</td>

<td style="text-align:right;">

19

</td>

<td style="text-align:right;">

989

</td>

</tr>

<tr>

<td style="text-align:left;">

09.06.2020

</td>

<td style="text-align:right;">

2415179

</td>

<td style="text-align:right;">

172114

</td>

<td style="text-align:right;">

4729

</td>

<td style="text-align:right;">

642

</td>

<td style="text-align:right;">

281

</td>

<td style="text-align:right;">

144598

</td>

<td style="text-align:right;">

18

</td>

<td style="text-align:right;">

993

</td>

</tr>

<tr>

<td style="text-align:left;">

10.06.2020

</td>

<td style="text-align:right;">

2451700

</td>

<td style="text-align:right;">

173036

</td>

<td style="text-align:right;">

4746

</td>

<td style="text-align:right;">

631

</td>

<td style="text-align:right;">

280

</td>

<td style="text-align:right;">

146839

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

922

</td>

</tr>

<tr>

<td style="text-align:left;">

11.06.2020

</td>

<td style="text-align:right;">

2500890

</td>

<td style="text-align:right;">

174023

</td>

<td style="text-align:right;">

4763

</td>

<td style="text-align:right;">

643

</td>

<td style="text-align:right;">

266

</td>

<td style="text-align:right;">

147860

</td>

<td style="text-align:right;">

17

</td>

<td style="text-align:right;">

987

</td>

</tr>

</tbody>

</table>

**100 Vaka sonrası günlük vefat sayısı - Daily number of deaths after
100th case** ![](README_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

**100 Vaka sonrası günlük vaka sayısı - Daily number of cases after
100th case** ![](README_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->
