# 更新履歴

CHRONOの主な変更内容を記録しています。

---

## [β0010-STD.1.38.1 / β0010-ENH.1.40 / β0010.1.36] — 全エディション共通（2026年5月）

### 追加

- **HISTORY：既存GROUPへのSession追加** — グループヘッダーに「＋」ボタンを追加。グループを作り直すことなく、既存グループへSessionを追加できるポップアップを表示。
- **HISTORY：GROUPからSessionを個別に外す** — グループ内の各Session行に「↩ Leave Group」ボタンを追加。グループ全体を削除することなく、特定のSessionだけをグループから外せる。
- **HISTORY：グループ内のSession並べ替え** — グループ内のSession行に↑↓ボタンを追加。ドラッグ不要でSession順を変更できる。

### 改善

- **HISTORY：CONTINUEボタン（▽/▼）** — 点滅アニメーションを廃止し、点灯/グレーアウトの表示に変更。ON = 塗りつぶし（▼）金色、OFF = アウトライン（▽）グレー。印刷時にも状態が反映される。
- **HISTORY：グラブアイコン** — Unicode点字文字（⠿）からインラインSVGに変更。環境・ブラウザによる表示の差異を解消。
- **HISTORY：印刷時のページ分割** — グループ単位でページ分割されるように改善。グループ内のSessionが1ページに収まらない場合は次ページに続く。
- **全エディション共通：「グループ化」→「Group」** — グループ化ボタンのラベルを英語に統一。

---

## [β0010-STD.1.36.2 / β0010-ENH.1.36.4 / β0010.1.34.3] — 全エディション共通（2026年5月）

### 追加

- **HISTORY：セッションメモ** — セッションごとにリッチテキストのメモを追加可能。文字色・フォントサイズの変更に対応。入力中に自動保存。
- **HISTORY：GAIN / FADER** — セッションごとにゲイン・フェーダー値を設定・表示。HISTORYリストおよびSETLIST右ペインのタイトル横に表示される。（GAIN は手入力、FADER はプルダウン選択 −20〜+12 dB）
- **HISTORY：CONTINUEボタン（▽/▼）** — セッションが次の曲へ続けて出すかどうかを示すフラグ。ON時は▼（塗りつぶし・金色）、OFF時は▽（アウトライン）で表示。印刷時にもON/OFFの状態が反映される。
- **HISTORY：印刷機能** — HISTORYツールバーにCOLOR / MONOの印刷ボタンを追加。セッション一覧をキューシートとして印刷・PDF出力できる。
- **HISTORY：ツールバーの整理** — SORTとDATAを1段に統合。TEMPLATE・GROUP・PRINTの段組みに変更。
- **SETLIST：セッション情報バー** — 右ペインのタイトル横にGAIN・FADER・セッションメモを表示。（Enhanced / LTC）

### 改善

- HISTORYのラップ列順を修正：✎（メモ）ボタンを最終列に移動し、スピーカーとCD列のヘッダーとのズレを解消。
- SETLISTバッジ（+SLボタン）を `updateSlBadges()` で一元管理するよう変更。

---

## [β0010.1.0] — LTC EDITION（2026年5月）

### 追加

- LTC（Linear Timecode）Sync — Q-LABなどのタイムコード信号と連動したセッション自動再生・自動追従
- SETLISTとLTC Syncの連携 — LTCタイムコードによるセッション自動切替
- キーボードショートカット対応

### 収録エディション

- Standard Edition β0010.10.39
- Enhanced Edition β0010.10.39
- LTC Edition β0010.1.0
- LTC Decoder α0000.8.10.17

---

## [β0010.10.39] — Standard / Enhanced Edition

### 追加

- REALTIMEモード — 事前に作成したセッションを再生しながらリアルタイムで上書き更新（Enhanced）
- SETLISTモード — 複数セッションをセットリストとして管理・順番切替（Enhanced）
- 2カラムレイアウト対応
- カウントダウン（PRE・3・2・1・GO）へのカスタム音源アサイン対応
- セッションデータのJSONエクスポート・インポート
- LAP OFFSETの設定
- ラップごとのLABEL COLOR設定
- rtSnapshot機能（Enhanced）

### 改善

- PREVIEWモードの安定性向上
- HISTORYモードのグループ化・並べ替え改善
- UI全体の調整

---

## Notes

- 本ソフトウェアは現在**β開発版**です。予期しない動作やエラーが発生する可能性があります。
- 本番運用前に必ず動作検証を行ってください。
- バグ報告・機能リクエストは [GitHub Issues](https://github.com/SOUND-SCOPE/CHRONO/issues) で受け付けています。

---

*English version: [CHANGELOG.md](CHANGELOG.md)*
