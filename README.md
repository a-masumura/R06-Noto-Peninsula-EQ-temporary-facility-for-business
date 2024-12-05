# 令和6年能登半島地震 産業用仮設施設GISデータ
## 概要
令和6年能登半島地震に伴い中小機構の助成により整備中の産業用仮設施設について、中小機構のウェブサイト等の情報をもとに、現地調査等により一部修正して、GISデータ化したデータ（GeoJSON形式）を公開しています。  
以下のリンクより、データにアクセス可能です。  
- GeoJSON形式  
[https://github.com/a-masumura/R06-Noto-Peninsula-EQ-temporary-facility-for-business/raw/main/令和6年能登半島地震_産業用仮設施設.geojson](https://raw.githubusercontent.com/a-masumura/R06-Noto-Peninsula-EQ-temporary-facility-for-business/main/%E4%BB%A4%E5%92%8C6%E5%B9%B4%E8%83%BD%E7%99%BB%E5%8D%8A%E5%B3%B6%E5%9C%B0%E9%9C%87_%E7%94%A3%E6%A5%AD%E7%94%A8%E4%BB%AE%E8%A8%AD%E6%96%BD%E8%A8%AD.geojson)
- Google スプレッドシートへのリンク  
https://docs.google.com/spreadsheets/d/1plrBhOUwE550-q0AkajTni-eTsPfjLpoJLNE7J1p3Ak/edit?usp=sharing

## 更新情報
- 2024/12/5
  - 中小機構のウェブページ「[仮設施設整備への助成](https://www.smrj.go.jp/reconstruction/noto_peninsula_20240101/support/temporary/index.html)」の情報（2024/11/28現在の情報）に基づきデータを作成し公開しました。データ列を見直しました。
- 2024/11/11
  - 中小機構のウェブページ「[仮設施設整備への助成](https://www.smrj.go.jp/reconstruction/noto_peninsula_20240101/support/temporary/index.html)」の情報（2024/10/21現在の情報）に基づきデータを作成し公開しました。位置は現地調査できたものについては、中小機構のデータの座標から多少修正しているものもあります。


## 属性情報
- **「災害」**	String
  - 「令和6年能登半島地震」
- **「都道府県」**	String
  - 立地する都道府県名。
- **「市町村」**	String
  - 立地する市町村名。
- **「施設種別」**	String
  - 「仮設店舗・事務所」、「仮設工房」、「仮設宿泊施設」に分類しています。
- **「整備主体」**	String
- **「施設種別」**	String
  - 中小機構の分類に従い、「仮設店舗・事務所」、「仮設工房」、「仮設宿泊施設」に分類しています。
- **「名称_愛称_」**	String
  - 現地調査等で確認できた施設の名称・愛称を記載しています。
- **「地区」**	String
  - 中小機構のウェブページに記載されている施設の呼び名を記載しています。
- **「立地」**	String
  - 中小機構のウェブページに記載されている施設の立地情報による補足を記載しています。
- **「所在地」**　String
- **「棟数」**　Integer
- **「区画数」**　Integer
- **「面積」**　Integer
  - およその床面積で、単位は平方メートルです。
- **「入居者」**　　Integr
  - 入居者数
- **「完成フラグ」**　　String
  - 供用開始日が明記されたものは「完成」、されていないものは「整備中」と記載しています。
- **「供用開始日」**　String
- **「供用開始日」**　String
- **「備考」**　String
- **「x」「y」**
  - Googleスプレッドシートのみに記載しています。（おそらく）Webメルカトル図法（WGS 1984）におけるメートル単位の座標です。

## ライセンスについて  
- 公開しているGeoJSON形式およびGoogle スプレッドシートのデータ: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 参考リンク
- [中小機構 仮設施設整備への助成](https://www.smrj.go.jp/reconstruction/noto_peninsula_20240101/support/temporary/index.html)
