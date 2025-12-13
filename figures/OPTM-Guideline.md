# OPTM (SPIE) 英文執筆・校正ガイドライン

日本語原稿の修正を英文に反映させる際、以下のルール（OPTM/SPIE標準）に準拠しているか確認するためのチェックリストです。

## 1. 文体と主語の使い分け (Voice & Subject)
「誰がやったか（貢献）」と「何が起きたか（事実）」で主語と態を明確に区別します。

- **能動態 (Active Voice): 著者自身の貢献・提案**
    - 主語: `We`
    - 用途: 提案手法、開発したシステム、結論を述べる時。
    - *例:* "We **developed** a multi-spectral imaging system..." (システムを開発した)
    - *例:* "We **propose** a step-wise band selection method..." (手法を提案する)

- **受動態 (Passive Voice): 実験手順・客観的事実**
    - 主語: `Measurements`, `The images`, `The error` など
    - 用途: 実験の手順、測定条件、結果の提示。
    - *例:* "The fluorescence images **were captured**..." (画像が取得された)
    - *例:* "The prediction accuracy **is calculated** by..." (精度は〜で計算される)

## 2. 時制のコントロール (Tense Strategy)
- **現在形 (Present Tense): 不変の事実・論文の構成**
    - 用途: 物理法則、一般的な性質、図表の説明、本論文の目的。
    - *例:* "Figure 1 **shows** the schematic diagram."
    - *例:* "Microplastics **exhibit** auto-fluorescence..." (一般的性質)

- **過去形 (Past Tense): 今回実施した実験・結果**
    - 用途: 行った実験の手順、特定のデータ結果。
    - *例:* "We **measured** the EEM of nine polymer types."
    - *例:* "The weighted F1-score **reached** 0.99."

## 3. 産業的価値の強調 (Keywords & Tone)
OPTMの趣旨（産業応用）に合わせ、以下のキーワードを積極的に使用し、曖昧な表現を避けます。

- **推奨キーワード (Keywords):**
    - **Robust** (ロバストな：外乱や配置変動に強い)
    - **Real-time / High-throughput** (リアルタイム / 高速処理)
    - **In-process** (インライン・製造工程内での)
    - **Low-cost** (低コスト：LED化など)
    - **Non-destructive** (非破壊)

- **禁止事項 (定性評価のみの記述):**
    - 数値の裏付けがない形容詞はNG。
    - × "High accuracy" (精度が良い)
    - 〇 "An accuracy of **89%**" (89%の精度)
    - × "Fast processing" (高速な処理)
    - 〇 "Processing time of **10 ms per frame**" (1フレーム10msの処理)

## 4. 実験機材の記述ルール (Experimental Setup)
再現性を担保するため、機材の初出時は以下のフォーマットで統一します。

- **表記:** `一般名称 (Model, Manufacturer)`
- *例:* "We used a **UV camera (GS3-U3, Teledyne FLIR)** and a **Xenon lamp (L25732, LPL)**."
- **必須:** 光学系の構成図 (Schematic Diagram) を `Fig. 1` 等として参照すること。

## 5. 図表と数式の記述 (Figures & Equations)
- **図表の説明:**
    - グラフを提示した直後に、軸の説明を入れる。
    - *例:* "The horizontal axis represents wavelength [nm], and the vertical axis represents intensity [a.u.]."
- **数式の定義:**
    - 数式の直後に必ず変数を定義する。
    - *例:* "...where $I$ is the fluorescence intensity and $\lambda$ is the wavelength."
- **単位:**
    - 数値と単位の間には半角スペースを入れる（例: `255 nm`, `0.60 g`）。

## 6. フォーマット最終確認 (Formatting Checklist)
- [ ] **カラム数:** 1カラム (Single column)
- [ ] **用紙サイズ:** Letter (8.5 x 11 in) または A4
- [ ] **ページ番号:** なし (SPIE側で付与されるため削除)
- [ ] **参考文献:** SPIEフォーマット準拠
    - `[Ref Number] A. Author, "Title," Journal Vol(Issue), Page (Year).`