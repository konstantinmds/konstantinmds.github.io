
   #  Par modela :prvi dio

Često se u društvu našalimo, dosta kreativno pritom, kako je Istočno Sarajevo na putu da postane "grad đedova i baba".
To je očit utsak, neposredan i snazan. Pored toga, vjerujem da se ovaj prostor ne prazni u mjeri kao tradicionalno jačim migracijama podložan sjeverni dio. Ovdje ću pokušati,brojevima i slikama, prikazati koliko brzo se demografska struktura mijenja, kakve ekonomske posljedice mogu biti i kako to utiče na dalje migracije. Čekao sam da se izborni proces završi, pa da mogu o ovome govoriti više, i mislim da se ovom problemu nije posvetilo dovoljno kvalitetnog prostora. 

Dakle, opteretiću sebe sa par zadataka pri ovom izlaganju: najvažnijim zadatkom-da ne budem naporan i nerazumljiv, 
a bez da zrtvujem preciznost i da bude razumljivo što široj publici. 
Ova analiza će ići u tri dijela.

## Demografski problem : 

Neka prva tačka bude godina 2015. Krenimo sa najširim demografskim predviđanjima populacije. Slika ispod pokazuje projektovanu starost populacije Bosne i Hercegovine prema starosnim grupama. Gornji desni ugao pokazuje godinu predviđanja. Radi se o UN-ovim demografskim projekcijama, tako da u metodološki integritet ocjena ne treba pretjerano sumnjati, iako, i to će predmet komentara.



```python

```




    Text(0,1,'Pop by age')




![png](output_4_1.png)


Iako nije lako, pokušajte uočiti smanjenja koja počinju sa lijeve strane, odozgo, prema dole. Pogledajte kako se se smanjuje stubić 15-19 i 20-24 iz 2015 u 2025.

Oprostite za suhoparnost, radi pojednostavljenja grafika, ispod prilažem jasnu tabelu, prva kolona '2015',
i raspored stanovnika po starosnim grupama su u redovima. Dakle, godine '2015' bilo je 237.025 ljudi starih između 20-24 godine, a deset godina kasnije, 2025. godine, predviđa se 175.849 ljudi u toj starosnoj grupi. Nećemo u procentima, jednostavnije je samo apsolutne veličine gledati, dakle, ugrubo oko 60 000 hiljada manje u toj starosnoj grupi. Koliko li je to potencijalnih brakova manje ? Ili djece ? Zagledajte se u tabelu procjenjene brojnosti naših starosnih kohorti. 2025 je relevantna i nama bitna, ova dalja budućnost je samo usput.

