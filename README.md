# -思路
>EPS是每股盈余（英文全称Earnings Per Share）的缩写，指普通股每股税后利润，也称为“每股收益”。EPS为公司获利能力的最后结果。每股盈余高代表着公司每单位资本额的获利能力高,这表示公司具有某种较佳的能力——产品行销、技术能力、管理能力等等,使得公司可以用较少的资源创造出较高的获利。
  
>市盈率（Price earnings ratio，即P/E ratio）也称“本益比”、“股价收益比率”或“市价盈利比率（简称市盈率）”。市盈率是最常用来评估股价水平是否合理的指标之一，由股价除以年度每股盈余（EPS）得出（以公司市值除以年度股东应占溢利亦可得出相同结果）。计算时，股价通常取最新收盘价，而EPS方面，若按已公布的上年度EPS计算，称为历史市盈率（historical P/E）；计算预估市盈率所用的EPS预估值，一般采用市场平均预估（consensus estimates），即追踪公司业绩的机构收集多位分析师的预测所得到的预估平均值或中值。何谓合理的市盈率没有一定的准则。

>股息率（Dividend Yield Ratio），是一年的总派息额与当时市价的比例。以占股票最后销售价格的百分数表示的年度股息，该指标是投资收益率的简化形式。股息率是股息与股票价格之间的比率。在投资实践中，股息率是衡量企业是否具有投资价值的重要标尺之一。

* CAGR复合年度增长率 = （2年后EPS-当前EPS）^(1/2)-1
>>> 盈利预测从东方财富爬  http://data.eastmoney.com/report/ylyc.html
* 股息率=10派红利/10/当前股价
* 低估程度 = (平均市盈率)/((CAGR复合年度增长率+股息率)*100) - 1

1. 低估程度标准化得分
2. 市值标准化得分
3. 市盈率标准化得分
4. 最后得分 = 低估程度标准化得分*0.55 + 市值标准化得分*0.1 + 市盈率标准化得分*25% + 资产收益率*0.05 + 市净率*0.05

+ 按照最后得分排名
