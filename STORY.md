# Day026 Story — Risk Quadrant Mapper

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day026専用にテーマをseed固定して再生成時の見た目を安定化
- planning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: quadrant_mapping
- Mechanic: axis_mapping
- Input/Output: item_with_scores -> quadrant_matrix
- Audience Promise: faster_priority_alignment
- Publish Hook: 4象限で優先度の議論を短縮
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Add 2 safe enhancement components from selected_components while keeping the app single-page and stable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day026｜Risk Quadrant Mapper
課題を4象限に配置して対応優先度を可視化するマッパー。（話題:GitHub Trending (A）
