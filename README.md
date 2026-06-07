# JongPilot — Legal Documents

[JongPilot](https://github.com/CitrusWorks) (麻雀 AI コーチ) の **利用規約** と **プライバシーポリシー** を公開する GitHub Pages リポジトリ。

## 公開 URL

プラットフォーム別の 4 ドキュメント構成:

| プラットフォーム | プライバシーポリシー | 利用規約 |
|---|---|---|
| Android | <https://citrusworks.github.io/JongPilot/android/privacy/> | <https://citrusworks.github.io/JongPilot/android/terms/> |
| iOS | <https://citrusworks.github.io/JongPilot/ios/privacy/> | <https://citrusworks.github.io/JongPilot/ios/terms/> |

ランディング (両プラットフォーム選択): <https://citrusworks.github.io/JongPilot/>

これらの URL は Google Play Console (Android URL) / App Store Connect (iOS URL) のアプリリスティング欄にそれぞれ登録します。

## 構成

```
android/
  privacy.md     ← /android/privacy/ で公開、Android 固有用語 (root / Play Store)
  terms.md       ← /android/terms/
ios/
  privacy.md     ← /ios/privacy/ で公開、iOS 固有用語 (jailbreak / App Store)
  terms.md       ← /ios/terms/
index.md         ← / ランディング、両プラットフォームへのリンク
_config.yml      ← Jekyll 設定
_layouts/        ← custom layout
```

## 内容の正本

| 媒体 | 役割 |
|---|---|
| 本リポジトリ (= GitHub Pages) | **公開正本**。Google Play / App Store にも同じ URL を登録 |
| `mahjong_ai_app/docs/{android,ios}/*.md` (= private repo) | 推敲・レビュー用 planning doc、本リポジトリと同期 |

アプリ内では `BrandConfig` が `Platform.isAndroid` / `isIOS` で URL を**動的切替**し、起動端末に合致する URL を OS ブラウザで開く設計 (= Pattern A)。

## ライセンス

本リポジトリの内容は JongPilot の規約・ポリシーであり、開発者 (citrus works) に帰属します。複製・再配布はご遠慮ください。

---

© 2026 citrus works. All rights reserved.
