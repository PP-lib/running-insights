# Running Insights

朝ランニングを生活設計の基盤にし、日々の練習・体調・気づき・仕事への転用アイデアを蓄積するためのリポジトリです。

> “We are what we repeatedly do. Excellence, then, is not an act, but a habit.”  
> — Aristotle に由来するとされる有名な要約表現

## 目的

- 朝ランニングの記録を継続する
- 練習内容と体調・集中力・仕事の成果を関連づける
- ランニング中の音声メモを後から整理し、実行可能なアクションに変換する
- 将来的に、週次・月次で振り返りできる知的ログにする

## 基本運用

1. 朝ラン後に `logs/YYYY/YYYY-MM-DD.md` を作成する
2. `templates/daily-run.md` をコピーして記録する
3. 気づきは小さくても残す
4. 週末に `reports/weekly/` にまとめる
5. 走行データを使う場合は `data/` に配置する

## ディレクトリ構成

```text
running-insights/
├── README.md
├── TEMPLATE.md
├── templates/
│   ├── daily-run.md
│   └── weekly-review.md
├── logs/
│   └── YYYY/
├── reports/
│   └── weekly/
├── data/
│   ├── raw/
│   └── processed/
└── docs/
    └── logging-guide.md
```

## 記録の考え方

完璧な記録より、継続できる記録を優先します。

ランニングは体力づくりだけでなく、思考整理・自己規律・仕事の判断力を高めるための“朝の研究所”として扱います。

## 今後の拡張案

- Strava / Garmin / Apple Health などのデータ取り込み
- Python による週次サマリー自動生成
- 距離・心拍・睡眠・集中度の相関分析
- Obsidian やブログへの自動連携
- GitHub Actions による週次レポート生成
