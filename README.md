# day32019.4.24
标准单元库
2,阅读文档transition time, propagation delay等参数的定义
  Transition Time：输入输出信号上升和下降的时间
  setup time:在时钟有效上升沿到来之前数据需要保持的最小时间
  hold time:在时钟有效上升沿到来之后数据需要保持的最小时间
  recovery time:在时钟有效上升沿到来之前后复位和置位需要保持的最小时间
3.Power Dissipation/Calculation描述
  器件的功耗与电源电压，内部电容，工作平率，以及复杂有关。
5提供的cell类型
   包含特殊标准单元，基础单元以及优化单元，其中基础单元包括一些全加器，与门，触发器等器件
6.verilogzhong 包含哪些信息。
        包含基本单元的代码，以及一些时序参数。
