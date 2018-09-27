title: 工资与五险一金计算
speaker: 关鹏
theme: light
transition: slide2
headFiles: /assets/light.css

[slide]

# 工资与五险一金计算
## 关鹏

[slide]

## 公式

- 核心公式
    - 实发工资 = <span style="color:#4387fd">应发工资</span> － <span style="color:red">个人五险一金</span> － <span style="color:#c700ff">个人所得税</span>
    - 个人资产 = 实发工资 + <span style="color:red">个人五险一金</span> + <span style="color:#ff7000">公司五险一金</span>
- 解释
    - <span style="color:#4387fd">应发工资</span> = 公司报价（比如20K/月，25K/月）
    - <span style="color:red">个人五险一金</span> = 个人按个人工资比例缴纳的保险
    - <span style="color:#ff7000">公司五险一金</span> = 公司按个人工资比例缴纳的保险
    - <span style="color:#c700ff">个人所得税</span> = **(应发工资 － 个人五险一金)**超过**3500元**后按比例缴纳的税收

[slide]

## 五险一金

- 不同城市五险一金缴费比例、最高缴费标准有差别，假设为以下比例
    - <span style="color:red">个人缴费23%</span> = 养老8% + 医疗2% + 失业1% + 公积金12%
    - <span style="color:#ff7000">公司缴费43.5%</span> = 养老20% + 医疗8% + 失业 2% + 生育1% + 工伤0.5% + 公积金12%
- 举例计算：
    - <span style="color:#4387fd">应发工资</span> = 10000
    - <span style="color:red">个人五险一金</span> = 10000 * 23% = 2300
    - <span style="color:#ff7000">公司五险一金</span> = 10000 * 43.5% = 4350
    
> 实发工资 = <span style="color:#4387fd">10000(应发工资)</span> － <span style="color:red">2300(个人五险一金)</span> － <span style="color:#c700ff">个人所得税</span>

> 个人资产 = 实发工资 + <span style="color:red">2300(个人五险一金)</span> + <span style="color:#ff7000">4350(公司五险一金)</span>


[slide]

## 个人所得税

税率表

| 级数 | 应纳税所得额（含税） | 应纳税所得额（不含税） | 税率（%） | 速算扣除数
|:----|:----|:----|:----|:----|
|1|	不超过1,500元的部分|	不超过1,455元的部分|	3|	0|
|2|	超过1,500元至4,500元的部分|	超过1,455元至4,155元的部分|	10|	105|
|3|	超过4,500元至9,000元的部分|	超过4,155元至7,755元的部分|	20|	555|
|4|	超过9,000元至35,000元的部分|	超过7,755元至27,255元的部分|	25|	1,005|
|5|	超过35,000元至55,000元的部分|	超过27,255元至41,255元的部分|	30|	2,755|
|6|	超过55,000元至80,000元的部分|	超过41,255元至57,505元的部分|	35|	5,505|
|7|	超过80,000元的部分|	超过57,505的部分|	45|	13,505|

[slide]

## 个人所得税计算

- 举例计算
    - <span style="color:#4387fd">应发工资</span> = 10000
    - <span style="color:red">个人五险一金</span> = 10000 * 23% = 2300
    - 应纳税所得额 = (<span style="color:#4387fd">应发工资</span> － <span style="color:red">个人五险一金</span>) － 3500 = (10000 － 2300) － 3500 = 4200
    - <span style="color:#c700ff">个人所得税</span> = 应纳税所得额 × 税率 － 速算扣除数 = 4200 × 10% － 105 = 315（等同于分段计算，[速算扣除数含义](https://baike.baidu.com/item/%E9%80%9F%E7%AE%97%E6%89%A3%E9%99%A4%E6%95%B0)）
- 所需税率表

| 级数 | 应纳税所得额（含税） | 应纳税所得额（不含税） | 税率（%） | 速算扣除数
|:----|:----|:----|:----|:----|
|2|	超过1,500元至4,500元的部分|	超过1,455元至4,155元的部分|	10|	105|

-----

> 7385(实发工资) = <span style="color:#4387fd">10000(应发工资)</span> － <span style="color:red">2300(个人五险一金)</span> － <span style="color:#c700ff">315(个人所得税)</span>

> 14035(个人资产) = 7385(实发工资) + <span style="color:red">2300(个人五险一金)</span> + <span style="color:#ff7000">4350(公司五险一金)</span>

[slide]

## 各阶段月薪情况

![](/assets/Salary/1.jpg)

> 7385(实发工资) = <span style="color:#4387fd">10000(应发工资)</span> － <span style="color:red">2300(个人五险一金)</span> － <span style="color:#c700ff">315(个人所得税)</span>

> 14350(公司总支出) = <span style="color:#4387fd">10000(应发工资)</span> + <span style="color:#ff7000">4350(公司五险一金)</span>

[slide]

## 结论

- 工资较低的时候，到手工资比例主要受五险一金影响
- 随着工资的升高，五险一金保持不变，到手比例主要受超额累进税率的影响
- 工资趋于无穷大，到手工资比例将无限接近55%，因为工资个税最高边际税率为45%
- 如果公司减少**公司五险一金**支出，那么亏本的是个人

[slide]

## 参考资料

- [算上交税、五险一金，真正到手的工资大概占比多少？](https://www.zhihu.com/question/30139332)
- [个人所得税计算方法](http://www.gerensuodeshui.cn/)