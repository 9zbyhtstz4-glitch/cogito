# Cogito-Plugin

AIを「全自動の代理人」ではなく、「人間の思考を止めない作業パートナー」へと変えるためのClaude Code用プラグイン

## 背景 (Background)
このプラグインは当初、単純に「AI開発の効率化」を目的に作り始められました。  
しかし計画を進めるうちに、ある深刻な問題に気づきました。それは「AIに頼りすぎることで、人間の思考が停止し、自ら決断する力が退化しつつあるのではないか」という懸念です。

この懸念を人間学や心理学の視点から分析して、この「思考の放棄」は決して人間の怠けではないことがわかりました。  
これはAIが出してくる情報量と人間の脳の受け入れ能力との間に大きなズレがあることが原因で起こる、**脳の防衛反応** によるものです。 ⁽¹⁾

この防衛反応を解き、人が心地よく考え続けられるようにするために本プラグインではAIの振る舞いに次のような制限をかけます。
* **情報の出し方を絞り込む:** 最初からすべての詳細を出さず、まずは全体を見渡せる数個の選択肢だけを短く提示します。 ⁽²⁾
* **直感的な言葉への翻訳:** 脳へのストレスとなる専門用語には、誰もがすぐ理解できる「意味」を添えさせること。 ⁽³⁾
* **思考の「余白」を作る:** AIに完璧な結論を押し付けさせず、人が自発的に発想できる安全なスペースを守ります。 ⁽⁴⁾

## 概要 (Overview)
上記のような背景から生まれた「Cogito-Plugin」は、AIを「全自動の代理人」ではなく、「人間の思考を止めない作業パートナー」へと変えるためのClaude用プラグインです。

AIの親切すぎる「しゃべりすぎ」をシステム側で抑え込み、人間の脳のペースに合わせて情報の出し方や言葉遣いを自動で調整します。  
これにより人が「自分で考え、選択し、学習する意欲」を保ち続けることをサポートします。

単なる作業のスピードアップを目指すのではなく、人が心地よく頭を使える「思考の足場」を用意することで、AI時代における人間の退化を防ぎ、結果として質の高い真の効率化を実現します。

## 由来（Origin）
このような問題や背景から、17世紀のフランスの哲学者ルネ・デカルトが残した言葉 "Cogito, ergo sum"（我思う、ゆえに我あり）から引用させてもらい。
まさに「私は考える」という意味で **Cogito** と命名しました。

---

<details>
<summary><small>科学的根拠・参考文献（Scientific References）</small></summary>
<small>

[ハーバード大学 (Harvard University)](https://developingchild.harvard.edu/resources/working-paper/understanding-motivation-building-the-brain-architecture-that-supports-learning-health-and-community-participation/)
<br>
[カーネギーメロン大学 (Carnegie Mellon University)](https://www.cmu.edu/student-success/other-resources/handouts/comm-supp-pdfs/visual-hierarchy-document-design.pdf)
<br>
[ハーバード大学 (Harvard University)](https://catalyst.harvard.edu/writing-communication-center/write-effectively/plain-language/)
<br>
[ハーバード大学教育大学院 (Harvard Graduate School of Education)](https://www.gse.harvard.edu/ideas/edcast/25/10/how-curiosity-can-unlock-learning-every-child)

</small>
</details>
</small>

## データの扱い（Data safety）

外部への通信はしません。
保存するのは、選んだ表示レベルとセッションごとの簡単な記録だけです。
記録は最後に使ってから7日経つと、次のセッション開始時に削除されます。

---

## 導入方法 (Install)

### Windows
```
claude.cmd plugin marketplace add dachi-jp3/cogito
```

```
claude.cmd plugin install cogito@cogito-plugins
```

---

### Mac
```
claude plugin marketplace add dachi-jp3/cogito
```

```
claude plugin install cogito@cogito-plugins
```

---

## 削除方法 (Uninstall)

### Windows
```
claude.cmd plugin uninstall cogito@cogito-plugins
```

```
claude.cmd plugin marketplace remove cogito-plugins
```

---

### Mac
```
claude plugin uninstall cogito@cogito-plugins
```

```
claude plugin marketplace remove cogito-plugins
```

---

## ライセンス（License）

Copyright 2026 dachi
[Apache License 2.0](LICENSE) 

## フィードバック（Feedback）

不具合や要望は [Issues](https://github.com/dachi-jp3/cogito/issues) へどうぞ。