Tabela:


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Year</th>
      <th>2015</th>
      <th>2025</th>
      <th>2035</th>
      <th>2045</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0-4</th>
      <td>162.360</td>
      <td>162.382</td>
      <td>144.127</td>
      <td>128.953</td>
    </tr>
    <tr>
      <th>5-9</th>
      <td>172.657</td>
      <td>160.964</td>
      <td>156.145</td>
      <td>133.588</td>
    </tr>
    <tr>
      <th>10-14</th>
      <td>176.910</td>
      <td>161.883</td>
      <td>161.967</td>
      <td>143.775</td>
    </tr>
    <tr>
      <th>15-19</th>
      <td>233.443</td>
      <td>172.097</td>
      <td>160.486</td>
      <td>155.722</td>
    </tr>
    <tr>
      <th>20-24</th>
      <td>237.025</td>
      <td>175.849</td>
      <td>160.954</td>
      <td>161.111</td>
    </tr>
    <tr>
      <th>25-29</th>
      <td>246.496</td>
      <td>231.605</td>
      <td>170.650</td>
      <td>159.183</td>
    </tr>
    <tr>
      <th>30-34</th>
      <td>245.154</td>
      <td>234.886</td>
      <td>174.203</td>
      <td>159.501</td>
    </tr>
    <tr>
      <th>35-39</th>
      <td>244.906</td>
      <td>244.091</td>
      <td>229.588</td>
      <td>169.160</td>
    </tr>
    <tr>
      <th>40-44</th>
      <td>248.928</td>
      <td>242.167</td>
      <td>232.419</td>
      <td>172.510</td>
    </tr>
    <tr>
      <th>45-49</th>
      <td>241.491</td>
      <td>240.568</td>
      <td>240.436</td>
      <td>226.684</td>
    </tr>
    <tr>
      <th>50-54</th>
      <td>278.138</td>
      <td>241.982</td>
      <td>236.457</td>
      <td>227.847</td>
    </tr>
    <tr>
      <th>55-59</th>
      <td>257.797</td>
      <td>230.659</td>
      <td>231.437</td>
      <td>232.839</td>
    </tr>
    <tr>
      <th>60-64</th>
      <td>234.907</td>
      <td>258.185</td>
      <td>227.374</td>
      <td>224.520</td>
    </tr>
    <tr>
      <th>65-69</th>
      <td>177.023</td>
      <td>228.477</td>
      <td>208.628</td>
      <td>212.817</td>
    </tr>
    <tr>
      <th>70-74</th>
      <td>114.403</td>
      <td>193.138</td>
      <td>218.728</td>
      <td>197.918</td>
    </tr>
    <tr>
      <th>75-79</th>
      <td>136.883</td>
      <td>128.366</td>
      <td>172.983</td>
      <td>165.039</td>
    </tr>
    <tr>
      <th>80-84</th>
      <td>79.631</td>
      <td>67.102</td>
      <td>121.531</td>
      <td>146.459</td>
    </tr>
  </tbody>
</table>
</div>



Sljedeći grafik, možda i nije najsrećnije rješenje za ono što nastojim pokazati. Ovo 'ispravljanje' i 'uvećavanje' vrha, odnosi se na biološko nestanje generacije 'bejbi bumersa'(generacije rođene između '1946' i '1964'), i posljedično poravnanje populacijske piramide, odnosno ujednačenja brojnosti populacije po pojedinačnim starosnim grupama. Dakle, nekada se brojnost mladih, brojnost ljudi u zrelim godinama, brojnost starijih prilično dosta razlikovala


```python

```


![png](output_9_0.png)


Odmaknimo se malo od budućnosti i pogledajmo kratko u demografsku prošlost, da vidimo šta je to bilo od godina "rata" pa do 2015. Kojom brzinom smo se kretali prema kakvim rezultatima u ovim godinama koje brojimo od rata.

# Od 1990 do 2015

