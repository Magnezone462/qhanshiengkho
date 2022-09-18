# 《漢字文聲義》數據庫  «Qhândziə̂myun Shieŋŋriê» Sryôkiôkhô
## DzQ.csv：字音數據 Dziə̂qrim Sryôkiô
字音のデータです。
### `grien`
キーです。`thovqitmra`-`chetxryn_ziosryo_sishiev`-`chetxryn_ziosryo_xrynmyuk`-`chetxryn_ziosryo_sieuxryn`です。
### `dziwdu`, `dziwdu_qhanshiev`
見出し字とその『漢字文声義』での表記です。
### `zyephev`
字音の隋拼表記です。
### `chetxryn_ziosryo_sishiev`, `chetxryn_ziosryo_xrynmyuk`, `chetxryn_ziosryo_sieuxryn`
『切韻』の四声、韻目、小韻の序数です。『切韻諸本輯覧』や藤田（2018）にあるものです。  
100番台は『切韻』原本にはないが『広韻』（まで）にある小韻の序数，200番台は複数候補のあるもの，500番台は『集韻』にあるもの，999番は『集韻』までのすべてにないものです。
### `diavko_xrynbu`
上古韻部です。正直よくわかりません。
### `chetxryn_dzankryen_pyunlyi`, `chetxryn_dzankryen`
`pyanchet_chetxryn`で採用している『切韻』の本とその藤田（2018）での分類です。
### `pyanchet_chetxryn`, `pyanchet_chetxryn_tyoshiek`
『切韻』の反切とその注釈です。注釈はまだできてないです。
### `pyanchet_xyavxryn`, `pyanchet_xyavxryn_tyoshiek`
『王韻』の反切とその注釈です。注釈はまだできてないです。
### `pyanchet_kuavxryn`, `pyanchet_kuavxryn_tyoshiek`
『広韻』の反切とその注釈です。注釈はまだできてないです。
### `pyanchet_dzipxryn`, `pyanchet_dzipxryn_tyoshiek`
『集韻』の反切とその注釈です。注釈はまだできてないです。
### `qhanziwqhwi_shievlyi`, `qhanziwqhwi_xrynlyi`, `qhanziwqhwi_deulyi`
『漢辞海』の声類、韻類、調類です。
### `giwtha_potyo`
その他の補注です。
### `qrimvrielan`
『漢字文声義』の音義欄です。原則として省略してありますが，`giwtha_potyo`で必要なものに限り残してあります。
### `thovqitmra`
`dziwdu`のUnicodeです。

## DzSh.csv：字書數據 Dziə̂shio Sryôkiô
字書データです。各種の異体字や『辞源』、『漢辞海』の収録情報があります。
### `grien`
### `dziwdu`
### `dziwdu_qhanshiev`
### `syenjyovdziw`
### `krenqhruadziw`
### `nitpun_diavjyovdziw`
### `jiwtheidziw`
### `thovjyov_kyebyam_zioxau`
### `dziwvyan_jiepmra`
### `qhanziwqhwi_bushyu`, `qhandziwqhwi_bushyuvuai`
### `thongqitmra`
## SKXM.csv：四角號碼數據 Sîkrok Xâumrá Sryôkiô
四角号碼データです。
### `grien`
### `dziw`, `dziw_qhanshiev`
### `dziwxev`
### `sikrok_xaumra`
### `thovqitmra`
### `pryentyov`
### `tyoshiek`
## XShB.csv：諧聲部數據 Xreishieŋbú Sryôkiô
各見出し字に対する諧声部のデータです。
### `grien`
### `dziwdu`, `dziwdu_qhanshiev`
### `xreishievbu`, `xreishievbu_qhanshiev`
### `pyunqhrua`
### `xreishievbu_pyuideiqit`
### `shievvuai`
### `shievvuai_pyunqhrua_xryitriw`
### `thonvqitmra_xreishievbu`, `thonvqitmra_dziwdu`
