## 返回结果为JS的Cookie逆向

### 简介
阿里系的Cookie均有这个特点：需要请求两次，第一次返回一段js代码，第二段才返回cookie
1. 首页：[https://xueqiu.com/today](https://xueqiu.com/today)
2. 目标：cookie： acw_sc__v2

### 技术点：
1. Hook：debug、cookie（油猴） 
2. OB混淆
3. 代码压缩
4. 扣代码
5. 函数参数为常量，则直接把结果写为常量

