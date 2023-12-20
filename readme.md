<h1>概要</h1>
偽装ページが電卓のやつです。<br>
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。<br>
画像は使えません。<br>
cookieにyuki=Trueを設定すると認証されます。<br>
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。<br>
<br>
<h1>Renderを使用する場合の手順</h1>
1~4の作業をやらないと、自動でURLがyuki-calculator-[4桁の英数字].onrender.comになります。<br>
<ol>
<li>githubアカウントを作成する</li>
<li>リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)</li>
<li>import codeを押して https://github.com/Suzuka8993/Yuki-YouTube-slim-calculator と入力</li>
<li>render.yamlを開いて編集(鉛筆のマーク)を押し、nameの横のyuki-calculatorをサイトのurlの最初の部分にしたい文字列に変更する。(yuki-1だったらurlはhttps://yuki-2.onrender.comになる)</li>
<li>Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapply(事前にrenderのアカウントを作っておく)</li>
</ol>
  <a href="https://render.com/deploy?repo=https://github.com/Suzuka8993/Yuki-YouTube-slim-calculator"><img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render"></a><br>
