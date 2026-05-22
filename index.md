---
title: FitForce プライバシーポリシー
layout: default
---

# FitForce プライバシーポリシー

**最終更新日: 2026年5月22日**

FitForce（以下「本アプリ」）は、ユーザーのプライバシーを尊重します。本ポリシーは、本アプリが扱うデータの種類、利用目的、端末内保存、外部サービスへの送信、第三者処理、保持、削除、同意撤回について説明します。

## 1. 取得・保存するデータ

本アプリは、以下のデータを iOS 標準の SwiftData / UserDefaults を用いて **利用者の端末内** に保存します。当社が運営するサーバーへの保管は行いません。

- 食事記録（食品名、カロリー、PFC値、食事写真）
- 筋トレ記録（種目、セット数、重量、回数）
- 体重、身長、性別、年齢、目標体重などのプロフィール
- 有酸素運動・スポーツ活動記録
- ユーザー設定（テンプレート、お気に入り、AI送信同意状態など）

これらの端末内データは、アプリをアンインストールすると端末から削除されます。

## 2. ヘルスケアデータ

本アプリは、ユーザーの明示的な許可がある場合に限り、Appleヘルスケアから以下のデータを読み取ります。

- 体重
- 歩数
- アクティブカロリー

また、ユーザーがアプリ内で記録した体重をAppleヘルスケアへ書き込む場合があります。これらのデータは、体重グラフ、当日の消費カロリー表示、食事・運動管理のために使用します。ヘルスケアへのアクセス許可は、iOSの「設定」またはヘルスケアアプリからいつでも変更できます。

## 3. Google Gemini APIへのデータ送信

本アプリは、AI解析・AI提案機能を提供するために、Google社の **Gemini API** にデータを送信する場合があります。AI機能を利用する前に、アプリ内でAIへのデータ送信について確認します。ユーザーが同意しない場合、AI機能は利用できません。

| 機能 | Gemini APIへ送信される可能性があるデータ | 利用目的 |
|---|---|---|
| 食事写真AI解析 | 撮影または選択された食事画像 | 食品名、量、カロリー、PFC値の推定 |
| 足りない栄養の補助提案 | 食事画像、残りカロリー、残りPFC目標 | 追加候補食品の提案 |
| AIメニュー生成 | 体重、身長、年齢、性別、目標、トレーニング条件 | ワークアウトメニューの生成 |
| AI食事レビュー | 食事記録、推定栄養値、目標カロリー、目標PFC | 食事内容の一般的なレビュー |
| AI筋トレ評価・週次レビュー | 筋トレ記録、食事記録、体重推移、プロフィール由来の情報 | 運動・食事・体重推移の一般的なレビュー |

送信されるデータには、氏名、メールアドレス、電話番号、連絡先、位置情報、広告識別子（IDFA）は含めません。ただし、食事写真、健康・フィットネス記録、プロフィール由来の情報は、ユーザーの健康管理に関する機微な情報を含む場合があります。

Gemini APIへの通信はHTTPSで暗号化されます。本アプリは、Gemini APIへ送信したデータを当社サーバーに保存しません。

## 4. Googleによる第三者処理・保持

Gemini APIに送信されたプロンプト、画像、追加文脈、生成結果などは、Google社により処理されます。Google社は、Gemini APIの安全性とポリシー遵守のため、不正利用対策・ポリシー執行・法令対応の目的で、プロンプト、文脈情報、生成出力を一定期間保持する場合があります。

Google社のGemini APIドキュメントでは、不正利用対策のためにこれらのデータを **55日間保持** する場合があること、フラグされた内容は権限を持つGoogle担当者が確認する場合があること、また不正利用対策のためにログされたデータは、ポリシー執行および違反防止の目的で使用され、ポリシー執行用のモデルを除きAI/MLモデルのトレーニングまたはファインチューニングには使用されないことが説明されています。

また、GoogleのGemini APIログ共有機能でプロジェクト所有者が任意にログ共有へオプトインした場合、APIリクエスト・レスポンス等がGoogle製品や機械学習技術の改善・評価・トレーニングに使用される場合があります。FitForceでは、ユーザーの健康・食事・運動データを含むGemini APIログを、モデル改善目的でGoogleへ任意共有しない運用とします。

Google社による処理、保持、削除、法令対応の詳細は、GoogleのポリシーおよびGemini API関連ドキュメントをご確認ください。