Nisam znao previše o ovom periodu u Bosni i Hecegovini. Mislim da smo nedovoljno precizni kada su teme ovako ozbiljne.  Za početak tabela, možemo vidjeti ogroman pad broja mladih. Grupa '0-4' godine sa 348.917 u 1990 godini, na 162.360 osoba u 2015. godini, 53% pad, vrtoglavo prepolovljavanje populacije beba. Sa druge strane, broj u grupi '80-84' '85-89' i dalje, skoro da se povećao tri puta(sklrolujte tabelu na desno, ne vidi se sav sadržaj).


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Region</th>
      <th>Year</th>
      <th>0-4</th>
      <th>5-9</th>
      <th>10-14</th>
      <th>15-19</th>
      <th>20-24</th>
      <th>25-29</th>
      <th>30-34</th>
      <th>35-39</th>
      <th>...</th>
      <th>60-64</th>
      <th>65-69</th>
      <th>70-74</th>
      <th>75-79</th>
      <th>80+</th>
      <th>80-84</th>
      <th>85-89</th>
      <th>90-94</th>
      <th>95-99</th>
      <th>100+</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2234</th>
      <td>Bosnia and Herzegovina</td>
      <td>1990</td>
      <td>348.917</td>
      <td>364.897</td>
      <td>364.554</td>
      <td>380.565</td>
      <td>378.855</td>
      <td>411.099</td>
      <td>375.500</td>
      <td>344.302</td>
      <td>...</td>
      <td>197.944</td>
      <td>121.044</td>
      <td>62.055</td>
      <td>56.609</td>
      <td>…</td>
      <td>36.787</td>
      <td>13.274</td>
      <td>3.585</td>
      <td>0.494</td>
      <td>0.062</td>
    </tr>
    <tr>
      <th>2235</th>
      <td>Bosnia and Herzegovina</td>
      <td>1995</td>
      <td>260.992</td>
      <td>293.930</td>
      <td>291.477</td>
      <td>289.287</td>
      <td>298.336</td>
      <td>290.404</td>
      <td>326.132</td>
      <td>303.110</td>
      <td>...</td>
      <td>201.083</td>
      <td>158.521</td>
      <td>94.371</td>
      <td>43.460</td>
      <td>…</td>
      <td>34.187</td>
      <td>17.514</td>
      <td>4.6</td>
      <td>0.826</td>
      <td>0.073</td>
    </tr>
    <tr>
      <th>2236</th>
      <td>Bosnia and Herzegovina</td>
      <td>2000</td>
      <td>235.649</td>
      <td>257.009</td>
      <td>287.463</td>
      <td>283.116</td>
      <td>275.575</td>
      <td>278.341</td>
      <td>270.128</td>
      <td>309.157</td>
      <td>...</td>
      <td>220.183</td>
      <td>172.375</td>
      <td>126.289</td>
      <td>66.631</td>
      <td>…</td>
      <td>23.972</td>
      <td>16.04</td>
      <td>6.21</td>
      <td>1.033</td>
      <td>0.105</td>
    </tr>
    <tr>
      <th>2237</th>
      <td>Bosnia and Herzegovina</td>
      <td>2005</td>
      <td>178.074</td>
      <td>234.977</td>
      <td>256.554</td>
      <td>286.611</td>
      <td>281.479</td>
      <td>273.539</td>
      <td>276.298</td>
      <td>268.020</td>
      <td>...</td>
      <td>147.611</td>
      <td>199.836</td>
      <td>147.274</td>
      <td>97.720</td>
      <td>…</td>
      <td>44.685</td>
      <td>12.822</td>
      <td>6.053</td>
      <td>1.474</td>
      <td>0.138</td>
    </tr>
    <tr>
      <th>2238</th>
      <td>Bosnia and Herzegovina</td>
      <td>2010</td>
      <td>174.088</td>
      <td>177.592</td>
      <td>234.431</td>
      <td>252.685</td>
      <td>279.019</td>
      <td>272.659</td>
      <td>263.778</td>
      <td>266.446</td>
      <td>...</td>
      <td>197.963</td>
      <td>133.880</td>
      <td>172.179</td>
      <td>115.462</td>
      <td>…</td>
      <td>65.878</td>
      <td>24.263</td>
      <td>5.015</td>
      <td>1.491</td>
      <td>0.201</td>
    </tr>
    <tr>
      <th>2239</th>
      <td>Bosnia and Herzegovina</td>
      <td>2015</td>
      <td>162.360</td>
      <td>172.657</td>
      <td>176.910</td>
      <td>233.443</td>
      <td>237.025</td>
      <td>246.496</td>
      <td>245.154</td>
      <td>244.906</td>
      <td>...</td>
      <td>234.907</td>
      <td>177.023</td>
      <td>114.403</td>
      <td>136.883</td>
      <td>…</td>
      <td>79.631</td>
      <td>36.415</td>
      <td>9.81</td>
      <td>1.339</td>
      <td>0.245</td>
    </tr>
  </tbody>
</table>
<p>6 rows × 24 columns</p>
</div>



Radi jednostavnijeg prikaza, grupisao sam podatke na drugačiji način, primjeti se oštar pad grupe '0-20' godina starosti, koja se prepolovila za 25 godina. Sa druge strane, populacija iznad 80 godina se uduplala.
Grafik:


