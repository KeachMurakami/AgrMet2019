










<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

<!--html_preserve--><div style='position:absolute; left:-50%; width:200%; top:550px; height:80px; padding:10px; font-size:0.5em; text-align:center; background-color:grey; color:white'><!--/html_preserve-->

日本農業気象学会2019年 (草薙キャンパス, 静岡県立大学)<br>
This slide is available: <!--html_preserve-->@fa[github]<!--/html_preserve--> `KeachMurakami/AgrMet2019`
</div>

<br>
<br>

**成熟した葉の光合成能力は強光順化応答を示さないのか**

<br>
<br>

<div style="text-align:right">
<span style="color:orange">村上 貴一<sup>1,2</sup></span>, Wah Soon Chow<sup>1</sup><br>(<sup>1</sup>The Australian National University, <sup>2</sup>山口大学)
</div style="text-align:right">

---?color=linear-gradient(to left, #ccddee, #aabbcc)

## Introduction

+++

光合成能力 = 光・CO<sub>2</sub>飽和条件下での総光合成速度



<div class="left">
<img src="figure/light_curve-1.png" width="110%">
</div class="left">

<div class="right">
<br>
<br>
@ul
- <small>強光下では高い方が有利</small>
- <small><orange>cytochrome *b*<sub>6</sub>*f* (cyt-bf) 量</orange>と<br>正の相関 <small>(Evans 1988; Aust J Plant Physiol)</small></small>
@ulend
</div class="left">

+++

強光下で<span class="fragment highlight-blue">育てば</span>光合成能力が高くなる (**強光順化**)




<p style="text-align:center;"><img src="figure/growth_irad-1.png" height="430px"></p>

<p class = "fragment" style="text-align:center;">展開を終えた葉 = **成熟葉**ではどうか？</p>

Note:

これは太陽光下で３水準の遮光レベルを設けてホウレンソウを栽培した例です。遮光率が高い、つまり暗いと光合成能力が低くなります。
こんな風に育つ過程での光環境の影響はよく調べられているのですが、展開後の葉、成熟葉、の順化に関してはあまりよく調べられていません。

+++

葉の寿命は長い

<p style="text-align:center;"><img src="img/jurik.png" height="430px"></p>

<p class = "fragment" style="text-align:center;">成熟葉の柔軟な強光順化は<orange>生涯の‘稼ぎ’</orange>に影響大？</p>

Note:

例えばいちごでは、展開までと展開後であれば、後者の期間のほうが長い。

+++

成熟葉の順化に着目した文献

<div class="column1" style="font-size: 0.5em">
受光量の低下に応じた速やかなcyt-bf分解
<img src="img/zhu.png" height="400px">
</div class = "column1">


<div class = "column2" style="font-size: 0.5em">
cyt-bfが新たに合成されず強光順化できない
<img src="img/hojka.png" height="400px">
</div class = "column2">

<p class="fragment" style="text-align:center;"><orange>数日の曇りで光合成能力が不可逆的に低下する？</orange></p>

Note:

ここ数年の文献では、強光から弱光へ移すとcyt-bfが速やかに分解される、その半減期は２日だった、というようなものがありました。
また詳細は省きますが、成熟葉ではどうやらサイトクロムが合成されなくて、強光に順化できない、というような報告もあります。

このふたつを踏まえると、、、、ということになります。
どうでしょうかね。曇りが数日つづくことなんてざらにありますから、ちょっと信じがたいとぼくは思います。

+++

<br>
<br>
**Q. 成熟葉は強光順化しないのか？**
<br>
<br>
<br>
<div style="position:relative; left:10px">
@ul
- 予想: 成熟後、徐々に強光順化の柔軟性が失われる
- 実験: 成熟葉に対して強光 → 数日の弱光 → 再強光
- 手法: 弱光日数が回復過程に及ぼす影響をモデル化
@ulend
</div>

---?color=linear-gradient(to left, #ccddee, #aabbcc)

## Materials & Methods

+++

供試植物

<img src="img/procedure.png" width="90%">

Note:

エンドウを使いました。１７日間育苗して、その後強光あるいは弱光のもとで育てて、光合成能力を測る、という簡単な系です。

+++

試験区

<img src="img/scheme.png" width="90%">

Note:

試験区は５つ。
基本的に処理区あたり３株を測定に使って、最大８反復をとりました。

+++

測定項目

<div style="position:relative; left:10px">
<br>
- <small>光合成能力</small>
  - <small>CO<sub>2</sub>濃度1%、飽和光 (白色LED, 2000 µmol m<sup>-2</sup> s<sup>-1</sup>) での総酸素発生速度</small>
- <small>functionalなPSII量</small>
  - <small>飽和閃光４回で１回の酸素発生を仮定 (Chow et al. 1991; Aust J Plant Physiol)</small>
- <small>cyt-bf量</small>
  - <small>光合成能力・functionalなPSII量から経験式に従って算出 (Dwyer et al. 2012; JXB)</small>

</div style="position:relative; left:25px">

---?color=linear-gradient(to left, #ccddee, #aabbcc)

## Results & Discussion

+++



**結果１: 光合成能力の推移**

<div class="column1">
<img src="figure/pmax-1.png" width="100%">
</div class="left">

<div class="column2">
<br>
@ul
- <small>HL:<br>処理開始から光合成能力が概ね一定<br> → 葉は成熟ずみ</small>
- <small>LL:<br>処理開始以降、指数関数的減衰<br> → 濃度依存的な分解 (一次反応)</small>
@ulend
</div class="left">

+++

**結果１: 光合成能力の推移**

<div class="column1">
<img src="figure/pmax-2.png" width="100%">
</div class="left">

<div class="column2">
<br>
@ul
- <small>R2, R4, R8:<br>再強光処理で回復 <br>→ <orange>強光順化</orange></small>
- <small>R17でも回復あり</small>
@ulend
</div class="right">

+++



**結果２: cyt-bf量の推移**

<div class="column1">
<img src="figure/cyt-1.png" width="100%">
</div class="left">

<div class="column2" style="position:relative; left:-2%">
<br>
<br>
@ul
- <small>光合成能力と同様の傾向</small>
- <small>cyt-bf量が光合成能力の主要な律速要因 <small>(Dwyer et al. 2012; JXB)</small></small>
- <small><orange>成熟葉内でもcyt-bfが合成された？</orange></small>
@ulend
</div class="right">

<!-- +++ -->

<!-- ```{r recovery} -->
<!-- list_figure$recovery + -->
<!--   labs(caption = "Means ± SE, N = 2–8 (Murakami et al., Under review)") -->
<!-- ``` -->

<!-- **結果２: cyt-bf量の推移** -->

<!-- <img src="figure/recovery-1.png" width="80%"> -->

<!-- @ul -->
<!-- - <small>R8でやや回復開始が遅れる傾向があるものの、大差なしか？</small> -->
<!-- @ulend -->





+++

**結果３: cyt-bf分解・合成特性の解析**

<div style="font-size: 0.5em">
`\[
\frac{dy}{dt} = - k_\textrm{d} \cdot y + k_\textrm{r} \cdot (y_\textrm{steady} - y)
\]`
</div style="font-size: 0.5em">

<div class="fragment">
<div class="column1">
<img src="figure/sample-1.png" width="90%">
</div>

<div class="column2">
<br>
@ul
- <small>*k*<sub>d</sub>: 分解速度</small>
- <small>*k*<sub>r</sub>: 合成速度</small>
- <small>*y*<sub>steady</sub>: 順化後の定常値</small>
@ulend
</div>
</div class="fragment">

Note:

この回復の項が、暗期あるいは弱光時にはなし、強光照射時にはあり、という形です。
強光処理区では、cyt-bfは一定と仮定しています。

+++

<!-- **結果３: cyt-bf分解・合成特性の解析 (モデル vs 実測)** -->

<!-- <img src="figure/model-4.png" width="80%"> -->

<!-- +++ -->

**結果３: cyt-bf分解・合成特性の解析**

<div class="column1">
<img src="figure/model-2_light.png" width="100%">
</div>
<div class="column2">
<img src="figure/model-3.png" width="100%">
</div>

Note:

ポイントが個葉のデータで、帯が確信区間です。
モデルと実測で散布図を見ておくと、こんな感じです。強光区は一定としているので覗いています。それなりに乗っているので大丈夫そうです。

+++

**結果３: cyt-bf分解・合成特性の解析**

<div style="font-size: 0.5em">
`\[
\frac{dy}{dt} = - k_\textrm{d} \cdot y + k_\textrm{r} \cdot (y_\textrm{steady} - y)
\]`
</div style="font-size: 0.5em">



<div class="column1">
<img src="figure/kr-1.png" width="100%">
</div class="column1">

<div class="column2">
<br>
@ul
- <small>顕著な試験区間差はなし<br>(半減期換算でおよそ14–17日の範囲)</small>
- <small>むしろ弱光日数が長いほど回復が速い？</small>
@ulend
</div class="column2">

Note:

１週間程度の弱光であれば強光順化の柔軟性を損ねないらしい、という結果です。
予想と大きく外れましたが、これはこれでいいこともあります。時定数が大きくは変化しないので、




+++

**補光シミュレーション: 来週の総光合成量を高める**

<img src="img/compare_schemes.png" width="100%">

<div style="line-height: 1.2; font-size: 0.5em">
個体に成熟葉が１枚だけ / ON・OFF制御 300 µmol m<sup>-2</sup> s<sup>-1</sup>の補光設備 / PPFD 300 µmol m<sup>-2</sup> s<sup>-1</sup> で回復項 (*k*<sub>r</sub>) ありなしが切り替わり / 非直角双曲線型の光ー光合成曲線 (初期勾配 = 0.05, 凸度 = 0.80, 暗呼吸速度 = 光合成能力/10) / 常にCO<sub>2</sub>飽和条件 / 葉温は一定
</div style="font-size: 0.5em">

+++

<div class="column1">
<img src="figure/simu-1.png" width="100%">
</div class="column1">

<div class="column2">
<div class="fragment">
<img src="img/with_curve.gif" width="100%">
</div class="fragment">
</div class="column2">

Note:

コツコツ補光区の例ですね。光合成能力の時間変化はこんな感じです。
で、その各時間での光合成曲線がこうです。水色のカーブが積み重なるイメージです。


+++

<div class="column1">
<img src="figure/simu-1.png" width="100%">
</div class="column1">

<div class="column2">
<img src="img/with_diurnal.gif" width="100%">
</div class="column2">

Note:
で、PPFDも既知としているので、光合成速度の経時推移が計算できる、という形です。

+++

<div class="column1">
<img src="figure/simu-2.png" width="100%">
</div class="column1">

<div class="column2">
<div class="fragment">
<img src="figure/simu-3.png" width="100%">
</div class="fragment">
</div class="column2">

Note:

コツコツとまとめてを比較してみます。
光合成能力の推移がこうで、光合成速度の推移がこうです。
どっちが大きいのか、ぱっと見てもわかりませんが

+++

<div class="column1">
<img src="figure/simu-2.png" width="100%">
</div class="column1">

<div class="column2">
<img src="figure/simu-4.png" width="100%">
</div class="column2">

<div class="fragment" style="text-align:center">
コツコツ補光 < まとめて補光
</div>

---?color=linear-gradient(to left, #ccddee, #aabbcc)

## Summary

+++

<div style="position:relative; left:30px">

@ul
- **Q. 成熟葉の光合成能力は強光順化応答を示さないのか**
    - **A. 示す**
<br>
- <middle>cytochrome *b*<sub>6</sub>*f*は成熟葉内でも合成されるらしい</middle>
- <middle>１週間程度の弱光処理であれば、強光順化の柔軟性を損ねないらしい</middle>
- <middle>順化のモデル化により少し先の将来までの光合成量を踏まえた意思決定が可能</middle>
@ulend
</div style="position:relative; left:10px">

<!--html_preserve--><div style='position:absolute; left:-50%; width:200%; top:580px; height:60px; padding:10px; font-size:0.5em; text-align:center; background-color:grey; color:white'><!--/html_preserve-->
This work was supported by JSPS KAKENHI (Grant Number 17J04736)  
‘個体光合成量の制御と予測のための個葉の光合成特性の経時推移モデルの開発’
</div>


---?color=linear-gradient(to left, #6688ee, #4466cc)

### Appendix

+++

<div style="position:relative; left:10px">

**新出葉・隣接個体からの遮蔽は？**  

<small>**若干はあり**。ただし主茎カット区の光合成能力がHL区と概ね同様なのでマイナー。</small>

</div>



![](/figure/stemcut-1.png)

+++


**モデルの妥当性は？**

<div style="position:relative; left:10px; font-size: 0.6em">

<ul>
<li> 悩ましい</li>
<li>R8の回復開始の遅れを反映する狙いで、ロジスティック曲線も試したが、<br>統計モデルの収束に難あり</li>
<li>一般化するなら完全に再順化能を失うまで弱光日数を伸ばす必要がある</li>
<li>R17までは試してみたところ、ややヘタれるものの強光順化可能</li>
<li>はっきり言えそうなのは、<br>「1週間程度の弱光であれば、光合成能力の順化の柔軟性を**極端に**損ねることはなさそう」ということ</li>

</div>

+++

<small>**The switch-off of cyt-bf biogenesis in mature leaves**—Hojka et al. (2014; Plant Physiol)</small>  
<small>**Ontogenetic repression of cyt-bf biogenesis**—Schöttler et al. (2015; JXB)</small>

<div style="position:relative; left:10px; font-size: 0.6em">
<br>
@ul
- 強光再照射が強すぎたせいでは？
    - ‘... under high-light conditions, all plants suffered from moderate oxidative stress ’—(Hojka et al. 2014)
        - cyt-bfのサブユニット (PetD) はPSIIのD1と同じくらい高速で分解・修復される <small>(Li et al. 2018; Trend Plant Sci)</small>
        - D1のような修復阻害？ <small>(Nishiyama et al. 2011; Physiol Plant)</small>
- 種依存性があるのでは？
    - 文献はタバコ、今回はエンドウ
@ulend
</div style="position:relative; left:10px">

<!-- +++ -->

<!-- <div style="position:relative; left:25px"> -->


<!-- **強光ストレスをもう少し具体的に**   -->

<!-- - <small>**cyt-bfのサブユニットのターンオーバー阻害では？**</small> -->
<!--     - <small>cyt-bfのPetDというサブユニットは、損傷・回復の顕著なPSIIのD1サブユニットと類似点が多い (Li et al. 2018; Trend Plant Sci) -->
<!--     - <small>D1は活性酸素により修復が止まる (Nishiyama et al. ; )</small> -->
<!-- </div> -->


