# 10-week-data-analysis
*  [第一週：培養資料分析思維](https://medium.com/@h0100556910721/%E6%95%B8%E6%93%9A%E5%88%86%E6%9E%90%E7%9A%84%E4%B8%89%E7%A8%AE%E6%80%9D%E7%B6%AD%E6%9E%B6%E6%A7%8B%E8%88%87%E4%B8%83%E7%A8%AE%E6%80%9D%E7%B6%AD%E6%8A%80%E5%B7%A7-904b6581a69a)
    * 思維方式：金字塔/結構化思維(分類問題、心智圖)、公式化思維(量化分析)、業務化思維
* 第二週：Excel 技能進階 
  * Excel 函數、資料透視表(樞紐分析表)
* 第三週：學習資料庫原理和 SQL
  * 資料庫核心技能
  >select 語句添加欄位和找出需要的資料
  >>select cola,colb,colc into newtable from oldtable wherecola=’x’ and colb is not null；
  >>select cola from oldtable group by cola;
  >>
  >alter 學會增加，減少欄位
  >>1. 增加欄位：alter table tablename add colname varchar;
  >>增加一個空欄位，varchar 是一種資料類型。
  >>2. 減少欄位：alter table tablename drop column colname;  
  >>
  >更新資料
  >>更新成一個固定值：update table set col=1;
  >>從另一張表裡面更新：update table set col=tableb.col from tablebwhere table.id=tableb.id;
  


