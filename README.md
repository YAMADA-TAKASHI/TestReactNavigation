# インストール

```
//--saveをつけると、package.jsonに記述が追加される
$ npm install react-navigation-stack --save
$ npm install
```

# ターミナルからエミュレータ起動(Win)
C:\Users\yamada.takashi>emulator -list-avds
Pixel_2_API_29
Pixel_API_28

C:\Users\yamada.takashi>emulator -avd Pixel_2_API_29

# エミュレーター 起動エラー(Win)

・「PANIC: Missing emulator engine program for 'x86' CPU.」

```
$ where emulator
C:(省略)\AppData\Local\Android\Sdk\emulator
C:(省略)\AppData\Local\Android\Sdk\tools
//環境変数>PATHに上記2つがあるか確認し、toolsが先に来ていたら順番を入れ替える
```

# 別の端末で作業したブランチにチェックアウトする

```
$ git fetch
$ git checkout branch_name
```