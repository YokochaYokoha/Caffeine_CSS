# CoffeeUI_CSS [Experimental]  
![見た目大体こんな感じっていう画像](./hanrei.png)
どなたでも気軽に利用(流用)できる横茶横葉のサイトのスタイルシートです!  
Coffeeブラウザー(アプリメイン画面)で制作したUIをCSSで再現し、それをさらに改良しました。ここにあるのは作った後、使いやすい形に整えたものです!  
色分けが簡単に行えるためサイトに彩りを添えることができます。  
実装するのにさほど時間がかからず楽してサイトを綺麗に整頓できる(多分)のがいい点です!  
(このリポジトリは予告なしに消滅することがありますので、使用時は直リンクを避け、ご自身のサーバーへアップロードすることをお勧めします。)  
Coffeeブラウザー(アプリ)のUI(ユーザーインターフェース)を参考に制作したCSSなので、CoffeeUI_CSSです(割とそのまんま)。  

このスタイルシートにはほとんど制約がなく、自由度の高い横茶横葉Aライセンスが適用されます。  
https://yokochayokoha.github.io/alicense  
実装方法から活用例、チートシートまで下にいろいろ書いておきましたのでご自由にご活用ください!  

## 使い方　　
最初のタイトル表示は以下のように設定します(もちろんコピペしてOK!)  
```html:title.html
        <div class="A">
            <div class="title">
                 <img src="trademark.png" width="15%" height="15%"><!--ここのimg srcは変えてくださいね!-->
                 <h1>横茶横葉のサイト(ここはご自身のサイト名に!)</h1> 
            </div>
       </div>
```
その下からは、div class=B~Hまで用意しています。(Rev.1時点で)  
以下のように  
```html:contents.html
        <div class="C"> <!--この部分の"C"をB~Hまで指定することで色を変えることができます。-->
<h3>お知らせ</h3>
<p>サイト管理者からのお知らせがここに表示されます。</p><!--使用例です-->
<p>現在、お知らせがありません。</p>
</div>
```
すれば、CSSが適用できます。  
実装例  
![上の2つを使った例](./rei.png)  
横茶横葉のサイトでは一部改変されていますが、フルに使っています。  
活用例1:https://yokochayokoha.github.io  
あんずはあんずが食べたい! ページでは画像やテキストなどを挟みながら使用しています。  
活用例2:https://yokochayokoha.github.io/anzu  
上記サイトは全部htmlに埋め込んで使用していますが、チートシート(早見表のことです。下記記載)を使えば、簡単に実装できます。
## チートシート  
楽がしたい方のためにチートシートをご用意しました。コピペして御利用下さい!(一部未検証。間違いあるかも..)  

### 1.CSS適用(ご自身のサーバーにアップしてから貼り付けます。ルートディレクトリに配置!)  
Rev.1版  
```
<link href="coffeeui.css" rel="stylesheet"/>
```

### 2.タイトル表示  
```
<div class="A">  
<div class="title">  
<img src="" width="15%" height="15%">  
<h1></h1>   
 </div>  
 </div>  
```
### 3.B~Hまでのdiv  
```
<div class="B">  
</div> 

<br>

<div class="C">  
</div>  

<br>

<div class="D">  
</div>  

<br>

<div class="E">  
</div>  

<br>

<div class="F">  
</div>  

<br>

<div class="G">  
</div>  

<br>

<div class="H">  
</div>
```
#### おまけ (これ、smallタグでOKなのでどこかに書いてくれると、誰か(CSSで楽したい方)の助けになるかもしれないのでとっても嬉しいです! もちろん、書かなくても"全然OK"です! あ、「全然」の誤用法、誰かに直されそう....)  
```
<p><small>このページでは<a href="https://github.com/YokochaYokoha/CoffeeUI_CSS">CoffeeUI_CSS</a>を使用しています。</small></p>  
```  

### 今後の展望ともう一つ  
このCSSは個人的に楽するために作ったものですが、気が向いたら改善版や拡張版(色を増やす 等)、div大幅追加版(サブタイトル対応とか)をつくろうかなぁ って考えています!  
あと、HTMLも枠組み書くのが面倒だったので軽いフレームワーク的なものをあげておきました。併せてご利用くださいね!  
https://github.com/YokochaYokoha/blank_HTML_Template  
徹底的に時短と楽がしたい! Time is like a precious thing, maybe!  
