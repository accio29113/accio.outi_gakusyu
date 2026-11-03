# Accio ホームページ（たたき台）

## フォルダの中身
- index.html … トップページ
- scratch.html / roblox.html / python.html / gokyoka.html … コース別ページ
- teacher.html … 講師紹介
- css/style.css … 色・デザイン（最初の :root の色を変えると全体が変わります）
- js/main.js … スマホのメニュー開閉
- images/ … ロゴ・キャラ・チラシ画像

## VS Codeで確認
1. VS Codeで accio-site フォルダを開く
2. 拡張機能「Live Server」を入れる
3. index.html を右クリック →「Open with Live Server」

## GitHubで公開（GitHub Pages）
1. GitHubで新しいリポジトリを作る（例：accio-site、Public）
2. VS Codeのターミナルで、フォルダ内にて次を実行
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/あなたのID/accio-site.git
   git push -u origin main
3. GitHubのリポジトリ → Settings → Pages → Branch を main / (root) にして Save
4. 数分後、https://あなたのID.github.io/accio-site/ で公開されます

## あとで直す所（【 】の部分）
- teacher.html … 講師のお名前・写真・経歴・資格
- index.html … ホームページ公開後のURL、特定商取引法などの表記リンク
