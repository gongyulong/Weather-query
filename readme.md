## Demo：天知道

1. 实现最终效果演示

   ![1569383470307](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1569383470307.png)

2. 天气接口查询

   > 获取天气url：<http://wthrcdn.etouch.cn/weather_mini?city=深圳>  是get请求

3. 实现步骤分析

   1. 天气搜索的输入框 v-model:city
   2. 点击回车 @keyup.enter = "searchWeather"
   3. 点击搜索 @click = "searchWeather"
   4. 发送数据请求 axios.get( url ).then().catch()
   5. 保存天气数据的数组 weatherList
   6. 使用 v-for 渲染到页面即可

4. 代码结构演示

5. 开发过程演示

6. 所用知识及注意事项小结

