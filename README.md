# Timelook

[![Latest Release](https://img.shields.io/github/v/release/yalkey/timelook-releases)](https://github.com/yalkey/timelook-releases/releases/latest)
[![License](https://img.shields.io/badge/license-Proprietary-blue)](#license)

> A free, ad-free, no-account-required time-tracking & life-logging app.
> 完全無料・広告なし・アカウント登録不要の時間管理アプリ。

---

## 🌐 Languages / 言語

- [日本語](#日本語)
- [English](#english)

---

## 日本語

### Timelook とは

毎日の行動を記録・見える化する時間管理アプリです。「自分が何にどれだけ時間を使っているのか」を正確に把握し、無駄な時間を減らして大切なことに集中できるようになることを目指しています。

### 主な機能

- 行動の記録（ストップウォッチ方式 / 手動入力）
- 円グラフ・棒グラフ・タイムテーブル・ヒートマップによる見える化
- 「理想の1日」と実績の比較
- 日記、目標積立時間、カウントダウン、実績（称号）
- Googleドライブによるクラウド同期・バックアップ
- 20言語対応

詳しい使い方はこちら 👉 **[Timelookの使い方（公式サイト）](https://yalkey.net/how-to-use-timelook-ja/)**

### 動作環境（Windows / Linux）

#### Windows

- Windows 10 / Windows 11（64bit）
- 約 200MB の空き容量

#### Linux

- 64bit Linux デスクトップ環境
- AppImage を実行できる環境
- AppImage が起動しない場合、FUSE 2 互換ライブラリが必要になることがあります

### ダウンロードとインストール

#### Windows

1. [Releases ページ](https://github.com/yalkey/timelook-releases/releases/latest) から最新版の `Timelook-x.x.x-win-x64.zip` をダウンロード
2. ZIP を任意の場所（例: `C:\Users\<あなたの名前>\Apps\Timelook\`）に展開
3. `timelook.exe` をダブルクリックして起動

> ⚠️ **SmartScreen の警告について**
> 初回起動時に「WindowsによってPCが保護されました」という警告が表示される場合があります。
> これは Microsoft のコード署名証明書を取得していないためで、ウイルス等ではありません。
>
> 「**詳細情報**」をクリック →「**実行**」をクリックすると起動できます。
> ご不安な方は VirusTotal などでファイルをスキャンしてからご利用ください。

#### Linux（AppImage）

1. [Releases ページ](https://github.com/yalkey/timelook-releases/releases/latest) から最新版の `Timelook-x.x.x-x86_64.AppImage` をダウンロード
2. AppImage に実行権限を付与

```bash
chmod +x Timelook-x.x.x-x86_64.AppImage
```

3. AppImage をダブルクリック、またはターミナルから起動

```bash
./Timelook-x.x.x-x86_64.AppImage
```

アプリメニューへの登録やタスクバーへのピン留めを行いたい場合は、`timelook-desktop-integration-vx.x.x+x.tar.gz` もダウンロードして、同梱の `README.md` に従ってインストールしてください。

AppImage が `libfuse.so.2` のエラーで起動しない場合は、FUSE 2 互換ライブラリをインストールしてください。Ubuntu 24.04 以降では、次のコマンドで解決する場合があります。

```bash
sudo apt-get install libfuse2t64
```

AppImage が利用できない環境向けに、`timelook-linux-x64-vx.x.x+x.tar.gz` も用意しています。展開後、`timelook` を実行してください。

### 新しいバージョンへの更新

#### Windows

1. Timelook を終了
2. [Releases ページ](https://github.com/yalkey/timelook-releases/releases/latest) から最新版の `Timelook-x.x.x-win-x64.zip` をダウンロード
3. ZIP を展開し、以前の Timelook アプリ本体フォルダを新しいファイルで置き換え
4. `timelook.exe` を起動

保存データはアプリ本体とは別の場所にあるため、通常はアプリ本体を置き換えても引き継がれます。下記の「データの保存場所」は削除しないでください。

#### Linux

1. Timelook を終了
2. [Releases ページ](https://github.com/yalkey/timelook-releases/releases/latest) から最新版の `Timelook-x.x.x-x86_64.AppImage` をダウンロード
3. 以前の AppImage と置き換え、必要に応じて実行権限を付与

```bash
chmod +x Timelook-x.x.x-x86_64.AppImage
```

4. デスクトップ連携を使っている場合は、最新版の `timelook-desktop-integration-vx.x.x+x.tar.gz` に含まれるインストールスクリプトをもう一度実行

tar.gz 版を使っている場合は、最新版の `timelook-linux-x64-vx.x.x+x.tar.gz` を展開し、以前のアプリ本体フォルダを新しいフォルダで置き換えてください。保存データはアプリ本体とは別のユーザーデータ領域に保存されるため、通常は引き継がれます。

### データの保存場所

行動記録などのデータは以下に保存されます：

```
C:\Users\<あなたのユーザー名>\Documents\yalkey\Timelook\
```

アンインストール時に削除されないため、アプリを再インストールしてもデータは引き継がれます。

Linux でも保存データは AppImage や展開したアプリ本体の中ではなく、ユーザーのデータ領域に保存されます。アプリを更新する際は、AppImage や展開したアプリ本体のみを置き換えてください。

### お問い合わせ・不具合の報告

- ブログ: https://yalkey.net/
- お問い合わせ: https://yalkey.net/contact/
- X (Twitter): [@yalkey_official](https://x.com/yalkey_official)

---

## English

### What is Timelook

Timelook is a time-management app that records and visualizes your daily activities. It helps you understand exactly how you spend your time, reduce wasted time, and focus on what matters most.

### Features

- Activity recording (stopwatch & manual entry)
- Visualization with pie charts, bar charts, timetables, and heatmaps
- Compare your "Ideal Day" with actual activities
- Diary, goal quotas, countdown, achievements (titles)
- Google Drive cloud sync & backup
- 20 supported languages

📖 Full user guide: **[How To Use Timelook (Official Site)](https://yalkey.net/how-to-use-timelook-en/)**

### System Requirements (Windows / Linux)

#### Windows

- Windows 10 / Windows 11 (64-bit)
- ~200 MB free disk space

#### Linux

- 64-bit Linux desktop environment
- Environment capable of running AppImage files
- A FUSE 2 compatibility library may be required if the AppImage does not start

### Download & Install

#### Windows

1. Go to the [Releases page](https://github.com/yalkey/timelook-releases/releases/latest) and download the latest `Timelook-x.x.x-win-x64.zip`
2. Extract the ZIP to any location (e.g., `C:\Users\<your-name>\Apps\Timelook\`)
3. Double-click `timelook.exe` to launch

> ⚠️ **About the SmartScreen warning**
> On first launch, Windows may show "Windows protected your PC".
> This appears because the app is not signed with a Microsoft code-signing certificate. It does **not** mean the app contains malware.
>
> Click **More info** → **Run anyway** to start the app.
> If you're concerned, feel free to scan the file with VirusTotal first.

#### Linux (AppImage)

1. Go to the [Releases page](https://github.com/yalkey/timelook-releases/releases/latest) and download the latest `Timelook-x.x.x-x86_64.AppImage`
2. Make the AppImage executable

```bash
chmod +x Timelook-x.x.x-x86_64.AppImage
```

3. Double-click the AppImage, or launch it from a terminal

```bash
./Timelook-x.x.x-x86_64.AppImage
```

To add Timelook to your application menu or pin it to the taskbar, also download `timelook-desktop-integration-vx.x.x+x.tar.gz` and follow the included `README.md`.

If the AppImage does not start because of a `libfuse.so.2` error, install the FUSE 2 compatibility library. On Ubuntu 24.04 or later, this may fix it:

```bash
sudo apt-get install libfuse2t64
```

For environments where AppImage is not suitable, `timelook-linux-x64-vx.x.x+x.tar.gz` is also available. Extract it and run `timelook`.

### Updating to a New Version

#### Windows

1. Quit Timelook
2. Download the latest `Timelook-x.x.x-win-x64.zip` from the [Releases page](https://github.com/yalkey/timelook-releases/releases/latest)
3. Extract the ZIP and replace the previous Timelook application files with the new files
4. Launch `timelook.exe`

Your data is stored outside the application files, so it is usually preserved when you replace the app. Do not delete the data folder listed below.

#### Linux

1. Quit Timelook
2. Download the latest `Timelook-x.x.x-x86_64.AppImage` from the [Releases page](https://github.com/yalkey/timelook-releases/releases/latest)
3. Replace the previous AppImage and make it executable if needed

```bash
chmod +x Timelook-x.x.x-x86_64.AppImage
```

4. If you use desktop integration, run the install script included in the latest `timelook-desktop-integration-vx.x.x+x.tar.gz` again

If you use the tar.gz package, extract the latest `timelook-linux-x64-vx.x.x+x.tar.gz` and replace only the previous application folder. Your data is stored in the user's data area outside the application files, so it is usually preserved.

### Data Location

Your records are stored in:

```
C:\Users\<your-username>\Documents\yalkey\Timelook\
```

This folder is preserved across reinstalls, so your data persists.

On Linux, saved data is stored in the user's data area, not inside the AppImage or extracted application folder. When updating the app, replace only the AppImage or extracted application files.

### Contact & Bug Reports

- Blog: https://yalkey.net/
- Contact: https://yalkey.net/contact/
- X (Twitter): [@yalkey_official](https://x.com/yalkey_official)

---

## License

© yalkey. All rights reserved.

This software is distributed as a freeware binary. The source code is **not** included in this repository. Redistribution of the binary without permission is prohibited.

---

## Privacy

- [プライバシーポリシー (日本語)](https://yalkey.net/privacy-policy-timelook/)
- [Privacy Policy (English)](https://yalkey.net/privacy-policy-timelook-en/)
