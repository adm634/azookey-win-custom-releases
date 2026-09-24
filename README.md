# azooKey for Windows（配布用）

このリポジトリは Windows 用日本語 IME「azooKey for Windows」改修版のインストーラー配布用です。ソースコードのリポジトリは非公開で、ここには実行ファイルとチェックサムだけを公開します。元の Windows 版は [fkunn1326/azooKey-Windows](https://github.com/fkunn1326/azooKey-Windows) です。

## 重要なお知らせ

`v0.1.0-alpha.3` には、候補確定後に変換サーバーが停止し、設定画面が開かず、ローマ字がそのまま入力される不具合があります。現在、修正版を検証中です。修正版が公開されるまで、新規インストールや友人への配布はお控えください。

## インストール

[Releases](https://github.com/adm634/azookey-win-custom-releases/releases) から最新の `azookey-setup.exe` をダウンロードして実行してください。64ビット Windows 専用で、インストーラーには管理者権限が必要です。32ビットアプリ内でのIME動作はサポートしません。

配布版は試験段階です。入力品質や学習効果は検証中です。更新後はIMEを使用しているアプリ、必要に応じてWindowsを再起動してください。不具合や再現例はこのリポジトリの [Issues](https://github.com/adm634/azookey-win-custom-releases/issues) に報告できます。

## 更新

`v0.1.0-alpha.3` 以降の設定画面は、このリポジトリの公開リリースを確認し、新版のインストーラーをSHA-256で検証して起動します。古い版からの最初の更新は、上記のReleasesから手動で行ってください。

各リリースには `SHA256SUMS.txt` も添付します。ライセンスと第三者コンポーネントの通知はインストーラーに同梱しています。
