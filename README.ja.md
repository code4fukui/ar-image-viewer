# AR 画像ビューアー

AR 画像ビューアーは、Web 上で2D画像を3D空間に表示できるシンプルなツールです。URL から画像を指定し、サイズや位置を調整することができます。

## デモ
https://code4fukui.github.io/ar-image-viewer/

## 機能
- 画像の表示
- 画像サイズの設定
- 画像の位置の設定

## 使い方
URLパラメータで画像や設定を指定できます。

- `src`: 画像URL
- `w`: 幅(m)
- `h`: 高さ(m) 
- `x`: 設置中心点X(m)
- `y`: 設置中心点Y(m)
- `z`: 設置中心点Z(m)

例えば、幅5.4m、高さ1.4mの画像を(0, 1.5, -1.8)の位置に表示するには、以下のURLを使います。

```
https://code4fukui.github.io/ar-image-viewer/?src=./img/sabae-candidates-2023.jpg&w=5.4&h=1.4&x=0&y=1.5&z=-1.8
```

## ライセンス
このプロジェクトはMITライセンスの下で公開されています。