# nezha-ui
##### 后台添加
###### 自用的探针更改 
```html
<meta name="referrer" content="no-referrer">
/* 自用的css格式 */
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ziwiwiz/nezha-ui@main/nezha-style.css">
/* 自用的探针修改 */
<script>
    window.CustomBackgroundImage = "https://bing.img.run/rand_uhd.php"; /* 页面背景图 */
    window.CustomMobileBackgroundImage = "https://bing.img.run/rand_m.php"; /* 移动端页面背景图 */
    /* 卡片显示上下行流量 */
    // window.ShowNetTransfer = "true";
    /* 关掉人物插图 */
    window.DisableAnimatedMan = "true";
    /* 自定义描述 */
    window.CustomDesc = "v2.games";
</script>
```
###### 周期性流量进度条 
```html
<script>
  window.TrafficScriptConfig = {
    showTrafficStats: true,    // 显示流量统计, 默认开启
    insertAfter: true,         // 如果开启总流量卡片, 是否放置在总流量卡片后面, 默认为true
    insertReplace: false,      // 如果开启，则流量条会替换出入流量统计, 默认为false
    interval: 60000,           // 60秒刷新缓存, 单位毫秒, 默认60秒
    toggleInterval: 5000,      // 4秒切换流量进度条右上角内容, 0秒不切换, 单位毫秒, 默认5秒
    duration: 500,             // 缓出缓进切换时间, 单位毫秒, 默认500毫秒
    enableLog: false,          // 开启日志, 默认关闭
    styleNum: 1,               // 风格切换，1为经典，2为本人自定义的，默认为1
  };
</script>
<script src="在这里添加属于你的分发链接，这里省略"></script>
```
