# Airport-Free
## 免费节点，每3h自动更新订阅

- 更新时间（UTC+8）：`2025-02-21 23:53:23`
- [v2ray节点多合一](https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray.txt)（不建议用这个，因为太多了系统ping不过来）
- [v2ray节点多合一](https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray.txt)（如果第一个无法订阅就用这个）
- 由于CDN加速会缓存导致节点更新滞后，可以前往[Github](https://github.com/xiaoji235/airport-free)获取<strong>v2ray.txt</strong>文件或者[clash](https://github.com/xiaoji235/airport-free/tree/main/clash)路径下的txt文件和[v2ray](https://github.com/xiaoji235/airport-free/tree/main/v2ray)路径下的txt文件。

### 已开启jsdelivr CDN加速：

<table style="width:90%">
<tr><td><strong>v2ray</strong></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/clashnodecc.txt">v2ray节点 1</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/naidounode.txt">v2ray节点 2</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/nodefree.txt">v2ray节点 3</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/nodev2ray.txt">v2ray节点 4</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/v2rayshare.txt">v2ray节点 5</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/v2ray/wenode.txt">v2ray节点 6</a></td>


</tr>
<tr><td><strong>clash</strong></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/clashnodecc.txt">clash节点 1</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/naidounode.txt">clash节点 2</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/nodefree.txt">clash节点 3</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/nodev2ray.txt">clash节点 4</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/v2rayshare.txt">clash节点 5</a></td>
<td align="center"><a href="https://cdn.jsdelivr.net/gh/xiaoji235/airport-free/clash/wenode.txt">clash节点 6</a></td>


</tr>
</table>

### 如果订阅更新不了再用这个：

<table style="width:90%">
<tr><td><strong>v2ray</strong></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/clashnodecc.txt">v2ray节点 1</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/naidounode.txt">v2ray节点 2</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/nodefree.txt">v2ray节点 3</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/nodev2ray.txt">v2ray节点 4</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/v2rayshare.txt">v2ray节点 5</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/v2ray/wenode.txt">v2ray节点 6</a></td>


</tr>
<tr><td><strong>clash</strong></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/clashnodecc.txt">clash节点 1</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/naidounode.txt">clash节点 2</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/nodefree.txt">clash节点 3</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/nodev2ray.txt">clash节点 4</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/v2rayshare.txt">clash节点 5</a></td>
<td align="center"><a href="https://ghp.ci/https://raw.githubusercontent.com/xiaoji235/airport-free/main/clash/wenode.txt">clash节点 6</a></td>


</tr>
</table>

## 源码
- 源码已开源，详情请移步[GitHub](https://github.com/xiaoji235/airport-free/tree/main)

## 特点
- 只需将v2ray的py脚本存放到 node/v2/ 当中后前往 <strong>action</strong> 运行workflow后即可看到输出结果。
- 只需将clash的py脚本存放到 node/clash/ 当中后前往 <strong>action</strong> 运行workflow后即可看到输出结果。

## 说明
- 本源码已默认添加了5个节点源，每隔3个小时自动检测更新，如果有新源欢迎大家前往[issues](https://github.com/xiaoji235/airport-free/issues)提交节点源！
- 修改README.md请前往：<strong>nodes/README.md</strong>
- 由于python脚本搜集的clash有些节点是合并为一个文本，可能会导入失败，尽量用v2ray节点吧，好处理。

## 问题
- 由于多个网站收录的节点有的可能重复，已做了去重处理，但可能仍有部分重复！
- 部分网站可能会由于长城或站点自身原因将来可能无法访问就可能导致无法更新订阅！

## 提示
- 所有数据来源于互联网，内容真实性请用户自行辨认。
- 本源码仅供Python学习，禁止用于违法犯罪行为，否则后果自负！
