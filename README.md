# Data
Intersection RandomTrip Simulation Data

SumoTrace.csv: RandomTrip生成的交叉口随机车流轨迹数据

SumoTrace_p2.csv：基于SumoTrace.csv添加了三种不同车辆类型（在pandas处理得到，sumo的RandomTrip似乎不支持设置不同车辆类型）

summary.zip：sumo的其他配置文件（如trip、rou文件）

map.net.xml：sumo路网文件

detection data.csv：基于SumoTrace_p2.csv与遮挡关系生成的探测数据表

data_split(PR).py： 基于不同渗透率对detection data.csv进行分割的代码