```python

```


![png](output_15_0.png)


 Sljedeća tabela grupiše podatke u 4 veće grupe. Prikazan je broj stanovnika u hiljadama. Dakle, grupa '40-60' godina, nezgrapno zavedena pod nazivom '40+', jedina je zadržala je brojnost od preko milion. Ostale grupe su se značajno smanjile. Dakle, devedesete smo imali 55 hiljada stanovnika preko 80 godina, danas ih je 127 hiljada.


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0-20</th>
      <th>20+</th>
      <th>40+</th>
      <th>60+</th>
      <th>80+</th>
    </tr>
    <tr>
      <th>Year</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1990</th>
      <td>1458.93</td>
      <td>1509.76</td>
      <td>1002.88</td>
      <td>437.652</td>
      <td>54.202</td>
    </tr>
    <tr>
      <th>1995</th>
      <td>1135.69</td>
      <td>1217.98</td>
      <td>935.409</td>
      <td>497.435</td>
      <td>57.2</td>
    </tr>
    <tr>
      <th>2000</th>
      <td>1063.24</td>
      <td>1133.2</td>
      <td>937.43</td>
      <td>585.478</td>
      <td>47.36</td>
    </tr>
    <tr>
      <th>2005</th>
      <td>956.216</td>
      <td>1099.34</td>
      <td>1068.36</td>
      <td>592.441</td>
      <td>65.172</td>
    </tr>
    <tr>
      <th>2010</th>
      <td>838.796</td>
      <td>1081.9</td>
      <td>1085.05</td>
      <td>619.484</td>
      <td>96.848</td>
    </tr>
    <tr>
      <th>2015</th>
      <td>745.37</td>
      <td>973.581</td>
      <td>1026.35</td>
      <td>663.216</td>
      <td>127.44</td>
    </tr>
  </tbody>
</table>
</div>



# Totalna populaciona zavisnost

Tabela ispod prikazuje racio populacione zavisnosti- udio zbira osoba starosti '0-19' i '65+', naspram  ekonomski aktivnih osoba, starosti '15-65'. Dakle, prikazan je broj izdržavanih osoba od strane 100 pojedinaca grupe '15-65'. Sljedeća tabela bira najrazličitije zemlje i vidi se da sve kreću sa sličnih pozicija i dolaze u slične pozicije.

Prva mjerenja iz 50-ih, kažu, u Bosni i Hercegovini imamo da je 110 zavisnih lica izdržavano od strane 100 radno sposobnih lica. Dvijehiljadepetnaeste, taj broj je pao na 46. __Dakle, danas, radnosposobnih 100 ljudi  izdržava 46 starijih i mladih osoba__ , rekli bismo- breme se olakšalo u odnosu na one koje su nosile prethodne generacije.

Kao što ste svi pretpostavili, takva brojka je posljedica odluke o planiranju manjih porodica ili, konkretno, odluka ili slučja neostavljanja potomstva. 


Tabela:


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Region</th>
      <th>index</th>
      <th>China</th>
      <th>Japan</th>
      <th>Slovakia</th>
      <th>Bosnia and Herzegovina</th>
      <th>Serbia</th>
      <th>Germany</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1950</td>
      <td>83.992072</td>
      <td>93.818651</td>
      <td>71.694814</td>
      <td>110.745311</td>
      <td>76.696108</td>
      <td>57.018900</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1955</td>
      <td>93.503465</td>
      <td>86.268174</td>
      <td>73.722059</td>
      <td>100.994806</td>
      <td>72.226668</td>
      <td>56.754277</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1960</td>
      <td>98.553843</td>
      <td>77.243792</td>
      <td>76.950973</td>
      <td>93.682514</td>
      <td>69.512845</td>
      <td>55.166870</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1965</td>
      <td>108.766967</td>
      <td>68.019927</td>
      <td>76.762859</td>
      <td>96.868383</td>
      <td>70.022605</td>
      <td>58.077026</td>
    </tr>
  </tbody>
