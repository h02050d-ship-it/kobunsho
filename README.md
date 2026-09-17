# 公文書ビューア（e-Gov XML）

e-Gov・日本年金機構から届く公文書(XML＋XSL)のzipをブラウザに放り込むと、XSLを当てて帳票の見た目に戻し、印刷/PDF保存できる。
ファイルはブラウザ内だけで処理（外部送信なし）。

- 本番: https://h02050d-ship-it.github.io/kobunsho/
- `?src=<zipのURL>` で自動読込、`?engine=js` で純JS変換(XSLTProcessor廃止後の保険)
