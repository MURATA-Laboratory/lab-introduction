---
theme: neversink
# themeConfig:
  # primary: '#5d8392'
title: 村田研究室研究室紹介
titleTemplate: '%s'
info: false
class: text-center
# drawings:
  # persist: false
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: cover
color: pink
neversink_slug: '村田研究室研究室紹介'
---

# <span class="font-bold">村田研究室<br>研究室紹介</span>

2024年度　村田 匡輝

<!-- <div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div> -->

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: top-title
color: pink-light
---

:: title ::
# 村田研究室では...

:: content ::
## <span v-mark.red>自然言語</span>処理に関する研究を促進

<v-click>

- 人間が普段，話したり書いたりする言葉．人間がコミュニケーションを取る最も手軽な方法の一つ

</v-click>

<v-click>

- 代表的な自然言語処理技術：

</v-click>

<v-click><img border="rounded" src="/lab/nlp.png" width="" height="" alt="nlp"></v-click>

<!-- <div grid="~ cols-3 gap-2" m="t-2"> -->

<!-- <v-click><img border="rounded" src="/lab/nlp1.png" width="1012" height="760" alt="nlp1"></v-click> -->

<!-- <v-click><img border="rounded" src="/lab/nlp2.png" width="857" height="847" alt="nlp2"></v-click> -->

<!-- <v-click><img border="rounded" src="/lab/nlp3.png" width="1595" height="893" alt="nlp3"></v-click> -->


<!-- </div> -->

<!-- The <span v-mark.red="3"><code>v-mark</code> directive</span>
also allows you to add
<span v-mark.circle.orange="4">inline marks</span>
, powered by [Rough Notation](https://roughnotation.com/): -->


---
layout: statement
color: pink
---

# 自然言語処理の中でも特に，<br><span v-mark.circle.red>「音声言語」</span><br>を対象とした研究を実施

---
layout: top-title-two-cols
columns: is-8
align: l-lt-lt
color: pink-light
transition: slide-up
---

:: title ::
# 1. 人の語りを傾聴するシステムの開発

:: left ::
## 人は基本，語りたい

- でも，話を聞いてくれる人がいつもいるわけじゃない...<br> ⇨ 情報機器に聞き手になってもらう‼️
<!-- <carbon-badge /> -->

## <span class="text-pink-500">話を上手に聞く方法</span>：傾聴態度を示す

- 適度に相槌する
- 共感する
- 褒める　etc...

<span class="bg-pink-400 text-pink-100 p-2 border-l-6 border-2 border-pink-500 rounded-lg pl-4 pr-4 font-size-7">**人間の欲求を満たすシステム**</span>

<!-- <AdmonitionType type='important' >
人間の欲求を満たすシステム
</AdmonitionType> -->

:: right ::
<img class="" src="/lab/robot.png" alt="">


---
layout: top-title
color: pink-light
---

:: title ::
# 1. 人の語りを傾聴するシステムの開発

:: content ::
## 研究テーマ

- 傾聴応答のタイミング推定，表現生成，個人最適化，<br>マルチモーダル情報の利用，大規模言語モデルの活用など
  - 高齢者の語り30名分に対する聴き手11人分の傾聴応答コーパスを利用して研究を推進

<audio controls><source src="/lab/01-1_o_mix.wav" type="audio/wav"></audio>

<img class="" src="/lab/attentive_listening.png" alt="">

---
layout: top-title-two-cols
columns: is-8
align: l-lt-lt
color: pink-light
transition: slide-up
---

:: title ::
# 2. 読みやすい字幕を生成するシステムの開発

:: left ::
## 講演などの場では

- 高齢者・聴覚障害者の方のために字幕を提示
  - 遠隔講義の動画等でも有用

⇨ <span class="text-pink-500">**音声認識で自動生成された字幕をより読みやすくしたい‼️**</span>

<span class="bg-pink-400 text-pink-100 p-2 border-l-6 border-2 border-pink-500 rounded-lg pl-4 pr-4 font-size-7">**整形，提示方法の工夫**</span>

## 研究テーマ

- 音声と視覚情報を活用した字幕表示の最適化
- ユーザ個別最適化字幕の生成
- 発話時間と字幕の提示時間の差異を埋める字幕提示　　など…

:: right ::
<img class="" src="/lab/transcription.png" alt="">

---
layout: top-title
color: pink-light
transition: slide-up
---

:: title ::
# 2. 読みやすい字幕を生成するシステムの開発

:: content ::
<img class="" src="/lab/eyetracking.gif" alt="">

---
layout: top-title
color: pink-light
---

:: title ::
# 2. 読みやすい字幕を生成するシステムの開発

:: content ::
<img class="" src="/lab/caption.gif" alt="">

---
layout: default
color: pink
---

# メッセージ

- 自然言語処理の研究には以下の能力が必要となりますが，これらは徐々に身につけていけば良いものです
  - 言語学や数学に関する基礎学力
  - プログラミング能力（うちでは主に Python を使用）
  - 既存研究を調査・理解する能力

<div class="text-pink-500 bg-white p-1 pl-3 pr-3 m-1 rounded font-size-6 text-center font-bold">
僕と密に報連相を行い，自主性を持ってコツコツ進めることが大事です．<br>
まずは興味ある研究テーマを一緒に見つけましょう
</div>

- 卒業研究の様子は見学で
  - 情報工学科棟4階　卒研室９
    - 4階は階段がちょっと大変だけど，端っこの部屋で気に入っています
    <!-- - 5年生に雰囲気とか聞いてみてね（卒研の中間発表前なので忙しなくしてるかもしれない） -->