</table>
</div>



Pomenutu mjeru ćemo grafički prikazati, od godine '1955' pratimo grafik do '2015' godine. Svršetkom drugog svetskog rata, BIH je krenula u proces demografske tranzicije sa nadprosječno visokim udjelom mladih '0-14' godina starosti u odnosu na brojnost aktivnog dijela populacije.


```python

```




    <matplotlib.axes._subplots.AxesSubplot at 0x7fa8a8208b70>




![png](output_22_1.png)



# Količnik pomoći starijim ljudima

Posljednja ilustracija je UN racio potencijalne pomoći klasi '64+' od strane radno sposobnog stanovnistva klase '20-65'. Dakle, sada ne brojimo mladu populaciju(od 0-19), __vidimo da u BIH na jednu osobu stariju od 65 godina idu 4,4 radno sposobna lica__  Ova mjera ne uključuje nezaposlena lica, sa čime BIH ima prilično problema. U tabeli ispod možemo vidjeti varijacije pomenute mjere. Smanjenje ove mjere ima ozbiljne implikacije za finansijske i osiguravajuće šeme, pogotovo za penzioni sistem zasnovan na međugeneracijskoj solidarnosti, kakav je implementiran u BIH. 

Tabela:


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Region</th>
      <th>China</th>
      <th>Japan</th>
      <th>Slovakia</th>
      <th>Bosnia and Herzegovina</th>
      <th>Serbia</th>
      <th>Germany</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1950</th>
      <td>13.891136</td>
      <td>12.159973</td>
      <td>9.752052</td>
      <td>14.541692</td>
      <td>8.437697</td>
      <td>6.961349</td>
    </tr>
    <tr>
      <th>1955</th>
      <td>14.400719</td>
      <td>11.654812</td>
      <td>9.514368</td>
      <td>16.696262</td>
      <td>9.162022</td>
      <td>6.453754</td>
    </tr>
    <tr>
      <th>1960</th>
      <td>15.315781</td>
      <td>11.406799</td>
      <td>9.114490</td>
      <td>17.011914</td>
      <td>9.653620</td>
      <td>5.845920</td>
    </tr>
    <tr>
      <th>1965</th>
      <td>16.181000</td>
      <td>11.021101</td>
      <td>7.771349</td>
      <td>14.779139</td>
      <td>8.817284</td>
      <td>5.183607</td>
    </tr>
    <tr>
      <th>1970</th>
      <td>14.858466</td>
      <td>10.037346</td>
      <td>6.893928</td>
      <td>13.458732</td>
      <td>7.985881</td>
      <td>4.635531</td>
    </tr>
    <tr>
      <th>1975</th>
      <td>13.661091</td>
      <td>8.815462</td>
      <td>6.409603</td>
      <td>11.786049</td>
      <td>7.148820</td>
      <td>4.274101</td>
    </tr>
    <tr>
      <th>1980</th>
      <td>12.669848</td>
      <td>7.572374</td>
      <td>6.042675</td>
      <td>11.300456</td>
      <td>7.171502</td>
      <td>4.202914</td>
    </tr>
    <tr>
      <th>1985</th>
      <td>11.995447</td>
      <td>6.749771</td>
      <td>6.894773</td>
      <td>12.511679</td>
      <td>7.873130</td>
      <td>4.770877</td>
    </tr>
    <tr>
      <th>1990</th>
      <td>11.604086</td>
      <td>5.868958</td>
      <td>6.288726</td>
      <td>10.517315</td>
      <td>6.951957</td>
      <td>4.640860</td>
    </tr>
    <tr>
      <th>1995</th>
      <td>10.781131</td>
      <td>4.857965</td>
      <td>6.198276</td>
      <td>7.477715</td>
      <td>5.811959</td>
      <td>4.415569</td>
    </tr>
    <tr>
      <th>2000</th>
      <td>9.910066</td>
      <td>4.017273</td>
      <td>6.110296</td>
      <td>6.237487</td>
      <td>4.873083</td>
      <td>4.118564</td>
    </tr>
    <tr>
      <th>2005</th>
      <td>9.410728</td>
      <td>3.384628</td>
      <td>6.147264</td>
      <td>5.101790</td>
      <td>4.579154</td>
      <td>3.538522</td>
    </tr>
    <tr>
      <th>2010</th>
      <td>8.779679</td>
      <td>2.851080</td>
      <td>5.799116</td>
      <td>5.049692</td>
      <td>4.689653</td>
      <td>3.207880</td>
    </tr>
    <tr>
      <th>2015</th>
      <td>7.506943</td>
      <td>2.344515</td>
      <td>5.026510</td>
      <td>4.441367</td>
      <td>4.110766</td>
      <td>3.114170</td>
    </tr>
  </tbody>
