# Mother Vegetable LP 静的デザインモック

作成物:
- `index.html` — 単体でブラウザ表示できるLPトップページの静的HTML/CSSモック

確認方法:
1. ブラウザで `/home/panai/workspace/mother-vegetable-lp/index.html` を開く
2. または、このフォルダで簡易サーバーを立てて確認

```bash
cd /home/panai/workspace/mother-vegetable-lp
python3 -m http.server 8080
```

その後、ブラウザで `http://localhost:8080/` を開く。

デザイン要点:
- 生成り・ミント・ディープグリーンを基調に、生命感/地球/透明感を表現
- ファーストビューは「地球原材料から生まれる、これからの商品づくり。」を中心に、地球・CO₂・素材・商品・人の想いの循環を抽象ビジュアル化
- Achieve / Confidence を2カラムの素材紹介として整理
- Product Story / Searching System / New Commerce で、ストーリーECと参加型コマースの方向性を見える化
- PC/SPどちらでも見られるレスポンシブ構成

注記:
- 実装先が未定のため、既存プロジェクトには組み込まず、単体で開ける静的モックとして作成
- 写真素材は未提供のため、現段階ではCSSによる抽象ビジュアル・商品モックで表現
