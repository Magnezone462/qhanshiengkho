# 《漢字文聲義》數據庫  «Qhândziə̂myun Shieŋŋriê» Sryôkiôkhô
『漢字文声義』掲載情報のデータベースです。音義以外のデータを載せるつもりです。
## DzQ.csv：字音數據 Dziə̂qrim Sryôkiô
字音のデータです。
### `grien`
キーです。
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
キーです。
### `dziwdu`, `dziwdu_qhanshiev`
見出し字とその『漢字文声義』での表記です。
### `syenjyovdziw`
『通用規範漢字表』で整理された選用字（繁体字）です。
### `krenqhruadziw`
『通用規範漢字表』で整理された簡化字（簡体字）です。
### `nitpun_diavjyovdziw`
『常用漢字表』で整理された常用漢字字体（新字体）です。
### `jiwtheidziw`
その他の異体字です。
### `thovjyov_kyebyam_zioxau`
『通用規範漢字表』での序号です。
### `ziwvyan_jiepmra`
『辞源』第3版でのページと段です。
### `qhanziwqhwi_bushyu`, `qhandziwqhwi_bushyuvuai`
『漢辞海』第4版での収録位置の部首と部首外画数です。
### `thongqitmra`
`dziwdu`のUnicodeです。

## SKXM.csv：四角號碼數據 Sîkrok Xâumrá Sryôkiô
四角号碼データです。
### `grien`
キーです。
### `dziw`, `dziw_qhanshiev`
Unicode字種とその『漢字文声義』での表記です。
### `dziwxev`
字形です。複数の字体がUnicode字種にあり，それによって四角号碼が異なる場合に指定しています。
### `sikrok_xaumra`
四角号碼です。複数候補があるものは『辞源』第3版のものを先頭に置いています。
### `thovqitmra`
`dziw`のUnicodeです。
### `pryentyov`
字形の変種情報です。"T" は中国字形，"N"は日本字形，"J"はその他の字形です。 
### `tyoshiek`
コメントです。

## XShB.csv：諧聲部數據 Xreishieŋbú Sryôkiô
各見出し字に対する諧声部のデータです。
### `grien`
キーです。
### `dziwdu`, `dziwdu_qhanshiev`
見出し字とその『漢字文声義』での表記です。
### `xreishievbu`, `xreishievbu_qhanshiev`
諧聲部とその『漢字文声義』での声首です。
### `pyunqhrua`
分化情報です。
### `xreishievbu_pyuideiqit`
二級以降の諧聲部です。
### `shievvuai`
聲符外部品です。
### `shievvuai_pyunqhrua_xryitriw`
聲符外部品の分化位置です。
### `thonvqitmra_xreishievbu`, `thonvqitmra_dziwdu`
`xreishievbu`と`dziwdu`のUnicodeです。