</table>
</div>




```python

```




    <matplotlib.axes._subplots.AxesSubplot at 0x7fcc36438860>




![png](output_26_1.png)


# Šelingov model

Ko to ide iz Bosne i Hercegocine ? Koliko često idemo iz Bosne i Hercegovine ? Egzaktno ću se nekada i probati pozabaviti, ali ovdje kroz Šelingov model samo pokušaj napomena.


```python
import matplotlib.pyplot as plt
import itertools
import random
import copy
class Schelling:
    def __init__(self, width, height, empty_ratio, similarity_threshold, n_iterations, races = 2):
        self.width = width 
        self.height = height 
        self.races = races
        self.empty_ratio = empty_ratio
        self.similarity_threshold = similarity_threshold
        self.n_iterations = n_iterations
        self.empty_houses = []
        self.agents = {}
        
        

    def populate(self):
        self.all_houses = list(itertools.product(range(self.width),range(self.height)))
        random.shuffle(self.all_houses)

        self.n_empty = int( self.empty_ratio * len(self.all_houses) )
        self.empty_houses = self.all_houses[:self.n_empty]

        self.remaining_houses = self.all_houses[self.n_empty:]
        houses_by_race = [self.remaining_houses[i::self.races] for i in range(self.races)]
        for i in range(self.races):
        #create agents for each race
            self.agents = dict(
                            self.agents.items() + 
                            dict(zip(houses_by_race[i], [i+1]*len(houses_by_race[i]))).items()
                        )
    def is_unsatisfied(self, x, y):

        race = self.agents[(x,y)]
        count_similar = 0
        count_different = 0

        if x > 0 and y > 0 and (x-1, y-1) not in self.empty_houses:
            if self.agents[(x-1, y-1)] == race:
                count_similar += 1
            else:
                count_different += 1
        if y > 0 and (x,y-1) not in self.empty_houses:
            if self.agents[(x,y-1)] == race:
                count_similar += 1
            else:
                count_different += 1
        if x < (self.width-1) and y > 0 and (x+1,y-1) not in self.empty_houses:
            if self.agents[(x+1,y-1)] == race:
                count_similar += 1
            else:
                count_different += 1
        if x > 0 and (x-1,y) not in self.empty_houses:
            if self.agents[(x-1,y)] == race:
                count_similar += 1
            else:
                count_different += 1        
        if x < (self.width-1) and (x+1,y) not in self.empty_houses:
            if self.agents[(x+1,y)] == race:
                count_similar += 1
            else:
                count_different += 1
        if x > 0 and y < (self.height-1) and (x-1,y+1) not in self.empty_houses:
            if self.agents[(x-1,y+1)] == race:
                count_similar += 1
            else:
                count_different += 1        
        if x > 0 and y < (self.height-1) and (x,y+1) not in self.empty_houses:
            if self.agents[(x,y+1)] == race:
                count_similar += 1
            else:
                count_different += 1        
        if x < (self.width-1) and y < (self.height-1) and (x+1,y+1) not in self.empty_houses:
            if self.agents[(x+1,y+1)] == race:
                count_similar += 1
            else:
                count_different += 1

        if (count_similar+count_different) == 0:
            return False
        else:
            return float(count_similar)/(count_similar+count_different) < self.happy_threshold
    
    def update(self):
        for i in range(self.n_iterations):
            self.old_agents = copy.deepcopy(self.agents)
            n_changes = 0
        for agent in self.old_agents:
            if self.is_unhappy(agent[0], agent[1]):
                agent_race = self.agents[agent]
                empty_house = random.choice(self.empty_houses)
                self.agents[empty_house] = agent_race
                del self.agents[agent]
                self.empty_houses.remove(empty_house)
                self.empty_houses.append(agent)
                n_changes += 1
                break
        print (n_changes)
     #   if n_changes == 0:
            
 

    def move_to_empty(self, x, y):
        race= self.agents[(x,y)]
        empty_house = random.choice(self.empty_houses)
        self.updated_agents[empty_house] = race
       
   # del self.updated_agents[(x, y)]
    #self.empty_houses.remove(empty_house)
    #self.empty_houses.append((x, y))
        
        
    def plot(self, title, file_name):
        fig, ax = plt.subplots()
    #If you want to run the simulation with more than 7 colors, you should set agent_colors accordingly
        agent_colors = {1:'b', 2:'r', 3:'g', 4:'c', 5:'m', 6:'y', 7:'k'}
        for agent in self.agents:
            ax.scatter(agent[0]+0.5, agent[1]+0.5, color=agent_colors[self.agents[agent]])

            ax.set_title(title, fontsize=10, fontweight='bold')
            ax.set_xlim([0, self.width])
            ax.set_ylim([0, self.height])
            ax.set_xticks([])
            ax.set_yticks([])
            plt.savefig(file_name)

    
```