- [Google プライバシーポリシー](https://policies.google.com/privacy)
- [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms)
- [Gemini API Abuse monitoring](https://ai.google.dev/gemini-api/docs/usage-policies#how-we-handle-data)
- [Gemini API Data Logging and Sharing](https://ai.google.dev/gemini-api/docs/logs-policy)

## 5. AI送信への同意と撤回

AI機能を初めて利用する前に、本アプリはGoogle Gemini APIへ送信されるデータの概要を表示し、ユーザーの同意を確認します。同意後は、プロフィール画面の「法務・プライバシー」セクションから「AIへのデータ送信を許可」をオフにすることで、将来のAI送信を撤回できます。

同意を撤回すると、食事写真AI解析、足りない栄養の補助提案、AI食事レビュー、AI筋トレ評価、週次AIレビューなど、Gemini APIへの送信を伴う機能は利用前に再確認されます。撤回は将来の送信を停止するものであり、撤回前にGemini APIへ送信済みのデータについては、Google社の保持・削除ポリシーに従って処理されます。

## 6. カメラ・フォトライブラリ、バーコード検索

本アプリは、食事写真の記録、食事写真AI解析、バーコードスキャンのために、ユーザーの許可に基づいてカメラおよびフォトライブラリへアクセスします。アクセス許可はiOSの「設定」からいつでも変更できます。撮影または選択された食事写真は、端末内保存およびAI解析のために使用される場合があります。

バーコード検索機能を利用する場合、本アプリはスキャンしたバーコード番号をOpen Food Factsへ送信し、食品名や栄養成分情報を取得します。本アプリおよび当社が運営するサーバーには、バーコード検索リクエストを保存しません。Open Food Facts側での処理、通信ログ、保持は同サービスのポリシーに従います。バーコード検索を利用せず、食品名や栄養成分を手動で入力することもできます。

## 7. 第三者への提供

本アプリは、AI解析・AI提案の処理目的でGoogle社のGemini APIへデータを送信する場合、およびバーコード検索のためにバーコード番号をOpen Food Factsへ送信する場合を除き、ユーザーのデータを第三者へ販売、共有、提供しません。広告目的のトラッキング、第三者広告ネットワーク、外部アナリティクスSDKは使用していません。

## 8. 取得しないデータ

本アプリは以下のデータを取得しません。

- 氏名
- メールアドレス
- 電話番号
- 位置情報
- 連絡先
- カレンダー
- 広告識別子（IDFA）
- 第三者広告目的のトラッキング情報

## 9. データの削除

端末内に保存されたデータは、アプリをアンインストールすることで削除されます。アプリ内の記録は、各画面の削除機能またはバックアップ復元機能により変更・削除できる場合があります。

Gemini APIへ送信済みのデータは、本アプリまたは当社サーバーには保存されませんが、Google社が上記の不正利用対策・ポリシー執行・法令対応のために一定期間保持する場合があります。Google社側の保持・削除はGoogleのポリシーに従います。

## 10. 子供のプライバシー

本アプリは13歳未満の児童を対象としていません。13歳未満の児童の個人情報を意図的に収集することはありません。

## 11. ポリシーの変更

本ポリシーは、機能追加、法令・プラットフォーム要件、外部サービスの仕様変更に応じて更新される場合があります。重要な変更がある場合は、本アプリの更新時またはアプリ内表示により通知します。

## 12. お問い合わせ

本ポリシーまたは本アプリに関するお問い合わせは、以下までご連絡ください。

- メール: jiuyejiang3@gmail.com

---

# Privacy Policy (English)

**Last updated: May 22, 2026**

FitForce (the "App") respects your privacy. This policy explains what data the App handles, how it is used, what is stored locally, what may be sent to external services, third-party processing, retention, deletion, and withdrawal of consent.

## 1. Data Stored Locally

The App stores the following data **on your device** using iOS SwiftData / UserDefaults. We do not store this data on servers operated by us.

- Meal records (food names, calories, PFC values, meal photos)
- Workout records (exercises, sets, weight, reps)
- Profile data such as weight, height, sex, age, and target weight
- Cardio / sports activity records
- App settings such as templates, favorites, and AI data sharing consent status

Locally stored data is removed from your device when you uninstall the App.

## 2. Health Data

With your explicit permission, the App may read the following data from Apple Health:

- Body weight
- Step count
- Active energy burned

The App may also write body weight records that you enter in the App to Apple Health. These data are used for weight charts, active calorie display, and meal/workout management. You can change Health permissions at any time in iOS Settings or the Health app.

## 3. Data Sent to Google Gemini API

The App may send data to Google's **Gemini API** to provide AI analysis and suggestion features. Before using AI features, the App displays a notice about AI data sharing. If you do not consent, AI features cannot be used.

| Feature | Data that may be sent to Gemini API | Purpose |
|---|---|---|
| Meal photo AI analysis | Selected or captured meal images | Estimating food names, amounts, calories, and PFC values |
| Nutrition complement suggestions | Meal image, remaining calorie target, remaining PFC targets | Suggesting additional foods |
| AI workout menu generation | Weight, height, age, sex, goals, training preferences | Generating workout menus |
| AI meal review | Meal records, estimated nutrition values, calorie target, PFC targets | General review of meal records |
| AI workout / weekly review | Workout records, meal records, weight trends, profile-derived information | General review of workout, meal, and weight trends |

We do not intentionally include your name, email address, phone number, contacts, location, or advertising identifier (IDFA) in data sent to Gemini API. However, meal photos, health/fitness records, and profile-derived information may include sensitive information about your health and fitness management.

Communication with Gemini API is encrypted via HTTPS. We do not store data sent to Gemini API on our own servers.

## 4. Third-Party Processing and Retention by Google

Prompts, images, contextual information, and generated outputs sent to Gemini API are processed by Google. Google may retain prompts, contextual information, and generated outputs for abuse monitoring, policy enforcement, safety, security, and legal or regulatory purposes.

Google's Gemini API documentation states that such data may be retained for **55 days** for abuse monitoring, that flagged content may be reviewed by authorized Google personnel, and that data logged for abuse monitoring is used solely for policy enforcement and preventing policy violations and is not used to train or fine-tune AI/ML models other than those specifically used for policy enforcement.

If a project owner opts in to Gemini API log sharing, API requests and responses may be used by Google to improve, evaluate, or train Google products, services, and machine learning technologies. FitForce does not opt in to sharing Gemini API logs containing users' health, meal, or workout data for model improvement.

For details about Google's processing, retention, deletion, and legal obligations, please refer to Google's policies and Gemini API documentation:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms)
- [Gemini API Abuse monitoring](https://ai.google.dev/gemini-api/docs/usage-policies#how-we-handle-data)
- [Gemini API Data Logging and Sharing](https://ai.google.dev/gemini-api/docs/logs-policy)

## 5. Consent and Withdrawal for AI Data Sending

Before you use an AI feature for the first time, the App shows a summary of the data that may be sent to Google Gemini API and asks for your consent. After consenting, you can withdraw future AI data sending by turning off "Allow AI data sending" in the "Legal & Privacy" section of the Profile screen.

Withdrawing consent stops future sending unless you confirm again before using an AI feature. It does not delete data that was already sent to Gemini API before withdrawal; such data is handled according to Google's retention and deletion policies.

## 6. Camera, Photo Library, and Barcode Lookup

The App requests camera and photo library access for meal photo recording, meal photo AI analysis, and barcode scanning. You can change access permissions at any time in iOS Settings. Selected or captured meal photos may be used for local storage and AI analysis.

When you use barcode lookup, the App sends the scanned barcode number to Open Food Facts to retrieve the product name and nutrition facts. We do not store barcode lookup requests on servers operated by us. Processing, communication logs, and retention by Open Food Facts are governed by Open Food Facts' own policies. You can avoid barcode lookup and enter food names and nutrition values manually.

## 7. Third-Party Sharing

We do not sell, share, or provide user data to third parties except for sending data to Google's Gemini API for AI analysis and suggestion processing, and sending barcode numbers to Open Food Facts for barcode lookup. We do not use advertising tracking, third-party ad networks, or external analytics SDKs.

## 8. Data Not Collected

The App does not collect:

- Name
- Email address
- Phone number
- Location
- Contacts
- Calendar
- Advertising identifier (IDFA)
- Tracking information for third-party advertising

## 9. Data Deletion

Locally stored data is deleted when you uninstall the App. In-app records may also be modified or deleted through available App features.

Data already sent to Gemini API is not stored by us or on our servers, but Google may retain it for abuse monitoring, policy enforcement, safety, security, and legal or regulatory purposes as described above. Google's retention and deletion policies apply to Google's processing.

## 10. Children's Privacy

The App is not directed at children under 13. We do not knowingly collect personal information from children under 13.

## 11. Changes to This Policy

This policy may be updated due to feature changes, legal or platform requirements, or changes in external service practices. Significant changes will be communicated through App updates or in-app notices.

## 12. Contact

For questions about this policy or the App:

- Email: jiuyejiang3@gmail.com
