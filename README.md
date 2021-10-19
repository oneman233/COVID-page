# Everything about COVID19

一个新冠疫情实时数据和防护指南的静态 html 页面

**WARNING：项目中使用了静态地址，迁移到其他设备时会产生错误**

## 实现方案

* [Vue3](https://v3.vuejs.org/) + [ElementPlus](https://element-plus.gitee.io/zh-CN/) + [axios](https://www.axios.com/)
* 丁香园的[新冠疫情 API](https://lab.isaaclin.cn/nCoV/)
  * 按天更新的感染者数据
  * 国内新冠疫情相关新闻
  * 新冠疫情相关谣言
* 字节跳动的[西瓜视频播放器](https://v2.h5player.bytedance.com/)
* 采用 [echarts](https://echarts.apache.org/zh/index.html) 绘制中国地图
* 采用 semantic scholar 的 [Google Scholar API](https://www.semanticscholar.org/product/api) 获取新冠相关论文

## TODOs

- [ ] 页面添加标题
- [ ] 关闭全部论文
- [ ] 论文标题修改
