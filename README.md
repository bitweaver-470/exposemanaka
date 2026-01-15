# SecretFlasherManaka Mosaic Remover

Unity (IL2CPP) ゲーム「Secret Flasher Manaka」用のモザイク除去プラグインです。
BepInEx 6 (IL2CPP) を使用しています。

## 動作環境

- **OS:** Windows 10 / 11 (64bit)
- **Game Version:** v1.1.3 (動作確認済み)
- **BepInEx:** 6.0.0-be (IL2CPP)

⚠️ **注意:** Mac/Linux での動作は確認しておらず、サポート対象外です。

## インストール方法 (一般ユーザー向け)

1. [Releases](../../releases) ページから最新の `All-in-One.zip` をダウンロードしてください。
2. ゲームのインストールフォルダ（`SecretFlasherManaka.exe` がある場所）に、zipの中身（`BepInEx` フォルダなど）をすべて上書きコピーしてください。
3. ゲームを起動すると、自動的にモザイク除去が適用されます。

## 開発者向けビルド方法

必要なもの:
- .NET 6 SDK
- ゲーム本体（インストール済みで、一度起動して `BepInEx/interop` が生成されていること）

ビルド:
```bat
cd src
build.bat
```

## ライセンス

### MosaicRemover Plugin
MIT License

### BepInEx (Bundled)
本パッケージには、[BepInEx](https://github.com/BepInEx/BepInEx) (LGPL-2.1) が同梱されています。
BepInEx のソースコードおよびライセンス全文は、上記リンク先または同梱の `LICENSE_BepInEx.txt` をご確認ください。

ソースコードの改変は行っておらず、オリジナルのバイナリをそのまま配布しています。
