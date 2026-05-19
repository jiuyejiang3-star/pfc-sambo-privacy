# FitForce プライバシーポリシー

**最終更新日: 2026年5月19日**

FitForce（以下「本アプリ」）は、ユーザーのプライバシーを最大限尊重します。本ポリシーは、本アプリが扱うデータの種類、利用目的、第三者への提供の有無について説明します。

## 1. 取得・保存するデータ

本アプリは、以下のデータを **すべて利用者の端末内** に保存します。サーバーへの送信・保管は行いません。

- 食事記録（写真・食品名・カロリー・PFC値）
- 筋トレ記録（種目・セット数・重量・回数）
- 体重・身長・性別・年齢などのプロフィール
- 有酸素運動・スポーツ活動記録
- ユーザー設定（テンプレート・お気に入りなど）

これらのデータは iOS 標準の SwiftData / UserDefaults を用いて端末内にローカル保存されます。アプリをアンインストールするとすべて削除されます。

## 2. 外部サービスへのデータ送信

本アプリは、以下の機能のために Google 社の **Gemini API** にデータを送信します。

| 機能 | 送信されるデータ |
|---|---|
| 食事写真の栄養解析 | 撮影/選択された食事画像 |
| AIメニュー生成 | 体重・身長・年齢・性別・トレーニング条件 |
| AI評価・週次レビュー | 食事記録・筋トレ記録・体重推移の集計値 |

- 送信されるデータには、氏名・メールアドレス・電話番号などの **個人を特定する情報は一切含まれません**
- 通信は HTTPS により暗号化されます
- Gemini API の利用は Google 社の[プライバシーポリシー](https://policies.google.com/privacy)に従います

## 3. 取得しないデータ

本アプリは以下のデータを **一切取得しません**。

- 氏名・メールアドレス・電話番号
- 位置情報
- 連絡先
- カレンダー
- 端末識別子（IDFA等）
- 利用状況の分析データ（アナリティクス）
- 広告識別子・トラッキング情報

## 4. カメラ・フォトライブラリへのアクセス

食事写真の記録のために、ユーザーの許可に基づいてカメラおよびフォトライブラリにアクセスします。許可は iOS 設定からいつでも変更可能です。撮影/選択された写真は、栄養解析のためにのみ Gemini API へ送信され、本アプリのサーバーには保存されません。

## 5. 第三者への提供

本アプリは、ユーザーのデータを Google 社の Gemini API（解析処理目的）以外の第三者に提供することはありません。

## 6. データの削除

本アプリをアンインストールすることで、端末内に保存されたすべてのデータが完全に削除されます。

## 7. 子供のプライバシー

本アプリは13歳未満の児童を対象としていません。13歳未満の児童の個人情報を意図的に収集することはありません。

## 8. ポリシーの変更

本ポリシーは予告なく変更される場合があります。重要な変更がある場合は、本アプリの更新時に通知します。

## 9. お問い合わせ

本ポリシーまたは本アプリに関するお問い合わせは、以下までご連絡ください。

- メール: jiuyejiang3@gmail.com

---

# Privacy Policy (English)

**Last updated: May 19, 2026**

FitForce (the "App") respects your privacy. This policy explains what data the App handles, how it is used, and whether it is shared with third parties.

## 1. Data Stored Locally

All of the following data is stored **only on your device**. It is never uploaded to our servers.

- Meal records (photos, food names, calories, PFC values)
- Workout records (exercises, sets, weight, reps)
- Profile (weight, height, sex, age)
- Cardio / sports activity records
- App settings

Uninstalling the App permanently deletes all data.

## 2. Data Sent to External Services

The App sends data to Google's **Gemini API** for meal photo analysis, AI menu generation, and AI evaluation/weekly review. **No personally identifiable information** (name, email, phone) is sent. All communication is encrypted via HTTPS.

## 3. Data NOT Collected

Name, email, phone, location, contacts, calendar, device identifiers, usage analytics, advertising/tracking identifiers — all not collected.

## 4. Camera & Photo Library Access

The App requests camera and photo library access for meal photo recording only. Photos are sent to the Gemini API for nutrition analysis and are not stored on our servers.

## 5. Third-Party Sharing

We do not share data with any third party other than the Gemini API for processing.

## 6. Data Deletion

Uninstalling the App permanently deletes all locally stored data.

## 7. Children's Privacy

The App is not directed at children under 13.

## 8. Changes to This Policy

This policy may be updated without notice. Significant changes will be communicated through App updates.

## 9. Contact

For questions: jiuyejiang3@gmail.com
