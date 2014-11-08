www.vyos-users.jp ソースリポジトリ
=======================

* [www.vyos-users.jp](http://vyos-users.jp/)のソースおよび設定用リポジトリです。
* [Pelican](http://docs.getpelican.com/)を利用しています。
* 公開リポジトリ [vyos-users-jp / vyos-users-jp.github.io](https://github.com/vyos-users-jp/vyos-users-jp.github.io)

編集方法
---------------------------------

* 必要な物
    * Python 2.7.x
        * pelican
        * Markdown
	* fablic

1. ソースコードを取得 `$ git clone --recursive https://github.com/vyos-users-jp/vyos-users-jp.github.io-source.git`
2. ディレクトリに移動 `$ cd vyos-users-jp.github.io-source`
3. ページを修正 `$ vi content/pages/index.md` (トップページを修正する場合)
4. 確認 `$ fab serve`
5. 公開 `$ fab deploy`
6. ソースリポジトリコミット&プッシュ `$ git commit -am "index.md追記" && git push`

ライセンス
---------------------------------

<p>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a> Content licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution 4.0 International License</a>, except where indicated otherwise.
</p>
