# 🌙 月の刻 — Tsuki no Koku craft studio

> **月明かりに、永遠を刻む。/ carved by moonlight**
>
> UVレーザー彫刻ブランド「月の刻」のデザインアセット管理リポジトリ。
>
> ## ブランド情報
>
> | 項目 | 内容 |
> |------|------|
> | ショップ名 | 月の刻（Tsuki no Koku）craft studio |
> | コンセプト | 月明かりに、永遠を刻む。/ carved by moonlight |
> | 使用機材 | xTool F2 Ultra（UV レーザー） |
> | デザイン生成 | Claude AI → SVG / DXF |
> | 販売先 | Etsy（海外）・国内直販 |
>
> ## ブランドカラー
>
> | 用途 | HEX |
> |------|-----|
> | ゴールド（メイン） | `#c9a04a` |
> | 夜空ネイビー（背景） | `#1e2a38` |
> | クリーム（アクセント） | `#fdf8f0` |
>
> ## リポジトリ構成
>
> ```
> mirai-kobo-crystal/
> ├── designs/            # マスターデザインファイル
> │   ├── svg/            # SVGソース（編集用）
> │   ├── dxf/            # DXF（xTool用）
> │   └── png-preview/    # プレビュー画像
> ├── products/           # 素材カテゴリ別の完成デザイン
> │   ├── crystal/        # クリスタル彫刻
> │   ├── acrylic/        # アクリル彫刻
> │   ├── wood/           # 木材彫刻
> │   └── glass/          # ガラス彫刻
> ├── templates/          # 再利用パーツ（和柄・枠・ロゴ等）
> └── docs/               # 加工設定メモ・運用ガイド
> ```
>
> ## ファイル命名規則
>
> ```
> [素材]_[モチーフ]_v[番号].[拡張子]
>
> 例:
> crystal_samurai-silhouette_v1.svg
> acrylic_torii-gate_v2.dxf
> wood_sakura-branch_v1.svg
> ```
>
> ## コミットメッセージ規則
>
> ```
> [add]    新規デザイン追加
> [update] 既存デザイン修正
> [fix]    パス修正・バグ修正
> [release] Etsy出品済みマーク
> ```
