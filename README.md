# 10-week-data-analysis
## 具備看待一個事物的邏輯化思維，其次用資料去證明
*  [第一週：培養資料分析思維](https://medium.com/@h0100556910721/%E6%95%B8%E6%93%9A%E5%88%86%E6%9E%90%E7%9A%84%E4%B8%89%E7%A8%AE%E6%80%9D%E7%B6%AD%E6%9E%B6%E6%A7%8B%E8%88%87%E4%B8%83%E7%A8%AE%E6%80%9D%E7%B6%AD%E6%8A%80%E5%B7%A7-904b6581a69a)
    * 思維方式：金字塔/結構化思維(分類問題、心智圖)、公式化思維(量化分析)、業務化思維
![image](https://lh6.googleusercontent.com/poV1jHjQhwD3d9jCpFkCAIEZR6-lHEc-84IJ8sA6W7AXK7iuwhc87lsIOL8em3R31Zy4m351ITM27Ye1qptpax2Od1k6NjncCO9gPFIe9HrAY7zBLK_cbdhfpILh75DI5-wFd85w)
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
* 第四週：數理統計學
1. 集中趨勢(中數、眾數、平均數)
2. 變異（四分位數、四分位距、異常值、方差）
3. 歸一化(標準分數)
4. 正態分布
5. 抽樣分布（中心極限、抽樣分布）
6. 估計(置性度、置信區間)
7. 假設檢驗
8. T 檢驗
* 第五週：資料分析軟體應用
   * 掌握BI工具
* 第六週：資料視覺化
   * 圖表類型：趨勢性、相關性、分布性、週期性、地理位置分布性… 
   * 視覺化陷阱
* 第七週：常見的業務分析模型
1. 購物籃分析模型
2. RFM 模型
3. 漏斗分析模型
4. 客戶生命週期
5. 預測、聚類分析等挖掘模型 
* 第八週：Python/R 語言掌握 
   * 掌握 Numpy、Pandas、Matplotlib
* 第九週：業務理解和指標設計 
* 第十週：資料驅動&成長駭客

待補充
待補充
待補充

