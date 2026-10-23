# reNera BOM

reNeraの組み立て、および使用に必要な部品の一覧です。

## 通常キットに同梱されている部品

| 部品         | 仕様・規格      |    数量 | 購入先                                                             | 備考            |
| ---------- | ---------- | ----: | --------------------------------------------------------------- | ------------- |
| PCB基板      |            | 左右各1枚 |                                                                 | ケースへ仮固定されています |
| M2インサートナット | M2 / 長さ3mm |    8個 | [ヒロスギネット](https://www.hirosugi-net.co.jp/shop/g/g27912/)        | ケースへ熱圧入済みです   |
| M2低頭ネジ     | M2 / 長さ3mm |    8個 | [ウィルコ（FX-0230EB）](https://wilco.jp/products/F/FX-EB.html#page3) | ケースへ仮固定されています |
| ケース        | 3Dプリンター製   |    1式 |                                                                 |               |

## ご自身で用意が必要な部品

### 組み立て時に必要な部品
| 部品             | 仕様・規格         |    数量 | 購入先                                                                                                                                                              | 備考                        |
| -------------- | ------------- | ----: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| スイッチソケット       | Kailh Choc用   |   48個 | [TALPKEYBOARD](https://shop.talpkeyboard.com/products/choc-kailh-pcbsocket-10) / [遊舎工房](https://shop.yushakobo.jp/products/a01ps?variant=37665172553889)         |                           |
| ダイオード          | 1N4148W / SMD |   48個 | [TALPKEYBOARD](https://shop.talpkeyboard.com/products/1n4148-diode-smd-100pcs) / [遊舎工房](https://shop.yushakobo.jp/products/a0800di-02-100)                       |                           |
| マイコン           | RP2040-Zero   |    2個 | [TALPKEYBOARD](https://shop.talpkeyboard.com/products/rp2040-zero-usb-c-compatible) / [遊舎工房](https://shop.yushakobo.jp/products/10947)                           | 左右各1個                     |
| ピンヘッダー / コンスルー | 高さ2.5mm       | 16ピン分 | [TALPKEYBOARD](https://shop.talpkeyboard.com/products/mac8-xb-3-2-5-20p) / [遊舎工房](https://shop.yushakobo.jp/products/31)                                         | RP2040-Zeroに付属するピンヘッダーでも可 |
| TRRSジャック       | 3.5mm 4極      |    2個 | [TALPKEYBOARD](https://shop.talpkeyboard.com/collections/trrs-parts) / [遊舎工房](https://shop.yushakobo.jp/collections/electronic-components/products/a0800tr-01-1) | 左右各1個                     |
| ゴム足            | 直径8mm         |    8個 | [Amazon](https://amzn.asia/d/07QkCnMq)                                                                                                                           | ケース底面滑り止め用                |
### 使用に必要なもの

| 部品       | 仕様・規格              |  数量 | 購入先                                                                                                     | 備考                      |
| -------- | ------------------ | --: | ------------------------------------------------------------------------------------------------------- | ----------------------- |
| キースイッチ   | Kailh Choc V2      | 48個 |                                                                                                         | お好みのChoc V2スイッチをご用意ください |
| キーキャップ   | Choc V2対応（MX互換十字軸） | 48個 | [comugi caps](https://alektor.booth.pm/items/8780480) / [3Dデータ](https://alektor.booth.pm/items/7088445) | 17mmピッチで使用可能なキーキャップを推奨  |
| USBケーブル  | USB Type-C         |  1本 |                                                                                                         | PCとの接続用                 |
| TRRSケーブル | 3.5mm 4極           |  1本 | [遊舎工房](https://shop.yushakobo.jp/collections/accessory/Cables)                                          | 左右間接続用                  |

## （参考）OLEDについて

reNeraのPCBには、OLEDディスプレイを取り付けられるスペースを用意しています。

OLEDを取り付ける場合は、基板上のシルクを参考にはんだ付けしてください。

なお、OLEDのSDA / SCLピンについてはPCB上で配線されていないため、RP2040-Zeroとの間を手配線（ハンドワイヤリング）する必要があります。

また、付属するケースデータはOLEDの取り付けを想定した形状にはなっていません。
OLEDを使用する場合は、ケースデータをご自身で加工してください。

ファームウェアについてもOLED表示には対応していないため、ご自身で修正していただく必要があります。

