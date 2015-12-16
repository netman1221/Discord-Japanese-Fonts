# Discord-Japanese-Fonts
Discordの日本語フォントを見やすくするCSSです。

# 利用方法

Discordで __Ctrl + Shift + I__ を押してください。

すると、__Developer Tools__ というウィンドウが出てくるので、その中の __Elements__ というタブを開いてください。

__[ここからの作業はわかりにくいのでビデオにしました。](https://ppn.pw/i/pc/fb8dc3b7/u0rspxvd.mp4)__

__Elements__ を開いたら __<head>__ というタグ ( <head>...</head> と表記されている場合もあります) を右クリックします。

開かれた枠内の、__</head>__ の前に

```
<link rel="stylesheet" type="text/css" href="https://cdn.ppn.pw/css/discord/jp-font.css">
```

を __Ctrl + V__ で貼り付け、ウィンドウを閉じて完了です。

また、この作業はDiscordの仕様によりDiscord再起動時にリセットされてしまいますので、多少面倒ですが起動時に再度行ってください。
