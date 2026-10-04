---
name: level
description: 表示レベル（auto / low / medium / high）を切り替える。
disable-model-invocation: true
argument-hint: "[auto|low|medium|high]"
---

切り替えの保存は、フックが入力を受け取った時点で済んでいる。結果は、このターンの `[Cogito] 表示レベル` で始まる追加コンテキストに示される。

この呼び出しへの応答は、表示行の1行だけにする。
- 例：`[High] ※表示レベルを High に切り替え`（English: `[High] * Display level set to High`）
- auto の場合：`[Medium] ※表示レベルを Auto に切り替え`（Auto の表示は Medium から始まる）
- 変わらなかった場合・保存できなかった場合は、追加コンテキストにある結果をそのまま1行で示す。
- 表示行の言語・記号は、ユーザーの言語に合わせる。

レベルの説明、使い方の案内、どのレベルがよいかの助言は付けない。どのレベルで進めるかは、ユーザー自身が決めることである。
