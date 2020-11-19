# for_seminar



## README.md

これがREADME.mdファイルです．

- .mdファイルはマークダウン形式のファイル
- どちらかというとLaTeXやHTMLのファイルのような系統の種類
  - ルールに従ってどのような表示・レイアウトにするかを記す種類
- githubでは成型して表示してくれる

上のファイル一覧からREADME.mdファイルを選択し，表示エリア右上の"**Raw**"ボタンからファイルの中身そのまま(生ファイル)が見れます．


## markdown形式

### Reference Site Links
[マークダウン記法の書き方(簡易) withプレビュー](https://web-cheatsheet.com/markdown)  
[Qiita マークダウン記法 一覧表・チートシート](https://qiita.com/kamorits/items/6f342da395ad57468ae3)  
[ローカル.mdファイルの表示方法](https://qiita.com/zoekaeru/items/084948b5c6479af1158e)  
[GitHub Flavored Markdown(GFM)](https://qiita.com/tbpgr/items/989c6badefff69377da7#github-flavored-markdowngfm)  


### Space
|表記|実際の幅||
|:---:|:---|:---|
|`&thinsp;`|"&thinsp;"|通常の半角スペースより狭い空白
|`&nbsp;`|"&nbsp;"|半角スペースと同じサイズの空白|
|`&ensp;`|"&ensp;"|半角スペースより少し広めの空白|
|`&emsp;`|"&emsp;"|半角スペースより更に広めの空白<br>≒ 全角スペースとほぼ同じ幅|

[マークダウンのお供html(空白，そのまま表示，改行)](https://hacknote.jp/archives/45735/)  

### Table

|左寄せ|中寄せ|右寄せ|
|:---|:---:|---:|
|:---|:---:|---:|

<!-- [細かい設定](https://seesaawiki.jp/w/tag_guide/d/%A5%C6%A1%BC%A5%D6%A5%EB%28%C9%BD%C1%C8%A4%DF%29%B5%AD%CB%A1) -->

### Anchor
[`[アンカーに飛ぶ](#Anchor)`](#Anchor)  
<a id="Anchor">`<a id="Anchor"> アンカー(ページ内リンク,ジャンプポイント)を作る </a>`</a>  

`<a name="hoge"></a>`は非推奨(HTML5)  
[idの命名の仕方の注意(文字種など)](https://www.kanzaki.com/docs/html/htminfo12.html#name-syntax)

[`[ページ内の見出しに飛ぶ](./<page-name>#<見出し>)でもいける`](README.md#Anchor)


## 特殊文字
html上では，&amp;などの特殊文字は直接使わず，**参照文字**で表記するのが望ましい．  
htmlの話題では，これがエスケープ処理と呼ばれてるらしい．

|表記|記号|
|:---:|:---:|
|`&amp;`|&amp;
|`&quot;`|&quot;
|`&lt;`|&lt;|
|`&gt;`|&gt;|
|`&#059;`|&#059;
|`&larr;`|&larr;|
|`&uarr;`|&uarr;|
|`&rarr;`|&rarr;|
|`&darr;`|&darr;|
|`&harr;`|&harr;|

[その他](http://web-dou.com/html/t023b.html)


## 上付き文字，下付き文字
マークダウンでは無理．(ものによってはT<sub>E</sub>X形式をサポートしてくれてるところもあるらしいけど)

|表記|表示|
|:---:|:---:|
|`上付き<sup>文字</sup>`|上付き<sup>文字</sup>|
|`下付き<sub>文字</sub>`|下付き<sub>文字</sub>|
