# Clock with YouTube
○時○分○秒に○○を流すと○○のときに○○ってやつ

## 動画の追加の仕方
`video-list.json`というファイルがあります。
そこにこのように書かれています。
```
[
  {
    "name": "Daisuke",
    "id": "Kwv_vPIL4IQ",
    "fit": 67,
    "start": 0,
    "end": 0
  },
  {
    ...
  }
  ...
]
```
### 各値の説明
|名前|例|説明|
----|----|----
|name|Daisuke|選ぶときに表示する名前|
|id|Kwv_vPIL4IQ|動画のID|
|fit|67|合わせる動画の時間(秒数) <br> この場合は1回目のDaisuke|
|start|0|動画を始める時間(秒数)指定しない場合は0|
|end|0|動画を終わらせる時間(秒数)指定しない場合は0|

start と end は動画が長過ぎるときに書いてください。

## ToDo
- [] スマホ対応
- [] 自分で時刻を決める
- [] 動画を先に読み込んでおく
- [] きれいなコード
