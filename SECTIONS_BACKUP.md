# 取扱商品・取扱ブランドセクションの再表示方法

このファイルには、現在非表示になっている「取扱商品」と「取扱ブランド」のセクションコードが保存されています。
写真が用意できたら、以下のコードを `index.html` の適切な位置に挿入してください。

---

## 📍 挿入位置

`<!-- Strength Section -->` の **直前**（サービス案内セクションの後）に挿入してください。

---

## 📄 取扱商品セクション (PRODUCTS)

```html
    <!-- Products Section -->
    <section class="section section-gray" id="products">
        <div class="container">
            <h2 class="section-title">PRODUCTS</h2>
            <p class="section-subtitle">取扱商品</p>
            
            <!-- Jewelry -->
            <div class="product-category">
                <h3 class="product-category-title">ジュエリー</h3>
                <div class="product-grid">
                    <div class="product-card">
                        <div class="product-image">
                            <!-- 👇 ここに実際の商品画像を設定 -->
                            <img src="images/jewelry-01.jpg" alt="BVLGARI ネックレス">
                        </div>
                        <h4 class="product-name">BVLGARI アストラーレ チェルキ ダイヤ ネックレス</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/jewelry-02.jpg" alt="BVLGARI リング">
                        </div>
                        <h4 class="product-name">BVLGARI ビーゼロワン ロック リング</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/jewelry-03.jpg" alt="Cartier ネックレス">
                        </div>
                        <h4 class="product-name">Cartier ダムール ダイヤ ネックレス</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/jewelry-04.jpg" alt="Van Cleef ピアス">
                        </div>
                        <h4 class="product-name">Van Cleef & Arpels フリヴォル ピアス</h4>
                    </div>
                </div>
            </div>

            <!-- Watch -->
            <div class="product-category">
                <h3 class="product-category-title">時計</h3>
                <div class="product-grid">
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/watch-01.jpg" alt="ROLEX デイトジャスト">
                        </div>
                        <h4 class="product-name">ROLEX デイトジャスト</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/watch-02.jpg" alt="OMEGA スピードマスター">
                        </div>
                        <h4 class="product-name">OMEGA スピードマスター</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/watch-03.jpg" alt="Cartier タンク">
                        </div>
                        <h4 class="product-name">Cartier タンク</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/watch-04.jpg" alt="PATEK PHILIPPE">
                        </div>
                        <h4 class="product-name">PATEK PHILIPPE カラトラバ</h4>
                    </div>
                </div>
            </div>

            <!-- Bag -->
            <div class="product-category">
                <h3 class="product-category-title">ブランドバッグ</h3>
                <div class="product-grid">
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/bag-01.jpg" alt="HERMES バーキン">
                        </div>
                        <h4 class="product-name">HERMES バーキン30</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/bag-02.jpg" alt="CHANEL マトラッセ">
                        </div>
                        <h4 class="product-name">CHANEL マトラッセ</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/bag-03.jpg" alt="LOUIS VUITTON">
                        </div>
                        <h4 class="product-name">LOUIS VUITTON ネヴァーフル</h4>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="images/bag-04.jpg" alt="GUCCI ディオニュソス">
                        </div>
                        <h4 class="product-name">GUCCI ディオニュソス</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>
```

---

## 📄 取扱ブランドセクション (BRANDS)

```html
    <!-- Brands Section -->
    <section class="section" id="brands">
        <div class="container">
            <h2 class="section-title">BRANDS</h2>
            <p class="section-subtitle">取扱ブランド</p>
            
            <h3 class="brand-category-title">ジュエリーブランド</h3>
            <div class="brand-grid">
                <div class="brand-card">Tiffany & Co.</div>
                <div class="brand-card">BVLGARI</div>
                <div class="brand-card">Cartier</div>
                <div class="brand-card">Van Cleef & Arpels</div>
                <div class="brand-card">HARRY WINSTON</div>
                <div class="brand-card">TASAKI</div>
            </div>

            <h3 class="brand-category-title">時計ブランド</h3>
            <div class="brand-grid">
                <div class="brand-card">ROLEX</div>
                <div class="brand-card">OMEGA</div>
                <div class="brand-card">PATEK PHILIPPE</div>
                <div class="brand-card">AUDEMARS PIGUET</div>
                <div class="brand-card">Cartier</div>
                <div class="brand-card">IWC</div>
                <div class="brand-card">BREITLING</div>
                <div class="brand-card">TAG Heuer</div>
                <div class="brand-card">ZENITH</div>
            </div>

            <h3 class="brand-category-title">バッグ・ファッションブランド</h3>
            <div class="brand-grid">
                <div class="brand-card">HERMES</div>
                <div class="brand-card">CHANEL</div>
                <div class="brand-card">LOUIS VUITTON</div>
                <div class="brand-card">GUCCI</div>
                <div class="brand-card">PRADA</div>
                <div class="brand-card">DIOR</div>
                <div class="brand-card">CELINE</div>
                <div class="brand-card">BOTTEGA VENETA</div>
                <div class="brand-card">FENDI</div>
            </div>

            <p class="brands-note">※上記以外のブランドも取り扱っております。お気軽にお問い合わせください。</p>
        </div>
    </section>
```

---

## 🔗 ナビゲーションリンクの追加

セクションを追加したら、以下のナビゲーションリンクも追加してください。

### ヘッダーナビゲーション
`index.html` の `<ul class="nav-menu">` 内に追加:

```html
<li><a href="#products">取扱商品</a></li>
<li><a href="#brands">取扱ブランド</a></li>
```

### フッターナビゲーション
フッターの「サービス」セクション内に追加:

```html
<li><a href="#products">取扱商品</a></li>
<li><a href="#brands">取扱ブランド</a></li>
```

---

## 📷 画像の設定方法

### 1. プレースホルダーを使う場合
CSSに既にプレースホルダースタイルが設定されています。
商品画像の代わりに `<div class="product-placeholder"></div>` を使用してください。

```html
<div class="product-image">
    <div class="product-placeholder"></div>
</div>
```

### 2. 実際の画像を使う場合
`images/` フォルダに画像を配置し、パスを指定してください。

```html
<div class="product-image">
    <img src="images/jewelry-01.jpg" alt="商品名">
</div>
```

---

## ✅ 再表示の手順

1. 写真を `images/` フォルダに配置
2. 上記のコードを `index.html` の適切な位置に挿入
3. 画像パスを実際のファイル名に変更
4. ナビゲーションリンクを追加
5. 公開して確認

---

**最終更新日**: 2026-03-14