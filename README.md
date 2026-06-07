# 🎵 AmbisonicsPlayer

ブラウザ上で動作する Ambisonics 再生 Web アプリケーションです。AmbiX / FuMa 形式の音源を読み込み、リスナーの向きを回転させながらステレオまたはバイノーラルにデコードして再生できます。

## バージョン

| バージョン | 説明 | リンク |
|-----------|------|--------|
| **Azimuth** | Yaw（左右方向）の回転のみ。シンプルで直感的な操作 | [▶ 開く](https://kagoiri.github.io/AmbisonicsPlayer/azimuth.html) |
| **Full** | Yaw / Pitch / Roll 全方向回転対応。クォータニオンベース | 🚧 未実装 |

## ドキュメント

- [Azimuth 版の使い方](README-azimuth.md)
- Full 版の使い方（未作成）

## 共通仕様

- **対応フォーマット**: AmbiX（ACN/SN3D）、FuMa
- **対応次数**: 1次〜3次（FOA/SOA/TOA: 4/9/16チャンネル）
- **デコードモード**: ステレオ / バイノーラル（HRTF 畳み込み）
- **ファイル形式**: WAV / MP3 / FLAC / OGG
- **動作環境**: HTTPS 環境 + モダンブラウザ（Chrome, Firefox, Edge, Safari）

## ライセンス

MIT License (Copyright (c) 2026 Kagoiri)
