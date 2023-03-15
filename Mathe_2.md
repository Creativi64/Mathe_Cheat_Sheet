
# Mathe 2

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Mathe 2](#mathe-2)
  - [Stetigkeit](#stetigkeit)
  - [Differenzialrechnung](#differenzialrechnung)
    - [Sekanten- und Tangentensteigungen](#sekanten--und-tangentensteigungen)
  - [Differenzierbarkeit/Knickestelle](#differenzierbarkeitknickestelle)
  - [Ableitungsregeln](#ableitungsregeln)
    - [Potenz](#potenz)
    - [Faktor](#faktor)
    - [Konstantenregel](#konstantenregel)
    - [Summenregel](#summenregel)
    - [Produkt Regel](#produkt-regel)
    - [Quotientenregel](#quotientenregel)
      - [KehrwertRegel](#kehrwertregel)
    - [Ketten Regel](#ketten-regel)
    - [Ableitungen Physik](#ableitungen-physik)
  - [Kurven Diskussion](#kurven-diskussion)
    - [Definitionsmenge](#definitionsmenge)
    - [Nullstellen](#nullstellen)
      - [X-Achse](#x-achse)
      - [Y-Achsen Abschnitt](#y-achsen-abschnitt)
    - [Symmetrie](#symmetrie)
      - [achsen sysmetrie](#achsen-sysmetrie)
      - [Punkt sysmetrie](#punkt-sysmetrie)
    - [Verhalten Für $f$ für $|x|\to\infty$](#verhalten-für-f-für-xtoinfty)
    - [stetigkeit](#stetigkeit-1)
    - [Extrempunkte](#extrempunkte)
    - [Monotonie / Steigunsverhalten](#monotonie--steigunsverhalten)
    - [Wendepunkte](#wendepunkte)
    - [Krümmungsverhalten](#krümmungsverhalten)
  - [Unterschied WeP / TeP](#unterschied-wep--tep)
    - [WeP](#wep)
    - [TeP](#tep)
  - [Wendetangente und Wendenormale](#wendetangente-und-wendenormale)
    - [Wendetankgente](#wendetankgente)
    - [Wende Normale](#wende-normale)
- [Tests](#tests)

<!-- /code_chunk_output -->

---

## Stetigkeit

Sprungstelle / Durchziehen ohne stift abzusetzen

eine funktion $f$ heißt an der stelle $x_0 \in \mathbb{D}$ stetig,
falls der Grenzwert für $x \to x_0 $ existiert (Links = Rechts) und mit dem Funktionswert  $f(x_0)$ übereinstimmt

$$
\boxed{
  \lim\limits_{x \to x_0^+}=
\lim\limits_{x \to x_0^-}=
f(x_0)
  }
$$

Lokale Stetigkeit $\widehat{=}$ Stetigkeit an der stelle $x_0$

Globale Stetigkeit: Einen Rationale Funktion (ganzrationale funktionen in $\mathbb{R}$ oder gebrochen Rationale Funktion in $\mathbb{D}$) ist an jeder stelle ihres Definitions Breiche Stetig

Unstetigkeitstellen treten hauptzächlich an den nahtstelen abschnitsweiser definierten funktionen auf

## Differenzialrechnung

<html>
<head><meta name=viewport content="width=device-width,initial-scale=1"><meta charset="utf-8" /><script src="https://cdn.geogebra.org/apps/deployggb.js"></script></head><body><div id="ggbApplet"></div><script>var parameters = {"id": "ggbApplet","width": 1068,"height": 738,"showMenuBar": true,"showAlgebraInput": true,"showToolBar": true,"customToolBar": "0 39 | 1 501 67 , 5 19 , 72 75 76 | 2 15 45 , 18 65 , 7 37 | 4 3 8 9 , 13 44 , 58 , 47 | 16 51 64 , 70 | 10 34 53 11 , 24  20 22 , 21 23 | 55 56 57 , 12 | 36 46 , 38 49  50 , 71 | 30 29 54 32 31 33 | 17 26 62 73 , 14 68 | 25 52 60 61 | 40 41 42 , 27 28 35 , 6","showToolBarHelp": true,"showResetIcon": false,"enableLabelDrags": false,"enableShiftDragZoom": true,"enableRightClick": false,"errorDialogsActive": false,"useBrowserForJS": false,"allowStyleBar": false,"preventFocus": false,"showZoomButtons": true,"capturingThreshold": 3,"appletOnLoad": function(api) { /* api.evalCommand('Segment((1,2),(3,4))');*/ },"showFullscreenButton": true,"scale": 1,"disableAutoScale": false,"allowUpscale": false,"clickToLoad": false,"appName": "classic","buttonRounding": 0.7,"buttonShadows": false,"language": "de",/* use this instead of ggbBase64 to load a material from geogebra.org"material_id":"RHYH3UQ8",use this instead of ggbBase64 to load a .ggb file"filename":"myfile.ggb",*/"ggbBase64": "UEsDBBQAAAAIAHpim1P0ityMAgUAAG0lAAAXAAAAZ2VvZ2VicmFfZGVmYXVsdHMyZC54bWztmktv2zgQgM/bXyHotHuILcmW7ARRirTAYgOkabEJFnulJVrmhia1IhXL+fUdknr5lYeSJm4aH0wNxec3Q3JI6vhjMafWDc4E4Sy03Z5jW5hFPCYsCe1cTg/G9seTD8cJ5gmeZMia8myOZGj7KmWdD6ReMHZUHErT0I4oEoJEtpVSJFWW0ObTKSUM25ZVCHLE+AWaY5GiCF9GMzxH5zxCUpc1kzI96vcXi0WvqrXHs6QPBYt+IeJ+ksgehLYFTWcitMuHIyh3JfdioPN5juP2//1ybuo5IExIxCJoCHQrxlOUUyngEVM8x0xacpni0E45YdK2KJpgGtrflGT9Ps0w/sO2ykxAy7FPPvx2LGZ8YfHJfziCOJnlUHSZTwt9lQZef+aUZ1YW2gAJ2ML/JLQ93wdkNJ0hFaOTUrTEmXWDIH8Zg3LJI51bx04RFWWxup4vPMbmzbBMzwjoCGBaQmLQhmtbIsU41k+mf/AAqllqLbfKizjPYmEVoX2BLmxrWYa3JtRJNJlLcltW6bdj5ZKW0brlx/0S6sPwxjjFLIZEK4zdToyDsYasAqCsgp8Z8uBHQw7eIVdVrkOGQf5Yyl9Zm63Xia3rwcQAXdLh+0TRonvG/sYJtLnNePDO+FkZr1rw8Bdc5nQSw1Cof/Bp+DyluHhG8MYfKiGea6GG7j3dt1DO2Msjh1o7Ilc4DDw5I9E1wwKcO69Vrnr4i8Sweqn6dB78P1tREgEdkYjIu8FPcxapXtQwP+fZTZv+YOi8Bv+mzOfGv5UtjMkdbC0OnjmRoCV3NL6bpcCJkmoul5XcmHI3F+5XM2WeS6rqOmMStlVACdomNjpzjXF6BZm/sqsMMaH2Vqu2s1tTGVrepSX/XUv7oKVqbmI3KKvZt/XUzdfZuRr3QPGvrKxHTNRtEE93S/bKYB9vjd2NKOg22D1nuJ1eb7THRnQD3eMNhn9KsVns312th8x8WzxilEksCGL37S/oMmmN4W+VXGtgZDTQpVWP3vP5A603Hyiu2bDrmJ87PHRcN4CN+96atEK6sntQTE1EA9W4XS8BdU+Hwm5+EWfqdLry/o1Ukxu+sQmh08aKJJiZmROmEkdXsoQAUt8qSR31F66WlxDA21sVQLTODi3NSGGdmhynJuGpZ4KBCYYm8Gsi3TZzWpcpTEUt53Zthh9224H8THPF29DyC/jXLJ/jrDX4Lyq5thbfDH8oL2+f4zxosO8yjN1mICiJwWbmBLRyAH75HMHCrfzzieA0l3A9BrdOrLkeM3a7ILGcKYcM6p6SQtmHeTHjGbnlTNYwLGX1p1Tfo62cMHQwl3XjhO4+eSpGLKHNQDw1UqMLc3quE60frG1TUZsmNETDDHreeOCO/YEzckeH/jh4IFx33BnupqWAXTzdVh6ls6q0LGpdJFWz0oYinfHIC4Jh4PmHhyM3GI6ef+/2Zx3R7EP28ZRNq3wj6Tb0sDx02Z1RHuWiOfg1Us0ErO5NeR8oLwglKFs+zZzvYSpx0TgAV1po3dPvIdLdXQHQSdO0MyO1LsRNZ6YEuDH4iAI29roSwj6h6DrJeM5K622vMs/S9XIZ2EePfsI5xbATrbr1qZJbF7Eb6/ouQCb+VccbfKwSXU94sbIA3XObJJoRcK6F1gXplhHw8F5uLl4HpSlMkuZwSJ0qQmIdrp0yqudXn4i6eDzb7/m2uiNtzfRbHxb1q6+YTr4DUEsDBBQAAAAIAHpim1OV02HwYgMAACsRAAAXAAAAZ2VvZ2VicmFfZGVmYXVsdHMzZC54bWztmM1y0zAQgM/wFBrdiX9ip02nLpOBA8wAU4YLV1XeJAJHMpISx3013oFnYvXT4EDbmXQCw18OWf14V9K365Xk86fbVUM2oI1QsqLZKKUEJFe1kIuKru38ySl9evH4fAFqAVeakbnSK2YrWrond3pYG01OU9fG2raivGHGCE5J2zDrVCqq5vNGSKCEbI04k+oNW4FpGYd3fAkr9kpxZr2tpbXtWZJ0XTe6GXWk9CJBwybZmjpZLOwIJSU4dWkqGgtnaHdPuxt7vTxNs+T961dhnCdCGsskx4ngsmqYs3VjDRahgRVIS2zfAi5AScHHOEbDrqCp6Etpca3A3RQJX+sN6kflio6zMqUXjx+dc6V0bYjaVhRJqD6I6yA6xIvIQt8m9G1CXxcau9DY+cbEGTRL1RF19QEHrqjVaxw1TshX/DPY/Uw1ShNd0bwsKUHHZfkJJVfeGmvaJcPSKEvDLyumaZZNsjyoN6wHTTYMbcZB2doq7i361jlrTBzKj/1a1RB6ivi8FBgSDoyxgM7HVZoWoPalgBPngZHQ+6Aa2sOAeGf7BohdCv5RgkF35gMlV3gh6hpcbAYdEAuQGwSitCHb1A/So8Cnr13NxeA28/UeBfZeO4HNXh1nqsWWzILGLDw4y4MYB1EEUe6IwCcZpmncf0VbpjF60RB3/edJjJ0foohthRk/3/lsFquDwEnHPnAO9TNOD0ni/76P/1CP3k2XxDLgmr98vh+2fys50xaMYHLw7j5zHd9zn/zr3O8GifYlDPhd+voeP8ypD+I3nXqAeYYSEXq5S1DlsTDGNBySasipMc/uTM6Z2+HiKKMYiLdCjOwOhqiafgm1VvIbx0HTN5TjiPIhb86h+LNy7PmXGE7f7Q5F3B3K6SQtJsXRfPHQkD6I7EzzpVhBDWwfLe5xd6LFjfKYaPMM14MLKMLG68TfwfayxwwsMBsMud4TskfnGlLGNHDN/5qYvdTCrPapZr+Q6iQk4kB1irU/kKoEu1vnG1ceZtXyf1Y9hOWnNav9iSsu9e1Nfcg0BOjBwZYWtx+bRidHA/ITbhK33iNcY7gs9EFco4j2Dr1akNkkiJMgToOY3nntEKu2EVzY+z1p1nqO1+rbTsKxa9+pxW/r1CMfh4dK957kksFngeTmG8TFV1BLAwQUAAAACAB6YptTRczeXRoAAAAYAAAAFgAAAGdlb2dlYnJhX2phdmFzY3JpcHQuanNLK81LLsnMz1NIT0/yz/PMyyzR0FSoruUCAFBLAwQUAAAACAB6YptTajKCkyIKAADVIgAADAAAAGdlb2dlYnJhLnhtbM1a25LbuBF93v0KFB9SdjKj4f3iSHaN1469Vfaua8dJbZLKA0RCEjMUqSVBjcblH8h/7DfkKW/+k3xJTgMgdZ2xZsdxjW0KJAg0gNPdpxugh89W84ItRd3kVTmynIFtMVGmVZaX05HVyslpbD17+u1wKqqpGNecTap6zuXICqhl3w9PgzC2qY4vFiMrLXjT5KnFFgWX1GVkVZNJkZfCYnk2suI45rYY26dR4Men/kT4pzwdR6fOJHGiRCRj4YwtxlZN/qSsfuBz0Sx4Ki7SmZjzN1XKpRp1JuXiydnZ1dXVoJvfoKqnZ5hCc7ZqsrPpdDxAaTEssmxGlrl5Arlbva881c+1befs57dv9DinedlIXqaYMgHQ5k+//WZ4lZdZdcWu8kzOAJcdxhabiXw6AySRh4czarUALguRynwpGvTdeFSrl/OFpZrxkt5/o+9Y0S/MYlm+zDNRjyx7EPmRkzi247hekASBY7GqzkUpTVs8qzHPOmnDZS6utFi6UyP6dhJBXXmTjwsxsia8aEgT5aQGtv1zI68LMeYYVdYtntcTck7UXzTJP6C9b0PRGgroMohPnNg9iWz7JAjwgqazMXbguBaTVVUoyTb7yBwW2LiYk7ATFkaocZkTMB81MWoi5lFd4PjMY9TE8Zjvo/Sp2gnpXYD+gc0cB9XMtZnrMtdhrofHIGBByIKIOrpoGyZKmI2LWmM6uDyq8zxcqs7zcbl0B0GBFoNJBF6o7gJqDfkBRvrIVKUXMz/BQFQRRA7zMAc8RzaDRAjGRNUifJvRP4f5JN6NmBszyMO6SbINaI7XiqnYUUunlGBTKQ6UQVeIS2lrRymw1F4laOfQfG2b4ELhMfZR3dC6UfjmkZBHobRgA1BdG9MPMAbSIQtjdXPPVXndmry7rAlI9KNqAz7ewPsRAxfQHDuiv23YsGMbFgI12zAWVZDSAYt6BZSpDvCqQtkDgasKQE1tYCv0CHtRhW6jjB8FJnkPF+5W6CbB8Su8n32uUfUIKj4eWedvXr18/tP5/gzc4Aat3tOYuik4RE3doBhL/VPX3pDenVZ9I9B3GDHcsqSvPbpDNv8lMPbjo8eMUHXAd3QJOlLl19HD8KyLmEMzI9bMqK0hESnmyB1A7BRIdOxC0AJ76wAWuSwKWETk2IUxRJ6YhVSaWEaRLN6KZQFFui6gIZqFVInoQZTKVDjSwc31u/iGexXhKPptRzgEJH8dkzBBEkWUboISRnc3w5ILnsakiYcQY4mymQuRLkM0C6nfDREL6VzV5D26M1Eg1TN6UEDm5aKVW+Clc8p31K2s0JoXKk0z7bMqvXzew20kCd4gmVqLRWazzp90prOVXn0zLPhYILecXpAtMLbkBTmRGmFSlZJ1dhBT3fBMpXJD0aZFnuW8/AuU36VNP7TzsahhdLitaJFKCHVnXc4XJRspXxgHuklaVXV2cd3AVtjqb6JG58BBSpwkUeS5sQvSTSx2rd/4oTcI/DBIEDe90Ea+AVNNOVm5jze2EzpJ4IaeHQcuiOF6552TeElix46ZnVheCCmx/IbxlYClarintUo1+/vvm+dVgRoD7KLKS/kdX8i2Vqk+plDTms7LaSEUkIr8kQmnl+NqdaFDB0yAZL2/XuDJQDyeflcVVc3ggm6A0AJhqgTZU6na0MT6VnA7tMEvWhgZJLR/n9AoukALFKoJbR60gvUqsXyzRtcI4au8UdwC0Zs2qMwDD+AONs9Li7VlLt/oSphlnl6a9RJjoJ82gh5IavAi11sB1YYqXq4WtcAWx7iC9oulOMcUTL/tKRnRO1PCu5Jdzr/mjAgy7C4a+TPtLaAmuv/rxv37mZBcPdN+I46iAL9uEhvn2XGb4aWoS1GQ5LYRjfdCe996vBQOmJdt1Tb6jTY/9Qod3nE5Oy+zn8QU837HidklFrorJBNpPkdHXe8abMlS/wzgdG0mprXoYNcso83F0AFrgA/PmpkQcFxjMtptN5upRXaLGiJlKYSKWTCckXUKj5jzlfIMuDr4TPngsEnrfEEuyMaIP5di7WZAlET0FdQakDRYG/irKqE6SYrGvrmVswrWjz5cUg1xVK/TzmIm4McVse4j+ZiN2PeTv9vsv//6lUn169gn7BE0x34PyivR5DH7A1XEqJCP/wFDUY47aUs1uJqNKMQcu8ndV+sBFQPCCFk1/idId9er1INYUjKsIEWrNR/YoK8NX2e8WMzIuIxL82si2w26VkJ/nEwaIRlgBtNeA3XHsIh6+7bKNpVFdgDbUFh2KoGqBUFOnmGYig4irhXRbRjgmlLkDB6E7TNcBfvkvhPdvM6zTCif0vav4VJqnM95mbFSpSPviE8VVjoIcpuw04i0sqs510JM1z30FSn30J7fFXoYVqbCsyKNH02f8b5eNhmYDhTuqJZTh2JZ74i/WS1EUwfUopyyoYEcTBHjRIPIRdhNfN8PAuzYwVQf+uCsMKPwpEc3pqJr9xz7ftp7eRftvXy42oOJA1Uz7P9Pe1p5+P3CynpDx4jbusJ+kjtGQVsqm96uMn0iaTQy/YzGuvz0cypL91XmuMC8V5pKj+6oNSSvigv9w05natfgH/AZRaVaHd0YhwgQLW8mQKSbv5S6i9p5jSyEoyJPc3m7zt6LlZzkosh2FKf0s+1kMCisbYK2hnJvUp7sZfY+t9l3T5ndvnXD/271rbvHK9/WWnLCzff7ztWu8iLn9fVesoR8nKxJVcPMdiDdTwcIVvihSgl+90tbyT++5pLh4Jidt7Ka8FmN2ywX7ENbfPoVXaeCvf7073TWyKlo0hntivPppaAkClID+3J+NmOf/kPZZjqrcylF+UwLPpAskAJ6PPVUjuY8A8V9sd/DdpKvRLaLKx83VdFKfEBAilh2HxCUWzm0waJjv9vt96KoFruks2+789sNtmznoqavIgaOuRKIubbdGgbRrtfqDejtiN7CRdkBLgqw1wPQFDq2kR7gHE79cfwE3xtCHNwfGVKQD5PZewc1Y4jjINnQp4Gjsq19218au380R3Yb2o/1YcHtiC93EffDgRdG2IWHYeR5TpwcbZaHwdqa8tZUxjhaEnydWPPdqaxVeYy6vxxp4aBBuwDOlw+pz9R2JwFMediNrPVqh1Z4+QFnJULvNY4GZ/xQwAlNroQz81tI50hs3rXlpcT5xW+CJH0okLih9nYfnxTvj8krUXP0/HCVw25Eyc5ZO2Am0f5c5AN1b0Q+hCwpikKyt4M/tYhwOLoc2OHAxZHZ8RHMf6ARTJ1jNuCyyfrkG2n0WxUzuoPuU5yYmaysyzRuDHxBhMbk9dEdeUtncA/ADumbiaKtL+GaFxIu2eIA50bnPGiBYM4NC3zR1rC7dIYzKdns5le9hSO+sbHA1/2SaUJQRo9M4+UTpuXg0GaJyzxQSmYM+ECE27Ng72gLVid6NyUO/IHkZ5HeuPiuisybGkGatT5HU+f65v+APP0fUEsBAhQAFAAAAAgAemKbU/SK3IwCBQAAbSUAABcAAAAAAAAAAAAAAAAAAAAAAGdlb2dlYnJhX2RlZmF1bHRzMmQueG1sUEsBAhQAFAAAAAgAemKbU5XTYfBiAwAAKxEAABcAAAAAAAAAAAAAAAAANwUAAGdlb2dlYnJhX2RlZmF1bHRzM2QueG1sUEsBAhQAFAAAAAgAemKbU0XM3l0aAAAAGAAAABYAAAAAAAAAAAAAAAAAzggAAGdlb2dlYnJhX2phdmFzY3JpcHQuanNQSwECFAAUAAAACAB6YptTajKCkyIKAADVIgAADAAAAAAAAAAAAAAAAAAcCQAAZ2VvZ2VicmEueG1sUEsFBgAAAAAEAAQACAEAAGgTAAAAAA==",};/* is3D=is 3D applet using 3D view, AV=Algebra View, SV=Spreadsheet View, CV=CAS View, EV2=Graphics View 2, CP=Construction Protocol, PC=Probability Calculator DA=Data Analysis, FI=Function Inspector, macro=Macros*/var views = {'is3D': 1,'AV': 0,'SV': 0,'CV': 0,'EV2': 0,'CP': 0,'PC': 0,'DA': 0,'FI': 0,'macro': 0};var applet = new GGBApplet(parameters, '5.0', views);window.onload = function() {applet.inject('ggbApplet')};applet.setPreviewImage('data:image/gif;base64,R0lGODlhAQABAAAAADs=', 'https://www.geogebra.org/images/GeoGebra_loading.png', 'https://www.geogebra.org/images/applet_play.png');</script></body>
</html>

Geschwindigkeit von anfang bis ende $\to$ steigung

$$
m=\frac{\triangle y}{\triangle x}
$$

$$
Geschwindigkeit = \frac{Strecke}{Zeit}= V\frac{s}{t}
$$

$$
\frac{7,7}{10min}*60min/h \approx 46,2 \text{ Km/h}
$$

$V_{max}\approx$ 78 Km/h bei $t=6$ min
$V_{min}\approx$ 18 Km/h bei $t=3.1$min

### Sekanten- und Tangentensteigungen

$$\tan a =m_t \\ \tan a = \frac{G}{A}$$

$$m_n=-\frac{1}{m_t}\text{,wenn }m_t \not ={0}$$

negativer Kehrwert der Tangentensteigung

$$\perp :m_n+m_t =-1$$

## Differenzierbarkeit/Knickestelle

Funktion muss an der zu untersuchenden stelle $x_0$ stetig sein

Ist die <ins>steigung links</ins> gleicher der <ins>steigung rechts</ins>, dann hat diese funktion an der stelle $x_0$ <ins>keinen knick</ins>

Die Funktion ist an der stelle $x_0$ <ins>Differenzierbar</ins>

$$\boxed{\lim\limits_{x \to x_0}f'(x)=\lim\limits_{x \to x_0}f'(x)}$$

---

$$f(x)=\begin{cases}(x+1)^2-1& \text{für } x \leq 0 \\2x& \text{für } x > 0\end{cases}$$

$$g(x)=\begin{cases}x(x+3)& \text{für } x \leq 0 \\2x& \text{für } x > 0\end{cases}$$

$$
\lim\limits_{x\to0^+}
\bigg(\frac{f(x)-f(x_0)}{x-x_0}\bigg)=
\lim\limits_{x\to0^+}
\bigg(\frac{2x-2*0}{x-0}\bigg)=
\lim\limits_{x\to0^+}
\bigg(\frac{2 \textcolor{red}{x}}{\textcolor{red}{x}}\bigg)=2
$$

$$
\lim\limits_{x\to0^-}
\bigg(\frac{f(x)-f(x_0)}{x-x_0}\bigg)=
\lim\limits_{x\to0^-}
\bigg(\frac{(x+1)^2-1-[(0+1)^2-1]}{x-0}\bigg)=
\lim\limits_{x\to0^-}
\bigg(\frac{2^2+2x\textcolor{red}{+1-1}}{x-0}\bigg)=
\lim\limits_{x\to0^-}\bigg(\frac{\textcolor{red}{x}(x+2)}{\textcolor{red}{x}} \bigg)=2
$$

$$
\lim\limits_{x\to0^-}
\bigg(\frac{g(x)-g(x_0)}{x-x_0}\bigg)=
\lim\limits_{x\to0^-}
\bigg(\frac{\textcolor{red}{x}(x+3)-0}{\textcolor{red}{x}-0}\bigg)=3
$$

$f(x)$ ist differenzierbar
$g(x)$ ist nicht differenzierbar

## Ableitungsregeln

### Potenz

$$
f(x)=x^m \qquad m \in \mathbb{Q}\ \{0\}
$$

$$
\bigg(f'(x)=m*x^{m-1}\bigg)=\bigg( \frac{d}{dx}(x^r)=(r*x^{r-1})\bigg)
$$

---

$$
\begin{align*}
  f(x)&=x^3\\
  f'(x)&=3x^2
\end{align*}
$$

$$
\begin{align*}
  f(x)&=\frac{1}{x^7}=x^{-7}\\
  f'(x)&=-7x^{-7-1}=-7x^{-8}\\
  f'(x)&=-\frac{7}{x^8}
\end{align*}
$$

$$
\begin{align*}
  f(x)&=\sqrt{x}=x^{\frac{1}{2}}\\
  f'(x)&=\frac{1}{2}x^{\frac{1}{2}-1}=\frac{1}{2}x^{-\frac{1}{2}}\\
  f'(x)&=\frac{1}{2}*\frac{1}{\sqrt{x}}=\frac{1}{2\sqrt{x}}
\end{align*}
$$

### Faktor

$$
g(x)=a*f(x)\qquad a \in \mathbb{R}
$$

$$
\bigg(g'(x)=a*f'(x)\bigg)=\bigg( f'(x)=c*u'(x)\bigg)
$$

---

$$
f(x)=5x^3=5*3x^2=15x^2
$$

$$
f(s)=-2x^{10}=-2*10x^9=-20x^9
$$

### Konstantenregel

$$
f(x)=c \text{ mit x,c } \in \mathbb{R} \text{ gilt: } f(x)=0
$$

---

$$
f(x)=3\\f'(x)=0
$$

### Summenregel

Sind zwei funktionen $u$ und $v$ differenzierbar auf einem infervall $D$, so ist auch die SummenFunktion $f=u+v$ auf $D$ Differenzierbar und es gilt für $x \in D$:
$$
f(x)=u(x)+v(x) \Rightarrow f'(x)=u'(x)+v'(x)
$$

---

$$
\begin{align*}
f(x)&=x^2+x^3\\
f'(x)&=2x^1+3x^2=2x+3x^2
\end{align*}
$$

$$
\begin{align*}
  f(x)&=x^7+10\\
  f'(x)&=7x^6+10 = 7x^6
\end{align*}
$$

### Produkt Regel

$$
f(x)=u(x)+v(x)=u'(x)*v(x)+u(x)*v'(x)
$$

---

$$
f(x)=x^5+x^3
$$

$$
\begin{align*}
  u(x)&=x^5 &\qquad u'(s)&=5x^4\\
  v(x)&=x^3 &\qquad v'(x)&=5x^2\\
\end{align*}
$$

$$
\begin{align*}
f'(x)&=5x^4*x^3+x^5*3x^2\\
&=5x^7+3x^7\\
&=8x^7
\end{align*}
$$

### Quotientenregel

Sind zwei funktionen $u$ und $v$ differenzierbar und gilt $v(x)\neq 0$, so ist auch die funktione $f$ mit $f(x)=\frac{v(x)}{v(x)}$ differenzierbar

$$
f(x)=\frac{u(x)}{v(x)}=\frac{u'(x)*v(x)-u(x)*v'(x)}{[v(x)]^2}
$$

#### KehrwertRegel

Ist die funktion $u(x)=1$ und die funktion $v$ differenzierbar und gilt $v(x)\neq0$, so ist auch $f(x)=\frac{1}{v(x)}$

$$
f(x)=\frac{1}{v(x)}\Rightarrow f'(x)=\frac{-v'(x)}{(v(x))^2}
$$

---

$$
f(x)=\frac{4x-2}{x+3} \qquad\mathbb{D=R \backslash \{3\}}
$$

$$
\begin{align*}
f'(x)&=\frac{4*(x+3)-(4x-2)\textcolor{grey}{*1}}{(x+3)^2}\\
&=\frac{\textcolor{red}{4x}+12\textcolor{red}{-4x}+2}{(x+3)^2}\\
&=\frac{14}{(x+3)^2}
\end{align*}
$$

### Ketten Regel

$$
k(x)=f[g(x)]
$$

$$
k'(x)=(f[g(x)])=f'[g(x)]*g'(x)
$$

--

$$
f(x)=u(v(x))
$$

$$
f'(x)=u'(v(x))*v'(x)
$$

Äusere mal innere ableitung

---

$$
k(x)=\underbrace{ (\overbrace{3x^4+2x}^{g(x)})^2}_{f(g(x))}
$$

$$
\begin{align*}
  f(x)&=(3x^4+2x)^2&\qquad f'(x)&= 2(3x^4+2x)\\
  g(x)&=3x^4+2x  &\qquad g'(s)&=12x^3+2 \\
\end{align*}
$$

$$
\begin{align*}
k'(x)&=2*(3x^4+2x)*(12x^3+2) \\
&=(6x^4+4x)*(12x^3+2) \\
&=72x^7+12x^4+48x^4+8x \\
&=72x^7+60x^4+8x
\end{align*}
$$

--

$$
k(x)=\sqrt{3x^4+2x}=(3x^4+2x)^{\frac{1}{2}}
$$

$$
\begin{align*}
k'(x)&=\frac{1}{2}*(3x^4+2x)*(12x^3+2) \\
&=\frac{12x^3+2}{2*(3x^4+2x)^{\frac{1}{2}}} \\
&=\frac{\textcolor{red}{2}*(6x^3+1)}{\textcolor{red}{2}*\sqrt{3x^4+2x}} \\
&=\frac{6x^3+1}{\sqrt{3x^4+2x}}
\end{align*}
$$

### Ableitungen Physik

Zeit-Weg-Gesetz: $s=s(t)$
Zeit-Geschwindigkeits-Gesetz: $v=v(t)=\dot{s}(t)$
Zeit-Beschleunigungs-Gesetz: $a=a(t)=\dot{v}(t)= \ddot{s}(s)$

## Kurven Diskussion

```gnuplot {cmd=true output="html"}
set terminal svg
set title "Simple Plots" font ",20"
set key left box
set samples 500
set xtics axis
set ytics axis
set style data points
set output
set xzeroaxis ls 7
set yzeroaxis ls 7
set terminal win
f(x)=0.08333*x**3+0.125*x**2-1.5*x+2
f1(x)=0.25*x**2+0.25*x-1.5
f2(x)=0.5*x+0.25
set arrow from -3, graph 0 to -3,graph 1 nohead
set arrow from 2, graph 0 to 2,graph 1 nohead
set arrow from -0.5, graph 0 to -0.5,graph 1 nohead
plot [-6:6][-2:6]  f(x),f1(x),f2(x)
```

### Definitionsmenge

wenn nicht angegeben grundemenge ist immer ganz $\mathbb{R}$#

Für $x$ einsetz bares $\mathbb{D}$ |alles was man einsetzen kann, bei ganzratzionalen funktionen nur $\mathbb{R}$ bei gebrochenen $\mathbb{R} \backslash \{...\}$

für $y$ einsetz bares $\mathbb{W}$ |alles was herrauskommen kann,  oft $\mathbb{R}$

### Nullstellen

#### X-Achse

Nullstellen der grundlegenden Funktion Berechnen

Schlagwort: Abzisse -> X-Achse

$f(x)=0$

wenn man kein x ausklammern kann und nicht auf $x^2$ kommt,
Polynmo division mit erratener nullstelle (Taschenrechner rät gut), $(x-{geratenenNST})$

bsp.

$$
f(x)=x^4-8x^3+18x^2 \qquad x\in\mathbb{R}\\
f(x)=0\\
0=x^2(x^2-8x-18)=0\\
\rightarrow x_1,x_2=0\\
0=x^2-8x+18\\
x_3,x_4=\frac{+8\plusmn \sqrt{(-8)^2-4*1*18} }{2*1}\\
x_3,x_4=\frac{+8\plusmn \sqrt{-8} }{2}= ↯ \\
\implies Nst(0|0) \quad Doppelt
$$

#### Y-Achsen Abschnitt

Schlagowrt: Ordinate -> Y-Achse

$$
f(0)=0^4-8*0^3+18*0=0\\
\implies S_y(0|0)
$$

### Symmetrie

Beachten das $-x^4 = -x*-x*-x*-x = + ;\qquad -x^3 = -x*-x*-x=-$

#### achsen sysmetrie

$$
f(x)=f(-x)
$$

bsp.

$$
f(x)=x^4-8x^3+18x^2 \qquad x\in\mathbb{R}\\
f(-x)=(-x)^4-8(-x)^3+18(-x)^2\\
f(-x)\neq x^4+8x^3+18x^2\\
\implies\text{Nicht Achsen Symetrisch}
$$

#### Punkt sysmetrie

$$
\begin{align*}
f(-x)&=-f(x) \qquad |*(-1)\\-f(-x)&=f(x)
\end{align*}
$$
bsp.w
$$
f(x)=x^4-8x^3+18x^2 \qquad x\in\mathbb{R}\\
-f(-x)=-((x)^4+8(x)^3+18(-x)^2)\\
-f(-x)\neq -x^4-8x^3-18x^2\\
\implies\text{Nicht Punkt Symetrisch}
$$

### Verhalten Für $f$ für $|x|\to\infty$

**Grenzwerte**
Nur die Höchste Potentz ist relevant

bsp. $\frac{1}{12}x^3$

$x^3$ ist ungerade

$$
\begin{align*}
   \rightarrow\quad&x\to-\infty&:&f(x)\to- \infty\\
  &x\to+\infty&:&f(x)\to+\infty
\end{align*}
$$

Koeffizient $\frac{1}{12}$ ist positiv

Lim für $\lim\limits_{x\to x_0^+}$ und $\lim\limits_{x\to x_0^-}$

ergibnt $\infty$ und $-\infty$

### stetigkeit

Eine Ungebrochene funktionen ist  Stetig

$$\lim\limits_{x\to x_0^-} f(x)=\lim\limits_{x\to x_0^+} f(x)=f(x)$$

Wenn der Nenner bei einer gebrochen rationalen funktion mit einem Faktor im zähler gekürzt werden kann dann ist die Definitions lücke behebbar

Es ist nur die höchste potenz relevant

bsp.

Positive seite

$$
\lim_{x\rightarrow \infty}(x^4-8x^3+18x^2)=\lim_{x\rightarrow \infty}x^4(1-\frac{8}{x}+\frac{18}{x^2})=\infty(1-0^++0^+)=0*\infty=+\infty
$$

negative seite

$$
\lim_{x\rightarrow -\infty}(x^4-8x^3+18x^2)=\lim_{x\rightarrow -\infty}x^4(1-\frac{8}{x}+\frac{18}{x^2})=\infty(1-0+0)=0*\infty=+\infty
$$

Die funktion verläuft auf beiden seiten ins positive unendlich

### Extrempunkte

Die Nullstelle der 1. Ableitung sind Mögliche Extrema, müssen aber nicht

**HOP / TIP**

$$
f'(x)=0
$$

Vorzeichen wechsel von $f'(x)$ ->Extrempunkt

Vorzeichen Bleibt Gleich ->Terassenpunkt (TEP)


HOP oder Top?

VZW  von **+** zu **-** $f'$ -> HOP$(x_1|f(x_1))$

VZW  von **-** zu **+** $f'$ -> TIP$(x_1|f(x_1))$

---

$$
f'(x)=0\\
\frac{1}{4}x^2+\frac{1}{4}x+\frac{3}{2}=0
$$
$$lösungsformel\\x_1=-3\\x_2=2$$

Vorzeichen Tabelle

|          |                  |     |             |     |            |
| -------- | ---------------- | --- | ----------- | --- | ---------- |
| x        | --               | -3  | --          | 2   | --         |
| $f'(x)$  | +                | 0   | -           | 0   | +          |
| steigung | $\nearrow$       | --  | $\searrow$  | --  | $\nearrow$ |
| --       | $\big\backslash$ | VZ  | $\bigwedge$ | VZ  | $\big/$    |
| --       | --               | HOP | --          | TIP | --         |

---

um die verlaufs form bestimmen zu können um die zahlen ein ne minimal großere oder kleiner zahl wähne und einsetzen vorzeichen bestimmt dann den verlauf

<svg xmlns="http://www.w3.org/2000/svg">
<rect x="21" y="66" width="299" height="4" fill="rgb(0, 0, 0)" />
<rect fill="rgb(0, 0, 0)" x="65" y="18" width="4" height="101" />
<rect x="72" y="18" width="4" height="97" fill="rgb(0, 0, 0)" />
<rect x="110" y="19" width="3" height="101" fill="rgb(0, 0, 0)" />
<rect x="139" y="17" width="3" height="101" fill="rgb(0, 0, 0)" />
<rect fill="rgb(0, 0, 0)" x="229" y="18" width="3" height="101" />
<rect fill="rgb(0, 0, 0)" x="260" y="20" width="3" height="101" />
<text textLength="21" font-size="38" x="35" y="49.9" fill="rgb(0, 0, 0)">x
</text>
<text textLength="33.9" font-size="25" x="25.6" y="96.8" fill="rgb(0, 0, 0)">f'(x)
</text>
<text textLength="38.9" font-size="41" x="80.6" y="103.2" fill="rgb(0, 0, 0)">+
</text>
<text fill="rgb(0, 0, 0)" font-size="41" x="168.6" y="104.2" textLength="38.9">-</text>
<text fill="rgb(0, 0, 0)" font-size="41" x="268.6" y="99.2" textLength="38.9">+</text>
<text fill="rgb(0, 0, 0)" font-size="25" x="237.9" y="55.8" textLength="23.2">2</text>
<text textLength="23.2" font-size="25" x="230.9" y="104.8" fill="rgb(0, 0, 0)">0</text>
<text fill="rgb(0, 0, 0)" font-size="25" x="111.9" y="52.8" textLength="23.2">-3</text>
<text fill="rgb(0, 0, 0)" font-size="25" x="115.9" y="103.8" textLength="23.2">0</text>
<path stroke="rgb(0, 0, 0)" d="M 272 16 C 199 166 166 152 97.1 14.9" fill="none"></path>
</svg>

---

### Monotonie / Steigunsverhalten

VZ tabelle Von Extrempunkt weiter nutzbar

$f'(x) < 0$ -> Streng Monoton Fallend
$f'(x) > 0$ -> Streng Monoton steigend

intervalle

Streng monton steigend/Fallend ist wenn bis zum steigungs wechsel im verlauf keine unterbrechung ist

monoton steigend/Fallend ist wenn der verlauf durch z.b. einen Terrasen punkt

$$
\begin{align*}
  f(x)\text{ ist im } &I_1 =]-\infty;-3[ & \text{streng monoton steigend (sms)} \\
  &I_2 = ]-3;2[& \text{streng monoton fallend (smf)} \\
  &I_3 =]2;\infty[& \text{streng monoton steigend (sms)}\\
\end{align*}
$$

<!-- +++ nicht strenge Monotonie -->

### Wendepunkte

WEP

Wenn $f''(x)$ and der stelle $x_1$ einen VZ wechsel hat und ungrade vielfachheit -> WEP

Doppelte NST ->Terrassenpunkt ohne Krümmungs Änderung

mit VZTabelle

---

$$f''(x)=\frac{1}{2}x+\frac{1}{4}$$

$$0=\frac{1}{2}x+\frac{1}{4}\\x_3=-\frac{1}{2}$$

|        |     |                |     |
| ------ | --- | -------------- | --- |
| x      | /   | $-\frac{1}{2}$ | /   |
| f''(x) | -   | 0              | +   |
| /      | /   | VZ             | /   |
| /      | /   | WEP            | /   |

WEP$(-\frac{1}{2}|f(-\frac{1}{2}))$

<svg xmlns="http://www.w3.org/2000/svg">
<rect x="21" y="67" width="299" height="4" fill="rgb(0, 0, 0)" />
<rect fill="rgb(0, 0, 0)" x="65" y="18" width="4" height="101" />
<rect x="72" y="18" width="4" height="97" fill="rgb(0, 0, 0)" />
<rect x="161" y="18" width="3" height="101" fill="rgb(0, 0, 0)" />
<rect x="216" y="20" width="3" height="101" fill="rgb(0, 0, 0)" />
<text font-size="38" textLength="21" fill="rgb(0, 0, 0)" x="35" y="49.9">x</text>
<text font-size="25" textLength="33.9" fill="rgb(0, 0, 0)" x="25.6" y="96.8">f'(x)</text>
<text textLength="38.9" font-size="41" x="122.6" y="102.2" fill="rgb(0, 0, 0)">-</text>
<text textLength="38.9" font-size="41" x="233.6" y="101.2" fill="rgb(0, 0, 0)">+</text>
<text textLength="43.2" font-size="25" x="168.9" y="49.8" fill="rgb(0, 0, 0)">-0,5</text>
<text fill="rgb(0, 0, 0)" font-size="25" x="174.9" y="98.8" textLength="23.2">0</text>
<path transform="matrix(0,-1,1,0,108,282)" stroke="rgb(0, 0, 0)" d="M 276 148 C 276 148 143 13 143 13" fill="none"/>
</svg>

### Krümmungsverhalten

VZ tabelle Von Wendepunkt weiter nutzbar

$f''(x)<0 \to$ ist rechts gekrümmt (steigung nimmt ab)
$f''(x)>0 \to$ ist links gekrümmt (steigung nimmt zu)

Die richung stellt man sich vor indem man von oben drauf schaut auf den verlauf

$$
\begin{align*}
  f(x)\text{ ist } &I_1 =]-\infty &;-\frac{1}{2}[ & \text{ rechtsgekümmt} \\
  &I_2 =]\frac{1}{2}&;\infty[& \text{ Linksgekrümmt}\\
\end{align*}
$$

<!-- Krümmung mit 3 krümmungen -->

## Unterschied WeP / TeP

### WeP

$f''(x_0) =0$ und $f(x)$ wechselt an der stellte das vorzeichen

alt.

$f''(x_0)=0 \land f''(x)\neq0$

### TeP

$f''(x_0) =0$ und $f(x_0)=0$ Und $f''(X)$ wechselt an der stelle das vorzeichen

Wird einmal  Flach also die steigung 0

alt.

$f''(x_0)=0 \land f'''(x_0)\neq0\land f'(x_0)=0$

## Wendetangente und Wendenormale

<!-- ```gnuplot {cmd=true output="html"}
set terminal win
set title "Simple Plots" font ",20"
set key left box
set samples 500
set grid nopolar
set grid xtics ytics 
set grid front   lt 0 linecolor 0 linewidth 0.500,  lt 0 linecolor 0 linewidth 0.500
set style data points
f(x)=-(1.0)/(6.0)*x**4+x**2-(4.0/3.0)*x+(1.0/2.0)  
t(x)=-(8.0/3.0)*x
n(x)=(3.0/8.0)*x+(73.0/24.0)  
plot [-4:4][-4:5] f(x),t(x),n(x)
``` -->

$$
f(x)=-\frac{1}{6}x^4+x^2-\frac{4}{3}x+\frac{1}{2}
$$

<?xml version="1.0" encoding="windows-1252"  standalone="no"?><svg  width="600" height="480" viewBox="0 0 600 480" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><title>Gnuplot</title><desc>Produced by GNUPLOT 5.4 patchlevel 2 </desc><g id="gnuplot_canvas"><rect x="0" y="0" width="600" height="480" fill="none"/><defs>	<circle id='gpDot' r='0.5' stroke-width='0.5' stroke='currentColor'/>	<path id='gpPt0' stroke-width='0.222' stroke='currentColor' d='M-1,0 h2 M0,-1 v2'/>	<path id='gpPt1' stroke-width='0.222' stroke='currentColor' d='M-1,-1 L1,1 M1,-1 L-1,1'/>	<path id='gpPt2' stroke-width='0.222' stroke='currentColor' d='M-1,0 L1,0 M0,-1 L0,1 M-1,-1 L1,1 M-1,1 L1,-1'/>	<rect id='gpPt3' stroke-width='0.222' stroke='currentColor' x='-1' y='-1' width='2' height='2'/>	<rect id='gpPt4' stroke-width='0.222' stroke='currentColor' fill='currentColor' x='-1' y='-1' width='2' height='2'/>	<circle id='gpPt5' stroke-width='0.222' stroke='currentColor' cx='0' cy='0' r='1'/>	<use xlink:href='#gpPt5' id='gpPt6' fill='currentColor' stroke='none'/>	<path id='gpPt7' stroke-width='0.222' stroke='currentColor' d='M0,-1.33 L-1.33,0.67 L1.33,0.67 z'/>	<use xlink:href='#gpPt7' id='gpPt8' fill='currentColor' stroke='none'/>	<use xlink:href='#gpPt7' id='gpPt9' stroke='currentColor' transform='rotate(180)'/>	<use xlink:href='#gpPt9' id='gpPt10' fill='currentColor' stroke='none'/>	<use xlink:href='#gpPt3' id='gpPt11' stroke='currentColor' transform='rotate(45)'/>	<use xlink:href='#gpPt11' id='gpPt12' fill='currentColor' stroke='none'/>	<path id='gpPt13' stroke-width='0.222' stroke='currentColor' d='M0,1.330 L1.265,0.411 L0.782,-1.067 L-0.782,-1.076 L-1.265,0.411 z'/>	<use xlink:href='#gpPt13' id='gpPt14' fill='currentColor' stroke='none'/>	<filter id='textbox' filterUnits='objectBoundingBox' x='0' y='0' height='1' width='1'>	  <feFlood flood-color='white' flood-opacity='1' result='bgnd'/>	  <feComposite in='SourceGraphic' in2='bgnd' operator='atop'/>	</filter>	<filter id='greybox' filterUnits='objectBoundingBox' x='0' y='0' height='1' width='1'>	  <feFlood flood-color='lightgrey' flood-opacity='1' result='grey'/>	  <feComposite in='SourceGraphic' in2='grey' operator='atop'/>	</filter></defs><g fill="none" color="white" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,66.01 L37.75,444.00 L574.82,444.00 L574.82,66.01 L37.75,66.01 Z  '/></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M46.14,129.01 L46.14,75.01 L139.04,75.01 L139.04,129.01 L46.14,129.01 Z  '/></g>	<g id="gnuplot_plot_1" ><title>f(x)</title><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(79.70,87.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text>f(x)</text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='rgb(148,   0, 211)'  d='M88.09,84.01 L130.65,84.01 M84.64,444.00 L85.11,439.34 L86.18,428.72 L87.26,418.32 L88.34,408.13 L89.41,398.14		L90.49,388.36 L91.56,378.78 L92.64,369.39 L93.72,360.21 L94.79,351.22 L95.87,342.42 L96.95,333.81 L98.02,325.39		L99.10,317.16 L100.17,309.11 L101.25,301.24 L102.33,293.55 L103.40,286.04 L104.48,278.71 L105.56,271.55 L106.63,264.56		L107.71,257.74 L108.79,251.09 L109.86,244.60 L110.94,238.28 L112.01,232.11 L113.09,226.11 L114.17,220.26 L115.24,214.57		L116.32,209.03 L117.40,203.65 L118.47,198.41 L119.55,193.32 L120.62,188.37 L121.70,183.57 L122.78,178.91 L123.85,174.39		L124.93,170.01 L126.01,165.77 L127.08,161.66 L128.16,157.68 L129.23,153.83 L130.31,150.11 L131.39,146.51 L132.46,143.04		L133.54,139.70 L134.62,136.47 L135.69,133.37 L136.77,130.38 L137.85,127.51 L138.92,124.75 L140.00,122.11 L141.07,119.58		L142.15,117.15 L143.23,114.84 L144.30,112.63 L145.38,110.52 L146.46,108.51 L147.53,106.61 L148.61,104.81 L149.68,103.10		L150.76,101.49 L151.84,99.97 L152.91,98.55 L153.99,97.22 L155.07,95.97 L156.14,94.82 L157.22,93.75 L158.29,92.76		L159.37,91.86 L160.45,91.04 L161.52,90.31 L162.60,89.65 L163.68,89.06 L164.75,88.56 L165.83,88.12 L166.91,87.77		L167.98,87.48 L169.06,87.26 L170.13,87.11 L171.21,87.03 L172.29,87.01 L173.36,87.06 L174.44,87.17 L175.52,87.34		L176.59,87.58 L177.67,87.87 L178.74,88.22 L179.82,88.63 L180.90,89.09 L181.97,89.60 L183.05,90.17 L184.13,90.79		L185.20,91.46 L186.28,92.17 L187.35,92.94 L188.43,93.75 L189.51,94.60 L190.58,95.50 L191.66,96.44 L192.74,97.43		L193.81,98.45 L194.89,99.51 L195.97,100.61 L197.04,101.75 L198.12,102.92 L199.19,104.13 L200.27,105.37 L201.35,106.64		L202.42,107.95 L203.50,109.28 L204.58,110.64 L205.65,112.03 L206.73,113.45 L207.80,114.90 L208.88,116.36 L209.96,117.86		L211.03,119.37 L212.11,120.91 L213.19,122.47 L214.26,124.04 L215.34,125.64 L216.41,127.26 L217.49,128.89 L218.57,130.54		L219.64,132.20 L220.72,133.88 L221.80,135.57 L222.87,137.27 L223.95,138.99 L225.02,140.72 L226.10,142.45 L227.18,144.20		L228.25,145.95 L229.33,147.71 L230.41,149.48 L231.48,151.26 L232.56,153.04 L233.64,154.82 L234.71,156.61 L235.79,158.40		L236.86,160.19 L237.94,161.99 L239.02,163.78 L240.09,165.58 L241.17,167.37 L242.25,169.17 L243.32,170.96 L244.40,172.75		L245.47,174.53 L246.55,176.32 L247.63,178.09 L248.70,179.87 L249.78,181.63 L250.86,183.39 L251.93,185.15 L253.01,186.89		L254.08,188.63 L255.16,190.36 L256.24,192.08 L257.31,193.79 L258.39,195.49 L259.47,197.18 L260.54,198.86 L261.62,200.53		L262.70,202.18 L263.77,203.83 L264.85,205.46 L265.92,207.07 L267.00,208.68 L268.08,210.26 L269.15,211.84 L270.23,213.40		L271.31,214.94 L272.38,216.47 L273.46,217.98 L274.53,219.48 L275.61,220.96 L276.69,222.42 L277.76,223.86 L278.84,225.29		L279.92,226.70 L280.99,228.09 L282.07,229.46 L283.14,230.81 L284.22,232.15 L285.30,233.46 L286.37,234.76 L287.45,236.03		L288.53,237.29 L289.60,238.52 L290.68,239.74 L291.76,240.93 L292.83,242.11 L293.91,243.26 L294.98,244.39 L296.06,245.51		L297.14,246.60 L298.21,247.67 L299.29,248.71 L300.37,249.74 L301.44,250.75 L302.52,251.73 L303.59,252.69 L304.67,253.63		L305.75,254.55 L306.82,255.45 L307.90,256.33 L308.98,257.18 L310.05,258.02 L311.13,258.83 L312.20,259.62 L313.28,260.39		L314.36,261.13 L315.43,261.86 L316.51,262.56 L317.59,263.25 L318.66,263.91 L319.74,264.55 L320.81,265.17 L321.89,265.77		L322.97,266.35 L324.04,266.91 L325.12,267.45 L326.20,267.97 L327.27,268.47 L328.35,268.95 L329.43,269.42 L330.50,269.86		L331.58,270.28 L332.65,270.69 L333.73,271.07 L334.81,271.44 L335.88,271.79 L336.96,272.13 L338.04,272.45 L339.11,272.75		L340.19,273.03 L341.26,273.30 L342.34,273.55 L343.42,273.78 L344.49,274.01 L345.57,274.21 L346.65,274.41 L347.72,274.58		L348.80,274.75 L349.87,274.90 L350.95,275.04 L352.03,275.17 L353.10,275.29 L354.18,275.39 L355.26,275.49 L356.33,275.57		L357.41,275.65 L358.49,275.71 L359.56,275.77 L360.64,275.82 L361.71,275.86 L362.79,275.90 L363.87,275.93 L364.94,275.95		L366.02,275.97 L367.10,275.98 L368.17,275.99 L369.25,276.00 L370.32,276.00 L371.40,276.00 L372.48,276.00 L373.55,276.00		L374.63,276.00 L375.71,276.01 L376.78,276.01 L377.86,276.01 L378.93,276.02 L380.01,276.03 L381.09,276.05 L382.16,276.07		L383.24,276.10 L384.32,276.13 L385.39,276.17 L386.47,276.22 L387.55,276.28 L388.62,276.35 L389.70,276.43 L390.77,276.52		L391.85,276.62 L392.93,276.74 L394.00,276.87 L395.08,277.02 L396.16,277.18 L397.23,277.36 L398.31,277.56 L399.38,277.78		L400.46,278.02 L401.54,278.28 L402.61,278.56 L403.69,278.86 L404.77,279.19 L405.84,279.54 L406.92,279.92 L407.99,280.32		L409.07,280.75 L410.15,281.22 L411.22,281.71 L412.30,282.23 L413.38,282.79 L414.45,283.38 L415.53,284.00 L416.60,284.66		L417.68,285.35 L418.76,286.09 L419.83,286.86 L420.91,287.67 L421.99,288.52 L423.06,289.42 L424.14,290.36 L425.22,291.34		L426.29,292.38 L427.37,293.45 L428.44,294.58 L429.52,295.76 L430.60,296.99 L431.67,298.27 L432.75,299.60 L433.83,300.99		L434.90,302.44 L435.98,303.94 L437.05,305.50 L438.13,307.12 L439.21,308.81 L440.28,310.56 L441.36,312.37 L442.44,314.25		L443.51,316.19 L444.59,318.20 L445.66,320.29 L446.74,322.44 L447.82,324.67 L448.89,326.97 L449.97,329.35 L451.05,331.81		L452.12,334.34 L453.20,336.96 L454.28,339.65 L455.35,342.43 L456.43,345.30 L457.50,348.25 L458.58,351.29 L459.66,354.41		L460.73,357.63 L461.81,360.95 L462.89,364.35 L463.96,367.85 L465.04,371.45 L466.11,375.15 L467.19,378.95 L468.27,382.85		L469.34,386.86 L470.42,390.97 L471.50,395.19 L472.57,399.52 L473.65,403.96 L474.72,408.51 L475.80,413.18 L476.88,417.96		L477.95,422.86 L479.03,427.88 L480.11,433.02 L481.18,438.29 L482.26,443.68 L482.32,444.00  '/></g>	</g>	<g id="gnuplot_plot_2" ><title>t(x)</title><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(79.70,105.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text>t(x)</text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='rgb(  0, 158, 115)'  d='M88.09,102.01 L130.65,102.01 M180.41,66.01 L180.90,66.82 L181.97,68.62 L183.05,70.41 L184.13,72.21 L185.20,74.01		L186.28,75.80 L187.35,77.60 L188.43,79.39 L189.51,81.19 L190.58,82.98 L191.66,84.78 L192.74,86.57 L193.81,88.37		L194.89,90.17 L195.97,91.96 L197.04,93.76 L198.12,95.55 L199.19,97.35 L200.27,99.14 L201.35,100.94 L202.42,102.73		L203.50,104.53 L204.58,106.33 L205.65,108.12 L206.73,109.92 L207.80,111.71 L208.88,113.51 L209.96,115.30 L211.03,117.10		L212.11,118.89 L213.19,120.69 L214.26,122.49 L215.34,124.28 L216.41,126.08 L217.49,127.87 L218.57,129.67 L219.64,131.46		L220.72,133.26 L221.80,135.05 L222.87,136.85 L223.95,138.65 L225.02,140.44 L226.10,142.24 L227.18,144.03 L228.25,145.83		L229.33,147.62 L230.41,149.42 L231.48,151.21 L232.56,153.01 L233.64,154.81 L234.71,156.60 L235.79,158.40 L236.86,160.19		L237.94,161.99 L239.02,163.78 L240.09,165.58 L241.17,167.37 L242.25,169.17 L243.32,170.97 L244.40,172.76 L245.47,174.56		L246.55,176.35 L247.63,178.15 L248.70,179.94 L249.78,181.74 L250.86,183.53 L251.93,185.33 L253.01,187.13 L254.08,188.92		L255.16,190.72 L256.24,192.51 L257.31,194.31 L258.39,196.10 L259.47,197.90 L260.54,199.69 L261.62,201.49 L262.70,203.28		L263.77,205.08 L264.85,206.88 L265.92,208.67 L267.00,210.47 L268.08,212.26 L269.15,214.06 L270.23,215.85 L271.31,217.65		L272.38,219.44 L273.46,221.24 L274.53,223.04 L275.61,224.83 L276.69,226.63 L277.76,228.42 L278.84,230.22 L279.92,232.01		L280.99,233.81 L282.07,235.60 L283.14,237.40 L284.22,239.20 L285.30,240.99 L286.37,242.79 L287.45,244.58 L288.53,246.38		L289.60,248.17 L290.68,249.97 L291.76,251.76 L292.83,253.56 L293.91,255.36 L294.98,257.15 L296.06,258.95 L297.14,260.74		L298.21,262.54 L299.29,264.33 L300.37,266.13 L301.44,267.92 L302.52,269.72 L303.59,271.52 L304.67,273.31 L305.75,275.11		L306.82,276.90 L307.90,278.70 L308.98,280.49 L310.05,282.29 L311.13,284.08 L312.20,285.88 L313.28,287.68 L314.36,289.47		L315.43,291.27 L316.51,293.06 L317.59,294.86 L318.66,296.65 L319.74,298.45 L320.81,300.24 L321.89,302.04 L322.97,303.84		L324.04,305.63 L325.12,307.43 L326.20,309.22 L327.27,311.02 L328.35,312.81 L329.43,314.61 L330.50,316.40 L331.58,318.20		L332.65,320.00 L333.73,321.79 L334.81,323.59 L335.88,325.38 L336.96,327.18 L338.04,328.97 L339.11,330.77 L340.19,332.56		L341.26,334.36 L342.34,336.16 L343.42,337.95 L344.49,339.75 L345.57,341.54 L346.65,343.34 L347.72,345.13 L348.80,346.93		L349.87,348.72 L350.95,350.52 L352.03,352.32 L353.10,354.11 L354.18,355.91 L355.26,357.70 L356.33,359.50 L357.41,361.29		L358.49,363.09 L359.56,364.88 L360.64,366.68 L361.71,368.47 L362.79,370.27 L363.87,372.07 L364.94,373.86 L366.02,375.66		L367.10,377.45 L368.17,379.25 L369.25,381.04 L370.32,382.84 L371.40,384.63 L372.48,386.43 L373.55,388.23 L374.63,390.02		L375.71,391.82 L376.78,393.61 L377.86,395.41 L378.93,397.20 L380.01,399.00 L381.09,400.79 L382.16,402.59 L383.24,404.39		L384.32,406.18 L385.39,407.98 L386.47,409.77 L387.55,411.57 L388.62,413.36 L389.70,415.16 L390.77,416.95 L391.85,418.75		L392.93,420.55 L394.00,422.34 L395.08,424.14 L396.16,425.93 L397.23,427.73 L398.31,429.52 L399.38,431.32 L400.46,433.11		L401.54,434.91 L402.61,436.71 L403.69,438.50 L404.77,440.30 L405.84,442.09 L406.92,443.89 L406.98,444.00  '/></g>	</g>	<g id="gnuplot_plot_3" ><title>n(x)</title><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(79.70,123.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text>n(x)</text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='rgb( 86, 180, 233)'  d='M88.09,120.01 L130.65,120.01 M37.75,211.26 L38.83,211.00 L39.90,210.75 L40.98,210.50 L42.06,210.25 L43.13,209.99		L44.21,209.74 L45.28,209.49 L46.36,209.24 L47.44,208.98 L48.51,208.73 L49.59,208.48 L50.67,208.23 L51.74,207.97		L52.82,207.72 L53.89,207.47 L54.97,207.22 L56.05,206.96 L57.12,206.71 L58.20,206.46 L59.28,206.21 L60.35,205.95		L61.43,205.70 L62.50,205.45 L63.58,205.20 L64.66,204.94 L65.73,204.69 L66.81,204.44 L67.89,204.19 L68.96,203.93		L70.04,203.68 L71.12,203.43 L72.19,203.18 L73.27,202.92 L74.34,202.67 L75.42,202.42 L76.50,202.17 L77.57,201.91		L78.65,201.66 L79.73,201.41 L80.80,201.16 L81.88,200.90 L82.95,200.65 L84.03,200.40 L85.11,200.15 L86.18,199.89		L87.26,199.64 L88.34,199.39 L89.41,199.14 L90.49,198.88 L91.56,198.63 L92.64,198.38 L93.72,198.13 L94.79,197.87		L95.87,197.62 L96.95,197.37 L98.02,197.12 L99.10,196.86 L100.17,196.61 L101.25,196.36 L102.33,196.11 L103.40,195.85		L104.48,195.60 L105.56,195.35 L106.63,195.10 L107.71,194.84 L108.79,194.59 L109.86,194.34 L110.94,194.09 L112.01,193.83		L113.09,193.58 L114.17,193.33 L115.24,193.08 L116.32,192.82 L117.40,192.57 L118.47,192.32 L119.55,192.07 L120.62,191.81		L121.70,191.56 L122.78,191.31 L123.85,191.06 L124.93,190.80 L126.01,190.55 L127.08,190.30 L128.16,190.05 L129.23,189.79		L130.31,189.54 L131.39,189.29 L132.46,189.04 L133.54,188.78 L134.62,188.53 L135.69,188.28 L136.77,188.03 L137.85,187.77		L138.92,187.52 L140.00,187.27 L141.07,187.02 L142.15,186.76 L143.23,186.51 L144.30,186.26 L145.38,186.01 L146.46,185.75		L147.53,185.50 L148.61,185.25 L149.68,185.00 L150.76,184.74 L151.84,184.49 L152.91,184.24 L153.99,183.99 L155.07,183.73		L156.14,183.48 L157.22,183.23 L158.29,182.98 L159.37,182.72 L160.45,182.47 L161.52,182.22 L162.60,181.97 L163.68,181.71		L164.75,181.46 L165.83,181.21 L166.91,180.96 L167.98,180.70 L169.06,180.45 L170.13,180.20 L171.21,179.95 L172.29,179.69		L173.36,179.44 L174.44,179.19 L175.52,178.94 L176.59,178.68 L177.67,178.43 L178.74,178.18 L179.82,177.93 L180.90,177.67		L181.97,177.42 L183.05,177.17 L184.13,176.92 L185.20,176.66 L186.28,176.41 L187.35,176.16 L188.43,175.91 L189.51,175.65		L190.58,175.40 L191.66,175.15 L192.74,174.90 L193.81,174.64 L194.89,174.39 L195.97,174.14 L197.04,173.89 L198.12,173.63		L199.19,173.38 L200.27,173.13 L201.35,172.88 L202.42,172.62 L203.50,172.37 L204.58,172.12 L205.65,171.87 L206.73,171.61		L207.80,171.36 L208.88,171.11 L209.96,170.86 L211.03,170.60 L212.11,170.35 L213.19,170.10 L214.26,169.85 L215.34,169.59		L216.41,169.34 L217.49,169.09 L218.57,168.84 L219.64,168.58 L220.72,168.33 L221.80,168.08 L222.87,167.83 L223.95,167.57		L225.02,167.32 L226.10,167.07 L227.18,166.82 L228.25,166.56 L229.33,166.31 L230.41,166.06 L231.48,165.81 L232.56,165.55		L233.64,165.30 L234.71,165.05 L235.79,164.80 L236.86,164.54 L237.94,164.29 L239.02,164.04 L240.09,163.79 L241.17,163.53		L242.25,163.28 L243.32,163.03 L244.40,162.78 L245.47,162.52 L246.55,162.27 L247.63,162.02 L248.70,161.77 L249.78,161.51		L250.86,161.26 L251.93,161.01 L253.01,160.76 L254.08,160.50 L255.16,160.25 L256.24,160.00 L257.31,159.75 L258.39,159.49		L259.47,159.24 L260.54,158.99 L261.62,158.74 L262.70,158.48 L263.77,158.23 L264.85,157.98 L265.92,157.73 L267.00,157.47		L268.08,157.22 L269.15,156.97 L270.23,156.72 L271.31,156.46 L272.38,156.21 L273.46,155.96 L274.53,155.71 L275.61,155.45		L276.69,155.20 L277.76,154.95 L278.84,154.70 L279.92,154.44 L280.99,154.19 L282.07,153.94 L283.14,153.69 L284.22,153.43		L285.30,153.18 L286.37,152.93 L287.45,152.68 L288.53,152.42 L289.60,152.17 L290.68,151.92 L291.76,151.67 L292.83,151.41		L293.91,151.16 L294.98,150.91 L296.06,150.66 L297.14,150.40 L298.21,150.15 L299.29,149.90 L300.37,149.65 L301.44,149.39		L302.52,149.14 L303.59,148.89 L304.67,148.64 L305.75,148.38 L306.82,148.13 L307.90,147.88 L308.98,147.63 L310.05,147.37		L311.13,147.12 L312.20,146.87 L313.28,146.62 L314.36,146.36 L315.43,146.11 L316.51,145.86 L317.59,145.61 L318.66,145.35		L319.74,145.10 L320.81,144.85 L321.89,144.60 L322.97,144.34 L324.04,144.09 L325.12,143.84 L326.20,143.59 L327.27,143.33		L328.35,143.08 L329.43,142.83 L330.50,142.58 L331.58,142.32 L332.65,142.07 L333.73,141.82 L334.81,141.57 L335.88,141.31		L336.96,141.06 L338.04,140.81 L339.11,140.56 L340.19,140.30 L341.26,140.05 L342.34,139.80 L343.42,139.55 L344.49,139.29		L345.57,139.04 L346.65,138.79 L347.72,138.54 L348.80,138.28 L349.87,138.03 L350.95,137.78 L352.03,137.53 L353.10,137.27		L354.18,137.02 L355.26,136.77 L356.33,136.52 L357.41,136.26 L358.49,136.01 L359.56,135.76 L360.64,135.51 L361.71,135.25		L362.79,135.00 L363.87,134.75 L364.94,134.50 L366.02,134.24 L367.10,133.99 L368.17,133.74 L369.25,133.49 L370.32,133.23		L371.40,132.98 L372.48,132.73 L373.55,132.48 L374.63,132.22 L375.71,131.97 L376.78,131.72 L377.86,131.47 L378.93,131.21		L380.01,130.96 L381.09,130.71 L382.16,130.46 L383.24,130.20 L384.32,129.95 L385.39,129.70 L386.47,129.45 L387.55,129.19		L388.62,128.94 L389.70,128.69 L390.77,128.44 L391.85,128.18 L392.93,127.93 L394.00,127.68 L395.08,127.43 L396.16,127.17		L397.23,126.92 L398.31,126.67 L399.38,126.42 L400.46,126.16 L401.54,125.91 L402.61,125.66 L403.69,125.41 L404.77,125.15		L405.84,124.90 L406.92,124.65 L407.99,124.40 L409.07,124.14 L410.15,123.89 L411.22,123.64 L412.30,123.39 L413.38,123.13		L414.45,122.88 L415.53,122.63 L416.60,122.38 L417.68,122.12 L418.76,121.87 L419.83,121.62 L420.91,121.37 L421.99,121.11		L423.06,120.86 L424.14,120.61 L425.22,120.36 L426.29,120.10 L427.37,119.85 L428.44,119.60 L429.52,119.35 L430.60,119.09		L431.67,118.84 L432.75,118.59 L433.83,118.34 L434.90,118.08 L435.98,117.83 L437.05,117.58 L438.13,117.33 L439.21,117.07		L440.28,116.82 L441.36,116.57 L442.44,116.32 L443.51,116.06 L444.59,115.81 L445.66,115.56 L446.74,115.31 L447.82,115.05		L448.89,114.80 L449.97,114.55 L451.05,114.30 L452.12,114.04 L453.20,113.79 L454.28,113.54 L455.35,113.29 L456.43,113.03		L457.50,112.78 L458.58,112.53 L459.66,112.28 L460.73,112.02 L461.81,111.77 L462.89,111.52 L463.96,111.27 L465.04,111.01		L466.11,110.76 L467.19,110.51 L468.27,110.26 L469.34,110.00 L470.42,109.75 L471.50,109.50 L472.57,109.25 L473.65,108.99		L474.72,108.74 L475.80,108.49 L476.88,108.24 L477.95,107.98 L479.03,107.73 L480.11,107.48 L481.18,107.23 L482.26,106.97		L483.34,106.72 L484.41,106.47 L485.49,106.22 L486.56,105.96 L487.64,105.71 L488.72,105.46 L489.79,105.21 L490.87,104.95		L491.95,104.70 L493.02,104.45 L494.10,104.20 L495.17,103.94 L496.25,103.69 L497.33,103.44 L498.40,103.19 L499.48,102.93		L500.56,102.68 L501.63,102.43 L502.71,102.18 L503.78,101.92 L504.86,101.67 L505.94,101.42 L507.01,101.17 L508.09,100.91		L509.17,100.66 L510.24,100.41 L511.32,100.16 L512.40,99.90 L513.47,99.65 L514.55,99.40 L515.62,99.15 L516.70,98.89		L517.78,98.64 L518.85,98.39 L519.93,98.14 L521.01,97.88 L522.08,97.63 L523.16,97.38 L524.23,97.13 L525.31,96.87		L526.39,96.62 L527.46,96.37 L528.54,96.12 L529.62,95.86 L530.69,95.61 L531.77,95.36 L532.84,95.11 L533.92,94.85		L535.00,94.60 L536.07,94.35 L537.15,94.10 L538.23,93.84 L539.30,93.59 L540.38,93.34 L541.45,93.09 L542.53,92.83		L543.61,92.58 L544.68,92.33 L545.76,92.08 L546.84,91.82 L547.91,91.57 L548.99,91.32 L550.07,91.07 L551.14,90.81		L552.22,90.56 L553.29,90.31 L554.37,90.06 L555.45,89.80 L556.52,89.55 L557.60,89.30 L558.68,89.05 L559.75,88.79		L560.83,88.54 L561.90,88.29 L562.98,88.04 L564.06,87.78 L565.13,87.53 L566.21,87.28 L567.29,87.03 L568.36,86.77		L569.44,86.52 L570.51,86.27 L571.59,86.02 L572.67,85.76 L573.74,85.51 L574.82,85.26  '/></g>	</g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,444.00 L574.82,444.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,444.00 L46.75,444.00 M574.82,444.00 L565.82,444.00  '/>	<g transform="translate(29.36,447.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,402.00 L574.82,402.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,402.00 L46.75,402.00 M574.82,402.00 L565.82,402.00  '/>	<g transform="translate(29.36,405.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,360.00 L574.82,360.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,360.00 L46.75,360.00 M574.82,360.00 L565.82,360.00  '/>	<g transform="translate(29.36,363.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,318.00 L574.82,318.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,318.00 L46.75,318.00 M574.82,318.00 L565.82,318.00  '/>	<g transform="translate(29.36,321.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,276.00 L574.82,276.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,276.00 L46.75,276.00 M574.82,276.00 L565.82,276.00  '/>	<g transform="translate(29.36,279.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 0</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,234.01 L574.82,234.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,234.01 L46.75,234.01 M574.82,234.01 L565.82,234.01  '/>	<g transform="translate(29.36,237.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,192.01 L574.82,192.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,192.01 L46.75,192.01 M574.82,192.01 L565.82,192.01  '/>	<g transform="translate(29.36,195.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,150.01 L574.82,150.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,150.01 L46.75,150.01 M574.82,150.01 L565.82,150.01  '/>	<g transform="translate(29.36,153.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,108.01 L46.14,108.01 M139.04,108.01 L574.82,108.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,108.01 L46.75,108.01 M574.82,108.01 L565.82,108.01  '/>	<g transform="translate(29.36,111.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,66.01 L574.82,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,66.01 L46.75,66.01 M574.82,66.01 L565.82,66.01  '/>	<g transform="translate(29.36,69.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 5</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,444.00 L37.75,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,444.00 L37.75,435.00 M37.75,66.01 L37.75,75.01  '/>	<g transform="translate(37.75,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M104.88,444.00 L104.88,129.01 M104.88,75.01 L104.88,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M104.88,444.00 L104.88,435.00 M104.88,66.01 L104.88,75.01  '/>	<g transform="translate(104.88,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M172.02,444.00 L172.02,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M172.02,444.00 L172.02,435.00 M172.02,66.01 L172.02,75.01  '/>	<g transform="translate(172.02,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M239.15,444.00 L239.15,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M239.15,444.00 L239.15,435.00 M239.15,66.01 L239.15,75.01  '/>	<g transform="translate(239.15,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M306.29,444.00 L306.29,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M306.29,444.00 L306.29,435.00 M306.29,66.01 L306.29,75.01  '/>	<g transform="translate(306.29,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 0</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M373.42,444.00 L373.42,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M373.42,444.00 L373.42,435.00 M373.42,66.01 L373.42,75.01  '/>	<g transform="translate(373.42,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M440.55,444.00 L440.55,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M440.55,444.00 L440.55,435.00 M440.55,66.01 L440.55,75.01  '/>	<g transform="translate(440.55,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M507.69,444.00 L507.69,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M507.69,444.00 L507.69,435.00 M507.69,66.01 L507.69,75.01  '/>	<g transform="translate(507.69,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M574.82,444.00 L574.82,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M574.82,444.00 L574.82,435.00 M574.82,66.01 L574.82,75.01  '/>	<g transform="translate(574.82,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="2.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="2.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,66.01 L37.75,444.00 L574.82,444.00 L574.82,66.01 L37.75,66.01 Z  '/></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(306.28,33.51)" stroke="none" fill="black" font-family="Arial" font-size="20.00"  text-anchor="middle"></g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g></g></svg>

### Wendetankgente

grundform

$ t(x)=m_t*x+S_{yt} $

1. Wep bestimmen


$$
\text{Wep   }(-1|\frac{8}{3})
$$

$$
x_0 =-1
$$

2.  $t_m$ bestimmen

$$
m_t=f'(x_0)=f'(-1)=-\frac{8}{3}
$$

3. $t(x_0)$

$$
t(x_0)=f(x_0)=f(-1)=\frac{8}{3} \widehat{=} \text{   y-wert des WEPs}
$$

4. y-Achsenabschnitt | $S_{yt}$ bestimmen

  $$
  \begin{align*}
   S_{yt} &= t(x_0) - m_t * x_0 \\
  &= \frac{8}{3}-(-\frac{8}{3})*(-1)
  &=0
  \end{align*}
  $$

5. Gleichung aufstellen

$$
t(x) = -\frac{8}{3}x 
$$

### Wende Normale

grundform 

$$
n(x) = m_n*x*S_{Yn}\\
t(x) \perp n(x)
$$

1. $m_n$ Bestimmen

$$
\begin{align*}
  m_n*m_t&=-1 \\
  m_n&=-\frac{1}{m_t} \\
  m_n&=-\frac{1}{-\frac{3}{8}}\\
  &=\frac{3}{8}
\end{align*}
$$

2. $n(x_0)$ Bestimmen

$$
\begin{align*} 
  \widehat{=}& \text{Y-wert des WeP} \\
  n(x_0) =& f(x_0) = f(-1)=\frac{8}{3}
\end{align*}
$$

3. $S_{Yn}$ Bestimmen

$$
\begin{align*}
  S_{Yn} &=n(x_0)-m_n*Y_0 \\
  &=\frac{8}{3}- \frac{3}{8}*(-1)\\
  &=\frac{73}{24} \approx 3,04
\end{align*}
$$

4. Wendenormale Aufstellen

$$
n(x)=\frac{3}{8}x+\frac{73}{24}
$$

# Tests

$$
\frac{x^3-20x^2+4}{30x^2+60x}
$$


```gnuplot {cmd=true output="html"}
set terminal svg
set title "Simple Plots" font ",20"
set key left box
set samples 500
set grid nopolar
set grid xtics ytics 
set grid front   lt 0 linecolor 0 linewidth 0.500,  lt 0 linecolor 0 linewidth 0.500
set style data points
f(x) =(x**(3)-20*x**(2)+4)/(30*x**(2)+60*x) #x**3-20*x
plot [-4:4][-5:5]  f(x)

```

<svg  width="600" height="480" viewBox="0 0 600 480" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><title>Gnuplot</title><desc>Produced by GNUPLOT 5.4 patchlevel 2 </desc><g id="gnuplot_canvas"><rect x="0" y="0" width="600" height="480" fill="none"/><defs>	<circle id='gpDot' r='0.5' stroke-width='0.5' stroke='currentColor'/>	<path id='gpPt0' stroke-width='0.222' stroke='currentColor' d='M-1,0 h2 M0,-1 v2'/>	<path id='gpPt1' stroke-width='0.222' stroke='currentColor' d='M-1,-1 L1,1 M1,-1 L-1,1'/>	<path id='gpPt2' stroke-width='0.222' stroke='currentColor' d='M-1,0 L1,0 M0,-1 L0,1 M-1,-1 L1,1 M-1,1 L1,-1'/>	<rect id='gpPt3' stroke-width='0.222' stroke='currentColor' x='-1' y='-1' width='2' height='2'/>	<rect id='gpPt4' stroke-width='0.222' stroke='currentColor' fill='currentColor' x='-1' y='-1' width='2' height='2'/>	<circle id='gpPt5' stroke-width='0.222' stroke='currentColor' cx='0' cy='0' r='1'/>	<use xlink:href='#gpPt5' id='gpPt6' fill='currentColor' stroke='none'/>	<path id='gpPt7' stroke-width='0.222' stroke='currentColor' d='M0,-1.33 L-1.33,0.67 L1.33,0.67 z'/>	<use xlink:href='#gpPt7' id='gpPt8' fill='currentColor' stroke='none'/>	<use xlink:href='#gpPt7' id='gpPt9' stroke='currentColor' transform='rotate(180)'/>	<use xlink:href='#gpPt9' id='gpPt10' fill='currentColor' stroke='none'/>	<use xlink:href='#gpPt3' id='gpPt11' stroke='currentColor' transform='rotate(45)'/>	<use xlink:href='#gpPt11' id='gpPt12' fill='currentColor' stroke='none'/>	<path id='gpPt13' stroke-width='0.222' stroke='currentColor' d='M0,1.330 L1.265,0.411 L0.782,-1.067 L-0.782,-1.076 L-1.265,0.411 z'/>	<use xlink:href='#gpPt13' id='gpPt14' fill='currentColor' stroke='none'/>	<filter id='textbox' filterUnits='objectBoundingBox' x='0' y='0' height='1' width='1'>	  <feFlood flood-color='white' flood-opacity='1' result='bgnd'/>	  <feComposite in='SourceGraphic' in2='bgnd' operator='atop'/>	</filter>	<filter id='greybox' filterUnits='objectBoundingBox' x='0' y='0' height='1' width='1'>	  <feFlood flood-color='lightgrey' flood-opacity='1' result='grey'/>	  <feComposite in='SourceGraphic' in2='grey' operator='atop'/>	</filter></defs><g fill="none" color="white" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,66.01 L37.75,444.00 L574.82,444.00 L574.82,66.01 L37.75,66.01 Z  '/></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M46.14,93.01 L46.14,75.01 L139.04,75.01 L139.04,93.01 L46.14,93.01 Z  '/></g>	<g id="gnuplot_plot_1" ><title>f(x)</title><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(79.70,87.91)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text>f(x)</text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='rgb(148,   0, 211)'  d='M88.09,84.01 L130.65,84.01 M37.75,314.85 L38.83,315.05 L39.90,315.25 L40.98,315.45 L42.06,315.66 L43.13,315.87		L44.21,316.08 L45.28,316.30 L46.36,316.53 L47.44,316.75 L48.51,316.98 L49.59,317.22 L50.67,317.46 L51.74,317.70		L52.82,317.95 L53.89,318.21 L54.97,318.47 L56.05,318.73 L57.12,319.00 L58.20,319.28 L59.28,319.56 L60.35,319.84		L61.43,320.14 L62.50,320.43 L63.58,320.74 L64.66,321.05 L65.73,321.37 L66.81,321.69 L67.89,322.02 L68.96,322.36		L70.04,322.71 L71.12,323.07 L72.19,323.43 L73.27,323.80 L74.34,324.18 L75.42,324.57 L76.50,324.97 L77.57,325.37		L78.65,325.79 L79.73,326.22 L80.80,326.65 L81.88,327.10 L82.95,327.56 L84.03,328.03 L85.11,328.52 L86.18,329.01		L87.26,329.52 L88.34,330.04 L89.41,330.58 L90.49,331.13 L91.56,331.70 L92.64,332.28 L93.72,332.88 L94.79,333.50		L95.87,334.13 L96.95,334.78 L98.02,335.46 L99.10,336.15 L100.17,336.86 L101.25,337.60 L102.33,338.36 L103.40,339.14		L104.48,339.95 L105.56,340.79 L106.63,341.65 L107.71,342.55 L108.79,343.47 L109.86,344.43 L110.94,345.42 L112.01,346.45		L113.09,347.51 L114.17,348.62 L115.24,349.77 L116.32,350.96 L117.40,352.21 L118.47,353.50 L119.55,354.84 L120.62,356.25		L121.70,357.71 L122.78,359.24 L123.85,360.84 L124.93,362.51 L126.01,364.26 L127.08,366.09 L128.16,368.02 L129.23,370.04		L130.31,372.17 L131.39,374.41 L132.46,376.78 L133.54,379.28 L134.62,381.92 L135.69,384.72 L136.77,387.69 L137.85,390.85		L138.92,394.22 L140.00,397.81 L141.07,401.66 L142.15,405.78 L143.23,410.22 L144.30,415.00 L145.38,420.16 L146.46,425.76		L147.53,431.86 L148.61,438.52 L149.41,444.00 M188.15,66.01 L188.43,69.93 L189.51,83.24 L190.58,95.01 L191.66,105.49		L192.74,114.88 L193.81,123.34 L194.89,131.00 L195.97,137.98 L197.04,144.35 L198.12,150.20 L199.19,155.59 L200.27,160.57		L201.35,165.18 L202.42,169.46 L203.50,173.45 L204.58,177.18 L205.65,180.67 L206.73,183.94 L207.80,187.02 L208.88,189.92		L209.96,192.65 L211.03,195.23 L212.11,197.68 L213.19,199.99 L214.26,202.19 L215.34,204.28 L216.41,206.27 L217.49,208.17		L218.57,209.98 L219.64,211.71 L220.72,213.36 L221.80,214.94 L222.87,216.46 L223.95,217.91 L225.02,219.31 L226.10,220.65		L227.18,221.94 L228.25,223.18 L229.33,224.38 L230.41,225.53 L231.48,226.65 L232.56,227.72 L233.64,228.76 L234.71,229.77		L235.79,230.74 L236.86,231.68 L237.94,232.59 L239.02,233.48 L240.09,234.34 L241.17,235.17 L242.25,235.98 L243.32,236.77		L244.40,237.54 L245.47,238.28 L246.55,239.01 L247.63,239.72 L248.70,240.42 L249.78,241.09 L250.86,241.75 L251.93,242.40		L253.01,243.04 L254.08,243.66 L255.16,244.26 L256.24,244.86 L257.31,245.45 L258.39,246.02 L259.47,246.59 L260.54,247.15		L261.62,247.70 L262.70,248.24 L263.77,248.78 L264.85,249.31 L265.92,249.84 L267.00,250.37 L268.08,250.89 L269.15,251.40		L270.23,251.92 L271.31,252.44 L272.38,252.95 L273.46,253.47 L274.53,253.99 L275.61,254.52 L276.69,255.05 L277.76,255.60		L278.84,256.15 L279.92,256.71 L280.99,257.29 L282.07,257.88 L283.14,258.50 L284.22,259.14 L285.30,259.82 L286.37,260.53		L287.45,261.28 L288.53,262.09 L289.60,262.96 L290.68,263.92 L291.76,264.97 L292.83,266.15 L293.91,267.48 L294.98,269.01		L296.06,270.82 L297.14,272.99 L298.21,275.68 L299.29,279.12 L300.37,283.73 L301.44,290.29 L302.52,300.48 L303.59,318.65		L304.67,360.76 L305.09,444.00 M307.45,66.01 L307.90,151.76 L308.98,193.86 L310.05,212.01 L311.13,222.17 L312.20,228.69		L313.28,233.26 L314.36,236.66 L315.43,239.29 L316.51,241.40 L317.59,243.14 L318.66,244.60 L319.74,245.85 L320.81,246.93		L321.89,247.89 L322.97,248.74 L324.04,249.50 L325.12,250.18 L326.20,250.81 L327.27,251.39 L328.35,251.92 L329.43,252.41		L330.50,252.87 L331.58,253.30 L332.65,253.70 L333.73,254.08 L334.81,254.43 L335.88,254.77 L336.96,255.09 L338.04,255.40		L339.11,255.69 L340.19,255.97 L341.26,256.24 L342.34,256.50 L343.42,256.74 L344.49,256.98 L345.57,257.21 L346.65,257.43		L347.72,257.64 L348.80,257.85 L349.87,258.05 L350.95,258.24 L352.03,258.43 L353.10,258.61 L354.18,258.79 L355.26,258.96		L356.33,259.13 L357.41,259.29 L358.49,259.45 L359.56,259.61 L360.64,259.76 L361.71,259.90 L362.79,260.05 L363.87,260.19		L364.94,260.32 L366.02,260.46 L367.10,260.59 L368.17,260.72 L369.25,260.84 L370.32,260.97 L371.40,261.09 L372.48,261.20		L373.55,261.32 L374.63,261.43 L375.71,261.54 L376.78,261.65 L377.86,261.76 L378.93,261.86 L380.01,261.97 L381.09,262.07		L382.16,262.17 L383.24,262.26 L384.32,262.36 L385.39,262.45 L386.47,262.54 L387.55,262.63 L388.62,262.72 L389.70,262.81		L390.77,262.90 L391.85,262.98 L392.93,263.06 L394.00,263.15 L395.08,263.23 L396.16,263.31 L397.23,263.38 L398.31,263.46		L399.38,263.53 L400.46,263.61 L401.54,263.68 L402.61,263.75 L403.69,263.82 L404.77,263.89 L405.84,263.96 L406.92,264.03		L407.99,264.10 L409.07,264.16 L410.15,264.23 L411.22,264.29 L412.30,264.35 L413.38,264.42 L414.45,264.48 L415.53,264.54		L416.60,264.60 L417.68,264.65 L418.76,264.71 L419.83,264.77 L420.91,264.82 L421.99,264.88 L423.06,264.93 L424.14,264.99		L425.22,265.04 L426.29,265.09 L427.37,265.14 L428.44,265.19 L429.52,265.24 L430.60,265.29 L431.67,265.34 L432.75,265.39		L433.83,265.43 L434.90,265.48 L435.98,265.53 L437.05,265.57 L438.13,265.62 L439.21,265.66 L440.28,265.70 L441.36,265.75		L442.44,265.79 L443.51,265.83 L444.59,265.87 L445.66,265.91 L446.74,265.95 L447.82,265.99 L448.89,266.03 L449.97,266.07		L451.05,266.11 L452.12,266.14 L453.20,266.18 L454.28,266.22 L455.35,266.25 L456.43,266.29 L457.50,266.32 L458.58,266.36		L459.66,266.39 L460.73,266.43 L461.81,266.46 L462.89,266.49 L463.96,266.52 L465.04,266.56 L466.11,266.59 L467.19,266.62		L468.27,266.65 L469.34,266.68 L470.42,266.71 L471.50,266.74 L472.57,266.77 L473.65,266.79 L474.72,266.82 L475.80,266.85		L476.88,266.88 L477.95,266.90 L479.03,266.93 L480.11,266.96 L481.18,266.98 L482.26,267.01 L483.34,267.03 L484.41,267.06		L485.49,267.08 L486.56,267.11 L487.64,267.13 L488.72,267.16 L489.79,267.18 L490.87,267.20 L491.95,267.22 L493.02,267.25		L494.10,267.27 L495.17,267.29 L496.25,267.31 L497.33,267.33 L498.40,267.35 L499.48,267.37 L500.56,267.39 L501.63,267.41		L502.71,267.43 L503.78,267.45 L504.86,267.47 L505.94,267.49 L507.01,267.51 L508.09,267.53 L509.17,267.55 L510.24,267.56		L511.32,267.58 L512.40,267.60 L513.47,267.61 L514.55,267.63 L515.62,267.65 L516.70,267.66 L517.78,267.68 L518.85,267.70		L519.93,267.71 L521.01,267.73 L522.08,267.74 L523.16,267.76 L524.23,267.77 L525.31,267.79 L526.39,267.80 L527.46,267.81		L528.54,267.83 L529.62,267.84 L530.69,267.85 L531.77,267.87 L532.84,267.88 L533.92,267.89 L535.00,267.90 L536.07,267.92		L537.15,267.93 L538.23,267.94 L539.30,267.95 L540.38,267.96 L541.45,267.97 L542.53,267.99 L543.61,268.00 L544.68,268.01		L545.76,268.02 L546.84,268.03 L547.91,268.04 L548.99,268.05 L550.07,268.06 L551.14,268.07 L552.22,268.08 L553.29,268.09		L554.37,268.09 L555.45,268.10 L556.52,268.11 L557.60,268.12 L558.68,268.13 L559.75,268.14 L560.83,268.15 L561.90,268.15		L562.98,268.16 L564.06,268.17 L565.13,268.18 L566.21,268.18 L567.29,268.19 L568.36,268.20 L569.44,268.20 L570.51,268.21		L571.59,268.22 L572.67,268.22 L573.74,268.23 L574.82,268.23  '/></g>	</g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,406.20 L574.82,406.20  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,406.20 L46.75,406.20 M574.82,406.20 L565.82,406.20  '/>	<g transform="translate(29.36,410.10)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,330.60 L574.82,330.60  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,330.60 L46.75,330.60 M574.82,330.60 L565.82,330.60  '/>	<g transform="translate(29.36,334.50)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" >-2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,255.00 L574.82,255.00  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,255.00 L46.75,255.00 M574.82,255.00 L565.82,255.00  '/>	<g transform="translate(29.36,258.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 0</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,179.41 L574.82,179.41  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,179.41 L46.75,179.41 M574.82,179.41 L565.82,179.41  '/>	<g transform="translate(29.36,183.31)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,103.81 L574.82,103.81  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,103.81 L46.75,103.81 M574.82,103.81 L565.82,103.81  '/>	<g transform="translate(29.36,107.71)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="end">		<text><tspan font-family="Arial" > 4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M37.75,444.00 L37.75,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,444.00 L37.75,435.00 M37.75,66.01 L37.75,75.01  '/>	<g transform="translate(37.75,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M104.88,444.00 L104.88,93.01 M104.88,75.01 L104.88,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M104.88,444.00 L104.88,435.00 M104.88,66.01 L104.88,75.01  '/>	<g transform="translate(104.88,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M172.02,444.00 L172.02,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M172.02,444.00 L172.02,435.00 M172.02,66.01 L172.02,75.01  '/>	<g transform="translate(172.02,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M239.15,444.00 L239.15,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M239.15,444.00 L239.15,435.00 M239.15,66.01 L239.15,75.01  '/>	<g transform="translate(239.15,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" >-1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M306.29,444.00 L306.29,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M306.29,444.00 L306.29,435.00 M306.29,66.01 L306.29,75.01  '/>	<g transform="translate(306.29,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 0</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M373.42,444.00 L373.42,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M373.42,444.00 L373.42,435.00 M373.42,66.01 L373.42,75.01  '/>	<g transform="translate(373.42,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 1</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M440.55,444.00 L440.55,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M440.55,444.00 L440.55,435.00 M440.55,66.01 L440.55,75.01  '/>	<g transform="translate(440.55,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 2</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M507.69,444.00 L507.69,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M507.69,444.00 L507.69,435.00 M507.69,66.01 L507.69,75.01  '/>	<g transform="translate(507.69,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 3</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="gray" stroke="currentColor" stroke-width="0.50" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='gray' stroke-dasharray='2,4' class="gridline"  d='M574.82,444.00 L574.82,66.01  '/></g><g fill="none" color="gray" stroke="gray" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M574.82,444.00 L574.82,435.00 M574.82,66.01 L574.82,75.01  '/>	<g transform="translate(574.82,465.90)" stroke="none" fill="black" font-family="Arial" font-size="12.00"  text-anchor="middle">		<text><tspan font-family="Arial" > 4</tspan></text>	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="2.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="2.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="black" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<path stroke='black'  d='M37.75,66.01 L37.75,444.00 L574.82,444.00 L574.82,66.01 L37.75,66.01 Z  '/></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter">	<g transform="translate(306.28,33.51)" stroke="none" fill="black" font-family="Arial" font-size="20.00"  text-anchor="middle"> 	</g></g><g fill="none" color="black" stroke="currentColor" stroke-width="1.00" stroke-linecap="butt" stroke-linejoin="miter"></g></g></svg>
