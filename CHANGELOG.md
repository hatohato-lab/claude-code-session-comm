# 変更履歴

## 2026-11-08
- 名前を、セッション一覧（session-list）から セッション間通信（session-comm）に変えた。コマンドは /sessions から /session-comm、リポジトリは claude-code-session-list から claude-code-session-comm に変えた。claude-code-session-list の名前は、いまは別の MOD（セッションリスト）のリポジトリが使っている。前の名前で入れていたら、入れ直す（README の「前の名前で入れていたとき」）
- session-comm v0.8.0。セッションリストの /session-set のペインでは、リストの表の下に矢印の図を足す
- v0.7.23 から v0.7.26。セッション情報の表のペインに図を足す試しをやめ、円グラフを外して、このペインを矢印の図だけにした

## 2026-10-21
- session-list v0.7.22 を公開した（Linux 向けの直し。同梱の Python 3本が、セッションが動いているかを Linux でも確かめる。Python は、Windows では python、Linux と macOS では python3 の名前で回し、起動できなければもう一方で回す）
- Linux で確かめる GitHub Actions（linux.yml）を足した。手で起動したときだけ動く

## 2026-10-20
- session-list v0.7.21 を公開した（セッション情報MOD の表のペインに、円グラフとやり取りの図を足す試し。いまの公開版のセッション情報MOD では、並ばないことがある）

## 2026-10-18
- session-list v0.7.20 を公開した（やり取りのシーケンス図、詳しい表示、返事待ちと承認待ち、入力欄、会話の地図、セッションの表、AI の要約、黒板の連絡）
