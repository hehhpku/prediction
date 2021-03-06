# prediction

## 特征工程


- 用户基本信息特征
  - 用户性别 one-hot
  - 用户年龄 one-hot
  - 用户等级 one-hot

- 用户行为特征
  - 用户浏览过的**目标品类**商品数量
  - 用户浏览过但没有下单的**目标品类**商品数量
  - 用户浏览过并下单的**目标品类**商品数量
  - 用户对**目标品类**的浏览后下单率<br/><br/>

  - 用户关注过的**目标品类**商品数量
  - 用户关注过但没有下单的**目标品类**商品数量
  - 用户关注过并下单的**目标品类**商品数量
  - 用户对**目标品类**的关注后下单率<br/><br/>

  - 用户浏览过但没有下单的**非目标品类**商品数量
  - 用户浏览过并下单的**非目标品类**商品数量
  - 用户关注过但没有下单的**非目标品类**商品数量
  - 用户关注过并下单的**非目标品类**商品数量<br/><br/>
 
  - 用户最后一次行为，距离考察日期的天数
  - 用户对目标品类商品的浏览日期，距离下单日期的平均天数

- 商品基本信息特征
  - 商品所处的价格区间等级
  - 商品品类
  - 商品参数para_1
  - 商品参数para_2
  - 商品参数para_3

- 商品统计特征
  - 商品的浏览量
  - 商品的评分
  - 商品的浏览=>下单转化率
  - 商品的关注=>下单转化率

- 时间特征
  - 是否春节
  - 是否促销

### 样本选择
  - 过滤爬虫
  - 过滤事先没有行为而最终购买的用户
