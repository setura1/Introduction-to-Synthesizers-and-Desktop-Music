# MIDI Synth Lab

GitHub Pagesでそのまま公開できる、静的HTML/CSS/JavaScriptのみの学習アプリです。

## 入っている機能

- Web Audio APIによる簡易シンセ
- Web MIDI APIによるMIDI鍵盤入力
- `.mid` / `.midi` の読込
- 読み込んだノート列のピアノロール表示
- 波形表示
- FFT表示
- 現在の音色でMIDI再生

## ファイル構成

- `index.html`
- `style.css`
- `app.js`

## GitHub Pagesへの置き方

1. 新しいリポジトリを作る
2. この3ファイルをルートに置く
3. GitHubの Settings → Pages を開く
4. Branch を `main`、Folder を `/ (root)` にする
5. 保存後、公開URLで開く

## 注意

- Web Audioは最初に `Audio開始` を押す必要があります
- Web MIDI APIはブラウザ差があります。Chrome系で試すのが無難です
- MIDIファイルは標準的なノートイベント中心のものを想定しています
- Tempo change には対応していますが、System Exclusive など高度なイベントは学習用途向けの簡易処理です

## 追加しやすい拡張

- 複数トラック個別再生
- ベロシティ編集
- クオンタイズ
- MIDI書き出し
- ステップシーケンサー
- エフェクト追加
