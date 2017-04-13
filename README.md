# financial-data-analysis-naive
 
1. 计算每个股票的5分钟均价
1. 计算每个股票每分钟已实现的日内回报
1. 计算行业均价指数(行业中的股票价格算术平均)，从1000起始
1. 计算每个行业每分钟的金融属性，并且编码：  
    -*  20分钟均线位置(当前的行业指数点位/20分钟的均线点位-1）
    -*  20分钟区间位置(当天的行业指数-20分钟内行业指数最小)/(20分钟内行业指数最大-20分钟内行业指数最小)
    -*  20分钟beta(采用经典算法，行业指数指数与其自身20分钟的指数）
1. 当天每个整点计算出截至到当前时间的最强的10个行业，评估这10个行业未来到下个整点的这段时间与全28行业的alpha（整点取10:00,11:00,14:00，3个) 例如(在10:00评估一下最强的行业，假设评估1个行业为银行，则计算一下从10:00到11:00银行指数的涨幅与28个行业的平均涨幅的差值)
