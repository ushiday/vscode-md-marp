---
marp: true
theme: uncover
header: "**ushiday** __Marp samples__"
footer: "by @ushiday (Chubu System.,Ltd.)"
---
<!--
backgroundColor: black
_color: white
-->

# ushiday marp
Marp = mdよりスライドを作成するプラグイン
## (03) ページ毎にスタイルを適用する方法

作成日 : 2020.07.08  **(ushiday)**

---
<!--
_backgroundColor: orange
paginate: true
-->
# ページ1
`<!-- -->`内に設定値を記載する。
`_`付きで設定すると、指定したページのみ反映。
`_`なしは指定ページ以降に反映。
使用例
```md
<!--
_backgroundColor: orange
paginate: true
-->
```

---
<!--
_backgroundColor: white
-->

# ページ2

コンテンツ2

---
<!--
_color: yellow
-->
# ページ3

コンテンツ3
