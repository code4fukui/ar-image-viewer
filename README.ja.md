# AR Image Viewer

3D空間に2D画像を表示するシンプルなARビューアー。

## デモ
https://code4fukui.github.io/ar-image-viewer/

## 機能
- 2D画像を3D空間に表示
- 画像のサイズ、位置、向きをカスタマイズ可能
- VR（仮想現実）体験を構築するためのWebフレームワーク、A-Frameを利用

## 使い方
AR画像ビューアーは、URLに以下のパラメータを指定することでカスタマイズできます。

- `src`: 表示する画像のURL
- `w`: 画像の幅（メートル単位）
- `h`: 画像の高さ（メートル単位）
- `x`: 中心位置のX座標（メートル単位）
- `y`: 中心位置のY座標（メートル単位）
- `z`: 中心位置のZ座標（メートル単位）

たとえば、幅5.4メートル、高さ1.4メートルで、位置(0, 1.5, -1.8)に画像を表示する場合、URLは以下のようになります。

```
https://code4fukui.github.io/ar-image-viewer/?src=./img/sabae-candidates-2023.jpg&w=5.4&h=1.4&x=0&y=1.5&z=-1.8
```

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
