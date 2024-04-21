# like_a_select_shop

```
https://hashsan.github.io/like_a_select_shop/
```

```
お取り扱いブランドについて、dl,dt,ddで書く。
https://affiliate.rakuten.co.jp/recommend/major/?l-id=af_header_search_04
```
```
ｔｉｔｉｖａｔｅ
ダブルスタンダードクロージング直営公式オンライン【Night STORE】（12-0920）
女性に大人気！リピータ多数！☆DHOLIC☆【ディーホリック-】(22-1214)
ＲＯＡＤＧＥＴ＿ＢＵＳＩＮＥＳＳ＿ＰＴＥ．ＬＴＤ．
セレブワンピース＆ドレスの【Pour Vous（プール・ヴー）】（14-0522）
キャバドレス激安通販【dazzystore】(22-0606)
雑誌掲載や有名モデル着用アイテムなど随時入荷中！【Pierrot】(16-1212)
およばれドレス　Dorry Doll(22-0715)
韓国の代表的な10代・20代女性のファッション通販【SONA】(22-0929)
シルク & カシミアの衣料品・ホームウエア【LILYSILK】(23-0825)
ファッション通販「SHOPLIST.com by CROOZ」（12-1107）
20〜30代女性に最も使われているファッションレンタルアプリ【メチャカリ】(21-0908)
オケージョンドレスショップ【 ANDRESD -アンドレスド】(23-0614)
【雑誌・ファッションショー出展】韓国発アパレルブランド|SELCA（セルカ）(23-1018)
【ドレスブランド-haremode-】結婚式お呼ばれコーデが3万円以下で揃う!(23-1227)
何枚でも欲しくなるカジュアルアイテムが豊富！華やかドレスも【GIRL】(15-1007)
オケージョンドレス 購入とレンタルが選べるブランド【&Robu. アンドロブ】(23-1212)
世界中の女性に愛されるブランドaxes femme【アクシーズファム 】(23-1128)
バストアップ専門サロン発ナイトブラ【PG-Bra】(19-1129)
```
```
商品データをグーグルに送信
https://developers.google.com/search/docs/appearance/structured-data/product?hl=ja
```
```
構造化データについて
https://blog.8bit.co.jp/?p=15373
```
```
グーグルサーチコンソール
https://search.google.com/search-console?resource_id=https://hashsan.github.io/nenreiga/
```

