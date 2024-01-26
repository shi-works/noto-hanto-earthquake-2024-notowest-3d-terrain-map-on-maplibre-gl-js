# 能登西部3D地形マップ（赤色立体地図）
能登西部の赤色立体地図（0.5m）と産総研のシームレス標高タイルをもとに、MapLibre GL JSで能登西部3D地形マップを表示するデモサイトです。

## Public Website
https://shi-works.github.io/noto-hanto-earthquake-2024-notowest-3d-terrain-map-on-maplibre-gl-js/

## Data Source
### 石川県
- 令和6年能登半島地震 能登東部・赤色立体地図（発災前）
    - 出典：https://xs489works.xsrv.jp/raster-tiles/pref-ishikawa/notowest-red-tiles/{z}/{x}/{y}.png
      - 原初データ出典：https://www.geospatial.jp/ckan/dataset/2024-notowest-mtopo
        - 概要：赤色立体地図はアジア航測株式会社の特許（第3670274号等）を使用して作成したものです。[アジア航測株式会社の許諾条件](https://www.rrim.jp/researcher/)を確認してください。
        - ライセンス：申請不要で利用できますが、商用利用することはできません。[利用規約](https://www.geospatial.jp/ckan/dataset/2024-notowest-mtopo/resource/e4b926f4-3e94-48b2-afb0-92e94830516e)参照。
        - 備考：この成果品は、石川県が作成した測量成果を、石川県知事の承認を得て複製したものである。承認番号 森管第１９７７号（令和５年度）
    - 概要：G空間情報センターにて公開されている、石川県提供の[令和6年能登半島地震 能登西部微地形表現図データ（発災前）](https://www.geospatial.jp/ckan/dataset/2024-notowest-mtopo)をラスタータイル化したデータです。
    - ズームレベル：10～18
    - タイルサイズ：256x256ピクセル
    - ライセンス：原初データのライセンスに従います。

### 産業技術総合研究所
- シームレス標高タイル（統合DEM）
    - 出典：https://tiles.gsj.jp/tiles/elev/tiles.html
    - ライセンス：「[産総研地質調査総合センターウェブサイト利用規約](https://www.gsj.jp/license/license.html)」に従い、商用を含む自由な二次利用が可能です。この規約はCC BY 4.0と互換です。
