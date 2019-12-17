# Masoniteを使ってみる
laravelインスパイアのPythonフレームワーク。  
とりあえずPHP使ってて辛かったのでこっちでやってみる。

## とりあえずプロジェクト作るまで
[公式](https://docs.masoniteproject.com/)  
- 公式の方のやり方でやればできた。
- c言語のコンパイラ無いとpsutils落とすときにエラー出るかも(gcc系落としたらいけた)

[これでよげ](https://qiita.com/dumblepy/items/65b975302618cb6a8f64)  

Pycharm使ったらvenvはできてるので以下
```
pip install pipenv

pipenv install masonite-cli

```


### Masonite触る
craftコマンドを使う

```
# プロジェクトの作成
craft new [projectName] craft new blog

cd blog

# Masoniteが使うパッケージ類のインストール
craft install
```

### ひとまずチュートリアルこなす(レンサバ借りてあげるとこまでやりたい)
- フロント: Vue
- バック: Masonite-Api

