# 令和6年能登半島地震 産業用仮設施設GISデータ
## 概要
令和6年能登半島地震に伴い中小機構の助成により整備中の産業用仮設施設について、中小機構のウェブサイト等の情報をもとに、現地調査等により一部修正して、GISデータ化したデータ（GeoJSON形式）を公開しています。  
以下のリンクより、データにアクセス可能です。  
- GeoJSON形式  

- Google スプレッドシートへのリンク  

## 更新情報
- 2024/11/11
  - 中小機構のウェブページ「[仮設施設整備への助成](https://www.smrj.go.jp/reconstruction/noto_peninsula_20240101/support/temporary/index.html#wajima-k4)」の情報（2024/10/21現在の情報）に基づきデータを作成し公開しました。位置は現地調査できたものについては、中小機構のデータの座標から多少修正しているものもあります。


## 属性情報
- **「施設種別」**	String
  - 「仮設店舗・事務所」、「仮設工房」、「仮設宿泊施設」に分類しています。
- **「地区」**　String
- **「立地」**　　String
- **「所在地」**　String
- **「棟数」**　Integer
- **「区画数」**　Integer
- **「面積」**　Integer
- **「供用開始日」**　　Date Only
- **「入居者」**　　Integr　入居者数
- **「備考」**　　String
- **「完成フラグ」**　　String
  - 供用開始日が明記されたものは「完成」、されていないものは「整備中」と記載しています。

## ライセンスについて  
- 公開しているGeoJSON形式およびGoogle スプレッドシートのデータ: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 参考リンク
- [中小機構 仮設施設整備への助成](https://www.smrj.go.jp/reconstruction/noto_peninsula_20240101/support/temporary/index.html#wajima-k4)