# Lotka-Voltera( grabljivac- žrtva modeli) : igra zečeva i lisica

Grabljivac-plijen model, u konkretnom slučaju, simulira konkurenciju  između dvije populacije za ograničeni resusrs. Probajte se i sami zamisliti, vjerovatno ćete oko sebe naći brojne situacije čija dinamika može biti zahvaćena ovakvim modelom. 

Zamisao se sljedeća, neka postoji jedan zatvoren ekosistem koji se sastoji od lisica i zečeva. Tu se zečevi hrane raznim biljkama, kojih ima u izobilju, i u odsustvu predatora, kao što su lisice, njihova brojnost raste jako brzo. Lisice, sa druge strane, ne mogu da se hrane travama, već se hrane zečevima i umjereno održavaju njihov broj. Ukoliko lisice postanu halapljive i ubiju previše zečeva, izumrijeće-neće imati šta jesti. 

Zamislimo da postoji kapacitet brojnosti, dakle koliko hrane može da se stvori u tom sistemu toliko zečeva i lisica tu mogu da opstaju. Nije li tako i u ekonomiji?- zatvorenom sistemu na prostoru države ? Kada nestane mogućnosti zaposlenja, mogućnosti za život kakvim se teži, kada je brojnost na maksimumu, odlaze li ljudi kao zečevi i lisice?

Pogledajmo grafik ispod. Vidimo da populacija brzo raste kada nije dostignut broj kapaciteta sistema.
I nije li tako bilo i kod nas ? Nije li posljeratna ekspanzija prije svega državnog sektora i masovnog zaposljavanja održala stope radjanja. Dok nema previše konkurencije za resurse, otvoren je rast prema većoj brojnosti.


```python

```


![png](output_33_0.png)


Po pitanju brojnosti zečeva i lisica, jednostavne dinamičke formule daju nam uvide u kretanja brojnosti.
Ciklusi nisu u fazi, dakle, kada plijen brzo raste, malo lisica je okolo. 

Možemo li tako 


```python

```


![png](output_35_0.png)



```python

```


![png](output_36_0.png)
