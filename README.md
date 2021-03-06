# Personally-frequently-used-IntelliJ-commands
個人的によく使う IntelliJ のコマンド

Windows 編


## ファイル

| コマンド | 説明 |
| ---- | ---- |
| Shift 2 回 | なんでもサーチ。クラスや、文字列など色々まとめて検索できる。 |
| Ctrl＋E | 最近利用したファイルを選択して開く |
| Alt＋Insert | ファイル新規作成 |
| F6 | 選択したファイルや、パッケージを移動する。 |
| Shift＋F6 | ファイル名を変更する。クラスファイルなどの場合には、クラス名も変更される。 |


## エディタ

| コマンド | 説明 |
| ---- | ---- |
| Alt＋Enter | エラー対処候補、複数行化、パラメータ名追加などなど、複数の機能を選択するダイアログが開く。表示内容は、場所によって適切な候補となる。 |
| Ctrl＋Alt＋O | インポートを整理する。 |
| Ctrl＋Alt＋L | ソースコードを整形する。 |
| Ctrl＋Q | カーソル箇所の関数などのドキュメントが確認できる。コード補完中では、候補のドキュメントが表示される。 |
| Ctrl＋P | 関数の引数定義を表示。カッコの内部にカーソルを入れておくこと。 |
| F2 | エラー箇所へ飛ぶ。文法エラーや、タイポなどにも移動できる。 |
| Shift＋Enter | カーソル位置に関係なく、下の行を改行してカーソルを下の適切な位置にカーソルを移動する。終端のカッコなどがあっても、カーソルを移動する事無く、次の行の入力をすぐに行える。 |
| Shift＋Ctrl＋Enter | Java や TypeScript などでは、行末の ; などを自動的に入力して、次の行を改行して、下の適切な入力位置にカーソルを移動する。 |
| F6 | 選択箇所のクラスや、関数をパッケージや、ファイルに移動する。 |
| Shift＋F6 | カーソル箇所のクラス名、関数名や、変数名を変更する。 |
| Alt＋F7 | カーソル上の定義などを利用している箇所を検索する。 |
| Ctrl＋B | カーソル上の定義箇所に飛ぶ。 |
| Ctrl＋Alt＋M | 選択範囲をメソッドに切り出すリファクタリングをする。 |
| Ctrl＋Z | アンドゥ |
| Shift＋Ctrl＋Z | リドゥ。Windows の場合、多くのエディタで Ctrl＋Y はリドゥだが、IntelliJ の場合は、行削除になるので注意。 |
| Ctrl＋D | 行を複製する。 |
| Ctrl＋C | コピー。未選択の場合は、行コピーとなる。 |
| Ctrl＋X | カット。未選択の場合は、行カットとなる。 |
| Shift＋Ctrl＋U | 大文字小文字変換。トグルで切り替わる。 |
| Shift＋Alt＋↑↓ | 選択行または、カレント行を上下に移動 |
| Shift＋Ctrl＋↑↓ | 移動対象を考慮した上下移動。インデントが考慮されたり、関数名上の場合、上下の関数を入れ替えるなど、対象によって挙動が変わる。複数行で引数を記述している場合では、引数を移動すると、行末のカンマなどが自動的に整形される。 |
| Ctrl＋Tab | 前回選択していたタブに切替。繰り返し押すと、交互に切り替わる。 |
| Ctrl＋Tab（Ctrl 押したまま） | ファイル選択ダイアログが開く。Ctrl を押したまま、Tab や、矢印キーでファイルを選択できる。Ctrl＋数字や、アルファベットで、Terminal ウィンドウや Git ウィンドウなどにカーソルを移動できる。 |
| Ctrl＋Space | コード補間。コード補完ダイアログ表示中にもう一度押すと、候補が追加される。初回は、よく使う候補が表示されている。 |
| Shift＋Ctrl＋Space | コード補完（型が合うなどの適切な候補のみ表示）。ただし、万能ではない。 |
| Esc | エディタ以外にカーソルがある場合、エディタにカーソルが移動する。 |
| Shift＋Ctrl＋F12 | エディタの全画面化のトグル動作をする。 |
| Shift＋Esc | エディタ以外にカーソルがある場合、非表示にしてエディタにカーソルが移動する。エディタ上にカーソルがある場合は、直前にカーソルがいたウィンドウが非表示となる。繰り返し押すと、順にエディタ以外が非表示となる。ただし、エディタ以外でも非表示にならない場合があるが、理由は不明。 |
| Shift＋Ctrl＋BackSpace | 直前にソースコードを変更した箇所に飛ぶ。 |
| Ctrl＋Alt＋←→ | カーソルの移動履歴にしたがって、戻ったり進んだりする。ソースコードが利用箇所へ飛んだりした後に、戻りたい時に利用する。 |
| Alt＋←→ | タブ切替をする。 |
| Alt＋↑↓ | クラス、フィールドや、関数単位でのカーソル移動。 |
| Alt＋Insert | カーソル箇所に適した、新規作成対象の選択ダイアログが開く。 |


## 構成管理（Git など）

| コマンド | 説明 |
| ---- | ---- |
| Ctrl＋K | Commit ダイアログ表示 |
| Shift＋Ctrl＋K | Push ダイアログ表示 |
| Ctrl＋T | Pull ダイアログ表示。rebase 設定にして、毎回問い合わせない設定で利用している。 |


## 実行

| コマンド | 説明 |
| ---- | ---- |
| Shift＋Ctrl＋F10 | カーソル行を実行。main 関数や、テストなどで利用可能。 |
| Shift＋F10 | 画面左上 run/debug 設定ドロップダウンで選択している対象を通常実行する。 |
| Shift＋F9 | 画面左上 run/debug 設定ドロップダウンで選択している対象をデバッグ実行する。 |


## デバッグ

| コマンド | 説明 |
| ---- | ---- |
| F7 | 呼び出し先内部に移動する。 |
| F8 | 次の行まで実行する。ラムダ関数内部には移動しないので注意。 |
| F9 | 再開する。 |
| Ctrl＋F2 | 停止する。 |
