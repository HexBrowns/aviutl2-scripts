# HexBrowns による追加

こんにゃくねこさんの [aviutl2-scripts](https://github.com/CatWithNeko/aviutl2-scripts) をフォークしたものです。

| ファイル | 内容 | 説明書 |
|---|---|---|
| `ロングシャドー_H.anm2` | `LongShadow.anm2` の拡張版。影の付け方と項目はそのまま、拡散・収束とエッジぼかし、グラデーションの色空間（Oklab・Oklch など）を足し、項目名を日本語にしたもの | [docs](docs/ロングシャドー_H.md) |
| `EffectUtils_ColorSpace.lua` | ロングシャドー_H がグラデーションの色空間を sRGB 以外にしたときに読む共有モジュール | — |
| `トーンカーブ_H.anm2` | `Tonecurve_C.anm2` と同じ項目・同じ使い方のまま、処理を作り直したもの | [docs](docs/トーンカーブ_H.md) |

## 導入

使用したいスクリプトを `Script` から取り出し、AviUtl2 の `Script` フォルダへコピーして、AviUtl2を起動します。
元のスクリプトとは名称が違うため競合の心配は不要です。
ロングシャドー_H を使うときは、`EffectUtils_ColorSpace.lua` も同じ `Script` フォルダの直下に置いてください。

## ライセンス

CC0-1.0

他のスクリプトは [HexBrowns/HexScript](https://github.com/HexBrowns/HexScript) にあります。
