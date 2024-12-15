Iki dipersembahake kanggo repositori pangembangan Kalender Jawa digital.

[Pustaka Kalender Jawa](https://github.com/kalenderjawa/pustaka)

**Pustaka** iku perpustakaan JavaScript kanggo Kalender Jawa.

> Kalender Jawa iku sistem kalender adhedhasar bulan. Wong Jawa nggunakake iki kanggo akeh tujuan ing urip saben dina nganti saiki wiwit abad kaping 14.

**Rumus Matematika Kalender Jawa**

Kalender Jawa adhedhasar matematika lan dilestarikake saka generasi menyang generasi liwat rumus matematika. Ironis, ora akeh generasi anyar sing ngerti utawa sadhar babagan ilmu iki.

![Rumus Matematika Kalender Jawa](https://assets.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)
[(*sumber gambar*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

## **API**

API iki gampang digunakake umpamane yen sampeyan pengin ngerti rumus matematika sasi `romadon` ing taun Jawa 1952,

```javascript
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {
  console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)
  // romadon_7_4 (don tu pat)
})
