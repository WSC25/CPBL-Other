# CPBL
## 1.RS% -- Run Scoring Percentage
跑者上壘(或作為代跑上場)後最終跑回來得分的比例

公式:
RS% = (R - HR) / (H + HBP + BB - HR + G_pr)
*G_pr = 代跑次數

## 2.第二打擊率 Secondary Average(SecA)
第二打擊率可以同時衡量出一位打者的選球、長打及速度能力的綜合數據。
一般來說 SecA過0.500 可以視為頂尖打者
 
公式:
SecA = (BB + (TB – H) + (SB – CS)) / AB


## 3.PowerSpeed(PwrSpd)
由Bill James發明的數據，以粗糙方式量化全壘打和盜壘能力的指標，不過Bill James本人表示該數據沒有太多的分析價值
“James himself has referred to this as a "freakshow" stat with little analytical value.”

公式:
PwrSpd = 2(HR x SB)/(HR + SB)
##### *1如果打者盜壘或全壘打任一項目為0，則PwrSpd為0，EX:2023年廖建富 22轟0盜

##### *2該數據對同時能轟能跑的打者較吃香

## 4.EqA (Equivalent Average)
等效打擊平均（Equivalent Average，簡稱EqA）是由Baseball Prospectus的Clay Davenport 所開發，用於衡量球員整體打擊能力的統計指標，旨在綜合考慮球員各種打擊表現而不僅僅是觀察傳統的打擊率或傳統的OPS(OBP+SLG)。
EqA的值通常以小數形式呈現，其數值越高代表球員在整體打擊表現上越出色。

公式:
EqA 	= (H + TB + 1.5x(BB + HBP) + SB) / (AB + BB + HBP + CS + SB/3)		　
= (安打+總壘打數+1.5x(四壞球+觸身球)+盜壘)/(打數+四壞球+觸身球+盜壘刺+盜壘/3)

