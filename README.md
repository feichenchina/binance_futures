### 没有订单的情况下
1. 查询当天永续合约的所有交易对中涨幅最高的，自定义币种，每个币种最多一个订单
2. 查询其交易深度，求其加权平均值，算出买入价格，买多进入（添加撤销时间）
3. 一旦买入，立刻添加卖出的订单，设定止盈率