```
スキーマorgは知ってるかい？
ChatGPT
はい、スキーマ.orgは、ウェブページの構造化データを記述するためのマークアップ形式であるSchema.orgのことですね。これは検索エンジンがウェブページのコンテンツを理解しやすくするための手段として広く使用されています。具体的には、Schema.orgを使用することで、製品、イベント、組織、レシピなどのさまざまな種類の情報を構造化して表現することができます。これにより、検索エンジンがコンテンツをより正確に解釈し、適切な検索結果に表示することができるようになります。

商品をそのマークアップにそって記述したいんだ。
ChatGPT
素晴らしいですね！商品情報をSchema.orgのマークアップに従って記述することで、検索エンジンがその情報を理解しやすくなり、より適切な検索結果に表示される可能性が高まります。具体的な商品情報を含めることで、消費者が検索結果から直接必要な情報を得ることができます。

たとえば、商品の名称、画像、価格、説明、ブランド、製造元などの情報をSchema.orgのマークアップに含めることができます。この情報は、商品のタイプや属性に基づいて適切なプロパティに対応するSchema.orgのスキーマを使用して構造化します。

具体的な例を示すために、次のようなJSON-LD形式のSchema.orgのマークアップを見てみましょう。ここでは、スマートフォンの商品情報を記述しています。

json
Copy code
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "スマートフォン",
  "image": "https://example.com/photos/123.jpg",
  "description": "高性能なスマートフォンです。",
  "brand": {
    "@type": "Brand",
    "name": "Example Brand"
  },
  "offers": {
    "@type": "Offer",
    "price": "100000",
    "priceCurrency": "JPY",
    "availability": "https://schema.org/InStock"
  }
}
</script>
この例では、スマートフォンの商品情報を記述しています。nameには商品名、imageには商品の画像URL、descriptionには商品の説明、brandには商品のブランド情報、offersには価格や在庫情報が含まれています。

商品の具体的な属性に合わせて、適切なSchema.orgのプロパティを使用して情報を記述してください。このようなマークアップをウェブページに追加することで、検索エンジンが商品情報を正確に理解し、適切な検索結果に表示されるようになります。

この場合は、ひとつの商品だけだよね
ChatGPT
そうですね、この例では1つの商品の情報を示しています。もし複数の商品情報を含むページをマークアップする場合、それぞれの商品に関する情報を個別にマークアップする必要があります。

複数の商品情報を含む場合、それぞれの商品情報を独立して記述する必要があります。例えば、複数の商品をリスト形式で表示する場合、それぞれの商品の情報に対して個別のSchema.orgのマークアップを追加します。

以下は複数の商品情報を含む場合の例です。

json
Copy code
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ItemList",
  "itemListElement": [
    {
      "@type": "Product",
      "name": "商品1",
      "image": "https://example.com/photos/1.jpg",
      "description": "商品1の説明",
      "brand": {
        "@type": "Brand",
        "name": "Example Brand"
      },
      "offers": {
        "@type": "Offer",
        "price": "5000",
        "priceCurrency": "JPY",
        "availability": "https://schema.org/InStock"
      }
    },
    {
      "@type": "Product",
      "name": "商品2",
      "image": "https://example.com/photos/2.jpg",
      "description": "商品2の説明",
      "brand": {
        "@type": "Brand",
        "name": "Example Brand"
      },
      "offers": {
        "@type": "Offer",
        "price": "8000",
        "priceCurrency": "JPY",
        "availability": "https://schema.org/InStock"
      }
    }
  ]
}
</script>
この例では、2つの商品情報が含まれています。各商品情報は独立して記述されており、それぞれの商品の名前、画像、説明、価格、ブランドなどが含まれています。

InStockというのは？
ChatGPT
"availability"プロパティにおける"InStock"は、商品の在庫状況を示す値です。具体的には、"InStock"は商品が在庫ありであることを示します。この値は、Schema.orgの「商品オファー」のマークアップで使用され、商品の在庫状況を検索エンジンに伝えるのに役立ちます。

他にも、「availability」プロパティには、商品が在庫切れであることを示す "OutOfStock" や、予約受付中であることを示す "PreOrder" などの値も存在します。これらの値を使用することで、検索エンジンはユーザーに正確な商品の在庫状況を表示することができます。

この情報は、実際のhtmlと違っていてもいいのかい？
ChatGPT
はい、Schema.orgのマークアップはHTMLとは独立しています。つまり、実際のHTMLの構造とは無関係に、JSON-LD形式でSchema.orgのマークアップを追加することができます。

JSON-LDは、HTML文書内の <script> タグ内に埋め込まれ、検索エンジンや他のウェブサービスにウェブページの構造化データを提供します。このため、実際のHTMLの構造を変更する必要はありません。

これにより、ウェブページの表示やスタイルに影響を与えることなく、検索エンジンがページのコンテンツを理解しやすくなります。そのため、Schema.orgのマークアップを追加する際には、HTMLの構造やスタイルに影響を与えることなく、ウェブページの構造化データを追加することができます。

商品の要素にタグの項目はないのかい？
ChatGPT
商品の要素にHTMLタグを使用することはありません。Schema.orgのマークアップはHTMLとは異なる形式であり、JSON-LD形式を使用しています。JSON-LDは、HTMLの構造とは独立してウェブページに追加できる形式です。

JSON-LD形式では、ウェブページの <script> タグ内にSchema.orgのマークアップを記述します。このため、商品の情報やその他の構造化データをHTMLの要素としてマークアップする必要はありません。代わりに、JSON-LD形式で、Schema.orgのタイプやプロパティを使用して、商品の情報を記述します。

商品の情報をマークアップする際には、HTMLのタグを使用せず、JSON-LD形式でSchema.orgのマークアップを追加することになります。JSON-LD形式を使用することで、ウェブページのHTML構造とは独立して、検索エンジンや他のウェブサービスに構造化データを提供することができます。

schema.orgの中にタグに該当するようなものはあるの？
ChatGPT
Schema.orgには、HTMLのタグに相当するものとして、特定の種類の情報を表現するための構造化データの種類が存在します。これらは、特定のコンテンツや属性を示すために使用されますが、HTMLのタグとは異なります。代わりに、JSON-LD形式で提供されるプロパティと値の組み合わせです。

例えば、商品情報を表現するためのタイプとしては、「Product」があります。また、特定の属性や値を示すプロパティとして、「name」（商品名）、 「description」（説明）、 「image」（画像URL）、 「brand」（ブランド）、 「offers」（提供）などがあります。

これらのプロパティを使用して、JSON-LD形式で商品情報をマークアップすることで、検索エンジンや他のウェブサービスに対して商品の情報を提供できます。HTMLのタグとは異なりますが、同様の目的を果たすための構造化データとして機能します。

ブランド情報を表現するためのタイプは？
ChatGPT
ブランド情報を表現するためのタイプは、Schema.orgでは「Brand」です。このタイプは、特定のブランドや企業に関する情報を提供します。

以下は、JSON-LD形式で「Brand」タイプを使用してブランド情報を表現する例です。

json
Copy code
{
  "@context": "https://schema.org",
  "@type": "Brand",
  "name": "Example Brand",
  "url": "https://example.com/brand",
  "logo": "https://example.com/logo.png"
}
この例では、「name」プロパティにブランド名、「url」プロパティにブランドのウェブサイトのURL、「logo」プロパティにブランドのロゴのURLを指定しています。これにより、特定のブランドに関する情報を構造化してウェブページに追加することができます。

ブランドの説明やモットーはないの？
ChatGPT
すみません、以前の回答で重要なプロパティを見落としてしまいました。ブランドの説明やモットーを表現するためのプロパティは、実際には存在します。それは「description」プロパティです。

以下は、JSON-LD形式で「Brand」タイプを使用してブランド情報を表現し、説明やモットーを含める例です。

json
Copy code
{
  "@context": "https://schema.org",
  "@type": "Brand",
  "name": "Example Brand",
  "url": "https://example.com/brand",
  "description": "私たちのブランドは、高品質な製品と優れたカスタマーサービスを提供しています。",
  "motto": "品質とサービスの追求"
}
この例では、「description」プロパティにブランドの説明、「motto」プロパティにブランドのモットーを指定しています。これにより、ブランドに関する詳細な情報を構造化して表現することができます。

沢山のブランドを一度に紹介するには？
ChatGPT
複数のブランドを一度に紹介する場合、それぞれのブランド情報をリスト形式で表現し、それを1つのリストとして示すことが一般的です。この場合、各ブランド情報は個別の「Brand」タイプとして定義されます。

以下は、JSON-LD形式で複数のブランド情報をリストとして表現する例です。

json
Copy code
{
  "@context": "https://schema.org",
  "@type": "ItemList",
  "itemListElement": [
    {
      "@type": "Brand",
      "name": "Brand A",
      "url": "https://example.com/brand-a",
      "description": "Brand Aの説明",
      "motto": "Brand Aのモットー"
    },
    {
      "@type": "Brand",
      "name": "Brand B",
      "url": "https://example.com/brand-b",
      "description": "Brand Bの説明",
      "motto": "Brand Bのモットー"
    },
    {
      "@type": "Brand",
      "name": "Brand C",
      "url": "https://example.com/brand-c",
      "description": "Brand Cの説明",
      "motto": "Brand Cのモットー"
    }
  ]
}
この例では、「ItemList」というタイプを使用して複数のブランド情報を表現しています。各ブランド情報は、「Brand」タイプとして定義され、それぞれのブランドに関する詳細な情報が含まれています。これにより、複数のブランドを一度に紹介することができます。

ブランドのロゴも追加して。
ChatGPT
ブランドのロゴを追加するには、各ブランド情報に「logo」プロパティを追加します。このプロパティには、ブランドのロゴのURLを指定します。

以下は、ブランド情報にロゴを追加したJSON-LD形式の例です。

json
Copy code
{
  "@context": "https://schema.org",
  "@type": "ItemList",
  "itemListElement": [
    {
      "@type": "Brand",
      "name": "Brand A",
      "url": "https://example.com/brand-a",
      "description": "Brand Aの説明",
      "motto": "Brand Aのモットー",
      "logo": "https://example.com/logos/brand-a.png"
    },
    {
      "@type": "Brand",
      "name": "Brand B",
      "url": "https://example.com/brand-b",
      "description": "Brand Bの説明",
      "motto": "Brand Bのモットー",
      "logo": "https://example.com/logos/brand-b.png"
    },
    {
      "@type": "Brand",
      "name": "Brand C",
      "url": "https://example.com/brand-c",
      "description": "Brand Cの説明",
      "motto": "Brand Cのモットー",
      "logo": "https://example.com/logos/brand-c.png"
    }
  ]
}
この例では、各ブランド情報に「logo」プロパティを追加し、それぞれのブランドのロゴのURLを指定しています。これにより、複数のブランドを紹介しながら、各ブランドのロゴも表示できます。


この情報は、<head>に書かないと駄目なの？
ChatGPT
Schema.orgのマークアップは通常、ウェブページの <head> セクション内に配置されますが、具体的にはJSON-LD形式のスクリプトとして埋め込まれます。 <head> セクション内に埋め込むことで、検索エンジンや他のウェブサービスがウェブページの構造化データをすばやく認識し、適切に解釈することができます。

ただし、 <head> セクション以外にもJSON-LD形式のスクリプトを配置することは可能です。一般的な場合は、ウェブページの <body> セクション内の任意の位置にJSON-LDスクリプトを埋め込むこともできます。ただし、構造化データが正しく解釈されるためには、スクリプトがウェブページの内容と関連していることが重要です。

例えば、商品情報が実際の商品の説明や画像の後に表示される場合、その商品情報のJSON-LDスクリプトも同じページ内の適切な位置に配置することが望ましいです。

要するに、JSON-LD形式のSchema.orgのマークアップは、ウェブページ内のどこにでも配置できますが、通常は <head> セクション内に配置して、検索エンジンにとって容易にアクセスできるようにします。

<section>
   <h1>商品１</h1>
   <p>説明。。。。</p>
   <script>商品１の json-ld</script>
</section>
<section>
   <h1>商品２</h1>
   <p>説明。。。。</p>
   <script>商品２の json-ld</script>
</section>
ChatGPT
提供された例では、各商品の情報にJSON-LD形式のスクリプトを埋め込んでいます。これは基本的に構造化データを提供する方法としては有効ですが、通常はJSON-LD形式のスクリプトはHTMLの <head> セクション内に配置されることが推奨されます。

ただし、スクリプトをセクション内に直接埋め込む方法も、ウェブページ内の特定のコンテンツと関連付けることができます。これにより、特定の商品情報がその商品の説明や画像の後に表示されるようになります。

以下は、提供された例を改良して、セクション内にJSON-LD形式のスクリプトを直接埋め込む方法です。

html
Copy code
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>商品ページ</title>
</head>
<body>

<section>
   <h1>商品１</h1>
   <p>説明。。。。</p>
   <script type="application/ld+json">
   {
     "@context": "https://schema.org",
     "@type": "Product",
     "name": "商品１",
     "description": "商品１の説明"
   }
   </script>
</section>

<section>
   <h1>商品２</h1>
   <p>説明。。。。</p>
   <script type="application/ld+json">
   {
     "@context": "https://schema.org",
     "@type": "Product",
     "name": "商品２",
     "description": "商品２の説明"
   }
   </script>
</section>

</body>
</html>
このようにして、各商品情報がそれぞれの商品の説明と関連付けられます。ただし、スクリプトがセクション内に直接埋め込まれているため、セクションごとに繰り返し記述する必要があります。通常は、商品情報を1回だけ記述し、それを各商品の説明や画像の後に追加することが一般的です。

じゃあ商品毎のページを作ればいいってこと？
ChatGPT
はい、商品毎のページを作成するのが一般的な方法です。各商品に独自のページを持たせることで、商品の詳細情報や構造化データを適切に提供しやすくなります。

各商品ページには、商品の説明、画像、価格、特徴などの詳細情報を提供するだけでなく、JSON-LD形式のSchema.orgのマークアップを追加して、検索エンジンや他のウェブサービスに商品情報を構造化して提供します。これにより、検索結果や検索エンジンの特別な機能（例: リッチリザルト）で商品が目立ちやすくなり、ユーザーがより便利に商品を見つけることができます。

商品毎のページを作成する際には、各ページに適切なタイトル、説明、画像、価格、特徴などの情報を含めることが重要です。また、ページの構造化データとして、JSON-LD形式のSchema.orgのマークアップを追加することも忘れないでください。

descriptionは長くてもいいのかな？
ChatGPT
descriptionはウェブページや商品などの要約や説明を提供するためのプロパティです。通常、descriptionは短くても良いですが、Googleなどの検索エンジンは長いdescriptionを使用しても一部を表示することがあります。一般的には、長さが約150〜160文字程度のdescriptionが推奨されますが、必ずしもこれに拘束される必要はありません。

descriptionの目的は、ユーザーが検索結果からウェブページの内容を理解できるようにすることです。そのため、適切な情報を提供し、ユーザーが関心を持つ可能性がある内容を強調することが重要です。長いdescriptionを使用する場合は、重要なキーワードや情報を最初に配置しておくと良いでしょう。

ただし、長いdescriptionを使用する場合でも、必要以上に冗長にならないように注意することが重要です。過度に長いdescriptionは、検索結果で完全に表示されず、効果的なコンテンツの伝達が難しくなる可能性があります。
```
