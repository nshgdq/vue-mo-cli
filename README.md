# vuedemo

> A Vue.js project


### 
***
* 不同环境调用不同的接口，分为开发环境，测试环境，预生产环境，生产环境，
* 本地调用接口，实用proxyTable代理
* 使用DllReferencePlugin将第三方资源分离打包，提高打包速度


安装 vue-cli
```
npm install -g vue-cli
```

安装
```
npm install
```



启动开发环境
```
npm run dev
```



打包到生产环境
```
npm run build
```


打包到预生产环境
```
npm run buildppe
```


打包到测试产环境
```
 npm run buildtest
```



将第三方资源分离打包，提高打包速度
```
 npm run build:dll
```

```
*新增demo，vue九宫格抽奖

```
***
* config中配合本地代理，处理跨域
*  package.json为项目拷贝文件，可忽略
***

部分字段说明
prizeDesc：奖品说明，采用“$utf8$”分割，前端截取成数组，进行展示

winners：获奖名单

defineId：活动id

remainingTimes：剩余抽奖次数

beginTime：活动开始时间

endTime活动结束时间

currTime:当前时间

title：活动标题

prizeInfo：奖品信息

lotteryDesc：抽奖活动说明规则,同奖品说明prizeDesc
