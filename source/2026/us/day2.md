# Day 2

````{admonition} コラム：(terapyon LTコラム)
ここにコラムを書いてね
````


## Member Lunch

* Grantの期間はみじかくなった
* 金額はAfricaが多いなぁ
* 質疑応答
* 寺田さんと吉田さんの質問

````{admonition} コラム：PSF Member Lunchについて
一般社団法人PyCon JP Association理事の吉田([@koedoyoshida](https://twitter.com/koedoyoshida/))です。PyCon US のメンバーランチに参加してきました。

```{figure} images/member-lunch-desc.jpg
:height: 400

Deb Nicholson氏の説明の様子
```


```{figure} images/member-lunch-food.jpg
:height: 400

食事の様子
```

PSFメンバーランチはランチを取りながら、PSF（Python Software Foundation）のメンバーが一堂に会し、財団の現状やこれからについて語り合う、毎年恒例の場です。

今年もPSFのExecutive DirectorであるDeb Nicholson氏から説明がありました。

例年であればこのランチで PSF の昨年の財務報告のサマリとなる資料が共有されるのですが、今年は財務資料の配布については見送りとなりました。

そこで私は「今年は財務資料の配布がないようですが、昨年の財務状況はどうだったのでしょうか。資料はWebで公開されるのでしょうか？」と直接質問してみました。すると運営側から率直な回答が返ってきました。

回答内容は「会計担当の体制が変わった影響で、今回はまとまった数字をお見せできる状態に間に合わせられなかった。ただ財務の透明性は大切にしているので、体制が整い次第あらためて資料を公表する予定です」といったものです。
数字の詳細こそその場では出ませんでしたが、財務状況をめぐる考え方や今後の方針について、こちらの疑問にきちんと答えてくれました。

PSFメンバーランチは、PSFメンバーが事前登録のうえ参加できる貴重なイベントで、その場で質問も可能です。たとえば、月に5時間程度、PythonやPyConに継続的に関わっているなどの条件を認められれば、PSFメンバーのうちContributing Memberとして登録が可能で、理事選挙の投票権なども得られます。該当する方や興味のある方は、ぜひ以下のページで詳細をご確認ください。

[Become a Member of the PSF](https://www.python.org/psf/membership/)


````

## Tachyon: Python 3.15's sampling profiler is faster than your code - PyCon US 2026

* https://us.pycon.org/2026/schedule/presentation/31/
* python -m profile.sampling
* capture mode

```
python -m profile.sampling run main.py
python -m profile.sampling attach <pid>
```

reporters

* visualizeされる
* 最初に見るのは --pstats

what;s happening now?

* フレームグラフがカラーで見れる

* --heatmap
* --diff-framegraph →パフォーマンスが上昇したか見れる
* --gecko: Firefoxのprofilerを使える
* あとでanalyzeする: --binary

````{admonition} コラム：(koxudaxiコラムタイトル)
ここにコラムを書いてね
````

## mypyc?

## PyLadis Auction


