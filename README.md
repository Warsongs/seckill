# 创建
基本的CRUD操作

# Task：19/6/5
前端设计  
主页面两个按钮选择，进去点击选择用户或者商家。
***
1. 点击用户的话点击进入登录界面，登录界面进行登录操作后进入秒杀商品列表页面。
  1. 秒杀商品列表，表格形式展示所有秒杀任务，并提供信息暂定如下   
商品名，价格，秒杀开始时间，秒杀结束时间，总商品数量，剩余商品数量（暂定），以及最后的秒杀按钮。
  2. 点击秒杀按钮后应当在前台屏蔽这个按钮的再次点击，从而在前端控制单用户重复购买。
    1. 秒杀按钮在秒杀开始时间之前应当为暗色不可选状态，在秒杀开始时间后才变为亮色可选状态。
    2. 秒杀按钮在可以秒杀后可以显示离秒杀结束时间之间剩余的时间间隔
    3. 剩余商品数量可以设置为一个每隔多少秒就触发一次的ajax操作，显示剩余数量。
    4. 剩余数量为0时或时间到达秒杀结束时间后，秒杀按钮应变为灰色。
2. 点击商家的话进入商家管理界面。
  1. 因为现在暂时没有在用户表上对用户类型进行管理，那暂时可认为点击商家按钮的都操作的是同一个商家，可以操作每一个商品和每一个秒杀任务。
  2. 可以对商品进行增删改查。
  3. 可以对秒杀任务进行增删查。
  4. 对秒杀任务的修改操作只能在秒杀任务开始时间之前进行。
