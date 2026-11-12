# セキュリティポリシー

## 脆弱性の報告

このリポジトリの設定や、それで動いている https://wema.fushihara.net に脆弱性を見つけたら、公開の Issue には書かず、GitHub の [Private vulnerability reporting](https://github.com/kan/wema-kake-site/security/advisories/new) から報告してください。報告の内容は、修正を公開するまでメンテナーにだけ見えます。

報告には次の内容を書いてください。

- 脆弱性の内容
- 再現の手順
- 想定される影響（読み書きできるデータ、必要な権限など）

受け取った報告は、できるだけ早く確認して返信します。

## 対象

対象は、このリポジトリの設定（`main` ブランチの最新）と、それで動いているインスタンス（Cloudflare Access のポリシーを含む）です。

次のものは、それぞれの報告先へお願いします。

- Wiki の処理と画面（`@kanf/wema-kake`）の問題: [kan/wema-kake](https://github.com/kan/wema-kake/security/policy)
- 付箋ボードのライブラリ wema の問題: [kan/wema](https://github.com/kan/wema/security/policy)
