﻿## 方針や目的
- ~~チャットツールは報告作業に用いられるが、タスク整理（Todo担当者変更）やファイル修正は別ツールでしか行えない~~
  - ~~結局、一連の作業工程を実施するのに、複数ツールを使うことになる。~~
  - ~~煩雑~~
~~それを、チャットツール上で完結したい＆他ツールとの互換性を高めたい~~

- 業務向けやサイボウズと連携するチャットツールは、Slackで実現する方が<br>良さそうなので方針転換
- チャット形式のゲームを開発することで、対話型の遊びを提供できるような<br>アプリにする方向に
  - まずは1つの機能（ゲーム）を実装してみて、完成したら拡張していく開発方針

## 使用形態
PCブラウザ（第一フェーズ）

## 要件
### コンテンツ内容
- 言葉の椅子取りゲーム
  - ゲームに必要な情報
     → 人数
     → 言葉
     → 難易度設定（言葉の長さ）
### 機能
- ログイン機能どうする？
→ 今回は不要（2019-09-28）
- 任意のURLを入力してもらうことで、チャットルームを生成する
→そのチャットルーム内で、「言葉の椅子取りゲーム」

## 開発環境
OS：Windows
開発ツール：Visual Studio Code 1.38

データベース：Mysql 8.0.17

サーバー：VirtualBox
　　　　　
          Apache2

言語：Python 3.7.4


