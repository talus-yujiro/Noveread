# Noveread

## 言語

[English](/README.md)

[Japanese](/README/README-ja.md)

## 概要

web小説サービスから小説をダウンロードして、リーダを使い読むことができます。

web上で読むこともできます。

ブックマークに登録すればいつでもアクセスできます。

それでは、楽しいweb小説ライフを👋

## How to use

[Release](https://github.com/talus-yujiro/Noveread/releases)から最新版の実行ファイルをダウンロードしてください。
|  OS   | ディストリビューション | ファイル名     |
| ---   | ---                    | ---            |
| Linux | Debian, Ubuntu         | Noveread-*.deb |
| Linux | その他のディストリビューション | Noveread-*.AppImage
| Windows | Windows 11以下       | Noveread.setup.*.exe |

または、ソースコードをダウンロードし、解凍したルートフォルダで

```bash
npm run dist
```

を実行してください。(Node.jsをインストールの上)

distフォルダの中に実行ファイルができるはずです。

## ロードマップ
- [x] v1.0.0 とりあえず起動できる
- [ ]
- [ ] v1.8.0 アプリとして使用できるようにする

## 最近の変更
### 2025/07/01
- `package.json`の変更
    - `.deb`ファイルでリリースを作れるように
### 2025/06/27
- v1.0.0公開
    - とりあえず起動できるように
    - 試験的に`webview`を導入