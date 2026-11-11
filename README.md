# 推しプレゼン（令和8年度 文章表現）

3年生が1年生に向けて、自分の「推し」を5分で語る発表の準備ワークです。

- 公開ページ：https://yama0113sg.github.io/R8bunsho-Hyogen_oshipre/
- 発表：令和8年12月11日（金）5・6時間目

## AIについて

AIの問い返しは、起承転結のリポジトリ（R8bunsho-Hyogen_kishou）にある中継 Worker「kishou」の `mode:"oshi_ask"` を使っています。
AIの問いかけ方（プロンプト）を変えるときは、そちらの `worker/worker_kishou.js` を直します（main に入ると Cloudflare で自動デプロイ）。

## 保存について

生徒の入力は、その端末のブラウザ（localStorage「oshipre_work1」）にだけ保存されます。
yama0113sg.github.io の中ならリポジトリが変わっても同じ保存場所なので、起承転結側の旧URLで書いた内容も引き継がれます。
