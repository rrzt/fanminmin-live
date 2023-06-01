<h1 align="center"> ✯ 一个国内可直连的直播源分享项目 ✯ </h1>

<h3 align="center">🔕 永久免费 直连访问 完整开源 不含广告 完善的台标 直播源支持IPv4/IPv6双栈访问 🔕</h3>

<p align="center">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/fanmingming/live">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/fanmingming/live">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/fanmingming/live">
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/fanmingming/live">
<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/fanmingming/live">
<img alt="GitHub" src="https://img.shields.io/github/license/fanmingming/live">
</p>

---

## 🤹‍♂️直播源:

<table>
  <thead>
    <tr>
      <th>名称</th>
      <th>直播源地址</th>
      <th>完善源</th>
      <th>频道数</th>
      <th>更新时间</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>📺IPTV(IPV6专用)</td>
      <td><a href="https://live.fanmingming.com/tv/m3u/ipv6.m3u">https://live.fanmingming.com/tv/m3u/ipv6.m3u</a></td>
      <td><a href="https://github.com/fanmingming/live/edit/main/tv/m3u/ipv6.m3u">编辑该源</a></td>
      <td>128个</td>
      <td>2023.5.29</td>
    </tr>
    <tr>
      <td>🌏Global直播源</td>
      <td><a href="https://live.fanmingming.com/tv/m3u/global.m3u">https://live.fanmingming.com/tv/m3u/global.m3u</a></td>
      <td><a href="https://github.com/fanmingming/live/edit/main/tv/m3u/global.m3u">编辑该源</a></td>
      <td>194个</td>
      <td>2023.5.21</td>
    </tr>
    <tr>
      <td>📻Radio直播源</td>
      <td><a href="https://live.fanmingming.com/radio/m3u/index.m3u">https://live.fanmingming.com/radio/m3u/index.m3u</a></td>
      <td><a href="https://github.com/fanmingming/live/edit/main/radio/m3u/index.m3u">编辑该源</a></td>
      <td>317个</td>
      <td>2023.5.3</td>
    </tr>
  </tbody>
</table>

## 🛠️工具
- 🆕EPG接口地址(测试)
  -  [https://live.fanmingming.com/e.xml](https://live.fanmingming.com/e.xml)
- M3U8 Web Player
  - Demo🔗 [https://live.fanmingming.com/player/?vurl=https://livedoc.cgtn.com/500d/prog_index.m3u8](https://live.fanmingming.com/player/?vurl=https://livedoc.cgtn.com/500d/prog_index.m3u8)

## 📖说明
- 所有播放源均收集于互联网，仅供测试研究使用，切勿商用。
- 通过M3U8 Player测试直播源需使用https协议的直播源链接。
- 部分广播电台节目播出具有一定的时效性，需要在指定时段进行收听。
- 本项目不存储任何的流媒体内容，所有的法律责任与后果应由使用者自行承担。
- 您可以Fork本项目，但引用本项目内容到其他仓库的情况，务必要遵守开源协议。
- 本项目不保证直播频道的有效性，直播内容可能受直播服务提供商因素影响而失效。
- 所有文件均托管在[GitHub](https://github.com/fanmingming/live)且自动构建，由项目发起人公益维护，欢迎Star本项目或点击[Issues](https://github.com/fanmingming/live/issues)反馈您的问题。
- 您可以编辑本项目的m3u文件或上传缺失的频道Logo到`tv`或`radio`目录下并发起拉取请求，收到请求后我们会对您提交的内容进行验证，审核通过后会自动发布。

## 📔更新
- 2023.6.1
  - ipv6.m3u频道将仅添加支持双栈或纯IPv6播放链接,不再加入纯IPv4链接。
  - 因服务器不堪重负，原IPv6源文件名现已变更为[ipv6plus.m3u](https://live.fanmingming.com/tv/m3u/ipv6plus.m3u)。
  - 对部分频道链接添加了auth参数验证以应对盗链，重新刷新即可正常收看节目。
