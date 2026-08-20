# 株式会社abby コーポレートサイト

## 🌐 公開URL
- **プレビュー**: https://preview-99259f27-885b-43f2-b00a-0973f87928ef.gensparkspace.com
- **本番**: https://99259f27-885b-43f2-b00a-0973f87928ef.vip.gensparksite.com

## 📋 プロジェクト概要

株式会社abbyの公式コーポレートサイト。リユース事業と人材ソリューション事業を展開する企業のウェブサイトです。

### 🏢 事業内容
- **リユース事業**: ジュエリー・時計・ブランド品の買取・卸販売
- **人材ソリューション事業**: 営業支援・人材採用・教育

## 🎨 デザインコンセプト

- **ミニマルデザイン**: 0.5px極細ボーダー、font-weight: 300の統一感
- **タイポグラフィ**: Montserrat 900（ロゴ）、Noto Sans JP（本文）
- **カラースキーム**: 
  - メインカラー: #0f172a（濃紺）
  - アクセントカラー: #94a3b8（グレー）
  - 背景: #fafafa（オフホワイト）

## 📁 ファイル構成

```
.
├── index.html                    # 企業トップページ（タイピングアニメーション）
├── css/
│   ├── corporate.css            # トップページ用CSS
│   ├── sales-support.css        # 営業支援ページ用CSS
│   └── style.css                # リユース事業ページ用CSS
├── js/
│   ├── handwriting.js           # タイピングアニメーションJS
│   └── image-debug.js           # 画像デバッグ用
├── images/
│   ├── business-growth-team.png # 人材ソリューションイラスト
│   ├── reuse-consultation.png   # リユース事業イラスト
│   └── kpi-illustration.png     # KPIイラスト
├── sales-support/               # 営業支援ページディレクトリ
│   ├── index.html              # 営業支援トップ
│   ├── inquiry.html            # お問い合わせフォーム
│   ├── privacy.html            # プライバシーポリシー
│   └── tokusho.html            # 特定商取引法表記
└── reuse/                       # リユース事業ページディレクトリ
    └── index.html              # リユース事業トップ
```

## ✨ 主な機能・特徴

### 🎯 トップページ（index.html）
- **タイピングアニメーション**: 「abby」ロゴが1文字ずつ表示
- **スムーズスクロール**: セクション間の滑らかな移動
- **レスポンシブデザイン**: PC・タブレット・スマホ対応
- **統一されたボタン高さ**: Flexboxによるカード内ボタンの位置統一

### 📄 営業支援ページ（sales-support/）
- **サービス一覧**: 営業支援、組織立ち上げ、人材育成、KPI設計
- **対応業界**: IT・SaaS・通信・EC など12業界
- **選ばれる理由**: 3つの強み（一気通貫サポート、実績、柔軟対応）
- **お問い合わせフォーム**: Formspree連携、カスタムラジオボタン

### 📝 法的ページ
- **プライバシーポリシー**: 個人情報保護方針の詳細
- **特定商取引法表記**: 買取・卸販売の法的情報

## 🔧 技術スタック

- **HTML5**: セマンティックマークアップ
- **CSS3**: Flexbox、Grid、カスタムプロパティ
- **JavaScript (Vanilla)**: タイピングアニメーション、フォーム制御
- **Google Fonts**: Montserrat、Inter、Noto Sans JP
- **Font Awesome 6**: アイコンライブラリ
- **Formspree**: お問い合わせフォーム送信

## 🎨 デザイン統一要素

### フォント設定
```css
/* ロゴ */
font-family: 'Montserrat', sans-serif;
font-weight: 900;

/* 本文 */
font-family: 'Noto Sans JP', sans-serif;
font-weight: 300;

/* ボタン */
font-family: 'Noto Sans JP', sans-serif;
font-weight: 600;
```

### ボーダースタイル
```css
border: 0.5px solid #e5e7eb; /* 極細ボーダー */
```

### セクションタイトル
```css
font-size: 0.75rem;
text-transform: uppercase;
letter-spacing: 0.3em;
font-weight: 400;
```

## 📱 レスポンシブ対応

- **デスクトップ**: 1280px以上
- **タブレット**: 768px - 1279px
- **スマートフォン**: 767px以下

### ブレークポイント
```css
@media (max-width: 768px) {
  /* モバイル対応スタイル */
}
```

## 🚀 デプロイ方法

### プレビュー環境
```bash
# プレビューURLで即座に確認可能
https://preview-{project-id}.gensparkspace.com
```

### 本番環境
1. **Publishタブ**から公開
2. または **Hosted Deploy** を使用

## 📊 SEO設定

- **メタタグ**: description、keywords設定済み
- **OGP対応**: SNSシェア用のメタタグ
- **構造化データ**: セマンティックHTML5
- **sitemap.xml**: サイトマップ生成済み
- **robots.txt**: クローラー設定

## 📞 お問い合わせ先

- **電話**: 03-6416-3142（平日 9:00-20:00）
- **Email**: info@abby-inc.com
- **LINE**: @310qcqmq
- **Instagram**: @_abby0228_

## 📝 更新履歴

### 2026-08-20
- ✅ タイピングアニメーション実装
- ✅ 事業内容の順序変更（リユース → 人材ソリューション）
- ✅ 「人材派遣」「人材紹介」文言を「人材ソリューション」に統一
- ✅ ボタン高さ統一（Flexbox対応）
- ✅ フォント統一（Noto Sans JP 600）
- ✅ フッター統一デザイン
- ✅ お問い合わせフォーム改善
- ✅ 法的ページのタイポグラフィ統一

### 2026-08-07
- 初期リリース
- コーポレートサイト構築
- リユース事業・営業支援ページ作成

## 📄 ライセンス

© 2026 株式会社abby. All Rights Reserved.

## 🔗 関連リンク

- [会社概要](https://99259f27-885b-43f2-b00a-0973f87928ef.vip.gensparksite.com/#company)
- [営業支援サービス](https://99259f27-885b-43f2-b00a-0973f87928ef.vip.gensparksite.com/sales-support/)
- [リユース事業](https://99259f27-885b-43f2-b00a-0973f87928ef.vip.gensparksite.com/reuse/)
- [お問い合わせ](https://99259f27-885b-43f2-b00a-0973f87928ef.vip.gensparksite.com/sales-support/inquiry.html)
