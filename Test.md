---
marp: true
paginate : true
theme : aquatan
math: mathjax
class: normal
---

<!--
_class: top
-->

# Marpの使い方
## t-tanimot@そふらぼ


---

# 書き方

- マークダウンで資料が作れる
- 例えばこのページは下のように書ける．

```md

# 書き方

- マークダウンで資料が作れるよ
- 例えばこのページは下のように書けるよ．

```

---

<!-- 
_class: title_dark
-->

# こんなページも作れる

---
<!--
_class: title_light
-->

# こんなページも作れる

---

# 文字装飾

- 色んな文字装飾ができるよ
- **太字**
    - \*\*太字\*\*
- *イタリック*
    - \*イタリック\*
- ***太字イタリック***
    - \*\*\*太字イタリック\*\*\*
- ~~取り消し線~~
    - \~\~取り消し線\~\~

---

# 文字装飾

- HTMLとして処理されるから，色も付けられるよ．
- <span style="color:red; ">赤色</span>
    - \<span style="color: red; ">赤色\</span>
- 順序つきの箇条書きもできるよ
    1. ようこそ
        1. ソフトウェア
            1. 工学研究所へ．

---

# 画像
- パスで指定することで、画像を配置できる
![h:120px](./img/aquatan_gray.png)

---
# 画像加工
- 画像を加工することもできるよ
![h:120px](./img/aquatan_gray.png) ![blur h:120px](./img/aquatan_gray.png) ![brightness h:120px](./img/aquatan_gray.png) ![contrast:200 h:120px](./img/aquatan_gray.png)![drop-shadow:0,10px,10px,rgba(120,0,0,.4) h:120px](./img/aquatan_gray.png)
![invert h:120px](./img/aquatan_gray.png)![opacity h:120px](./img/aquatan_gray.png)![sepia h:120px](./img/aquatan_gray.png)

---

# 使いづらい所

- アニメーションとか
  - Bespoken.js,reveal.js
- 中央寄せとか
- 左右分割とか
- 画像の配置とか
- CSSの勉強

---

<!--
_class: title_dark
-->

<style scoped>
section h1{
    position:float;
    text-align:center;
    justify-content: center;
    font-size: 500%
}

</style>

# Let's Marp