# 北京周末机票雷达

网站：https://yueyangpaul.github.io/flight-radar/

北京出发周末往返机票的每晚扫描结果，由本地定时任务生成 `data.json` 并推送到这里，GitHub Pages 直接展示 `index.html`。

- `data.json`：最近 10 天列表页精查、最新一次全年日历预筛、各目的地动态阈值（每晚覆盖）
- `cities.json`：扫描城市列表。网页上用有本仓库写权限的 GitHub 令牌修改；每晚扫描前同步回本地数据库

价格均为携程列表页起价推算，未经订单页核验。
