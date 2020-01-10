# Brinson-Attribution

1.概述
------
brinson模型是基金组合业绩归因的重要工具，借助基金具体的持仓信息，来实现基金当期收益的分解。

具体而言，可以将基金所持有的股票组合相对于基准股票组合的超额收益分为资产配置收益和个股选择收益，考虑到股票组合通常按照行业维度进行分类，因此可将基金投资股票部分的超额收益分解为行业配置收益和行业内的个股选择收益。

另一方面，基金除了股票之外，还会将部分资金配置于债券、银行存款、货币基金等类固定收益资产。随着市场行情的变动，组合投资经理会调整股票与债券两部分投资之间的比例，从而通过择时对超额收益产生贡献，因此，最终可以将基金的超额收益分解为择时效应、行业配置效应和选股效应三部分。

2.模型细节
------
