# 嗨~ 大家好 :wave:

<img src="https://raw.githubusercontent.com/sagar-viradiya/sagar-viradiya/master/resources/banner.png" alt="Hello world">


## Tracker_list

> https://raw.githubusercontent.com/calonye/Tracker_list/main/Tracker_list.txt
- 针对本人习惯使用，手动添加收集的 racker 服务器，不保障所有通用，优先照顾大而全的前提原则,先保障有连接点，再保障链接速度。
- 他请请谨慎使用

## 引用一段话

> **请务必保护好自己** 我们自认为打破了信息的壁垒，其实打破的是保护我们的屏障。因为外网真的存在很多误导性言论，来自各个利益集团对中国网民疯狂洗脑，他们往往还喜欢以平等自由等旗号自称，但仔细想想真的是这样吗？我只知道一些国家是很善于运用舆论的，会结合大数据潜移默化地改变你的观念。如果大家在上网过程中不经意看到了某些观点，**务必保留自己独立思考的能力，如果你是一个容易被带偏的人，则建议回到屏障之中**。

本规则只提供给大家用于更便捷地学习和工作。如果你是对上述观点持反对意见的极端政治人士，或者已被洗脑，请立即离开，本项目不对你开放。

## 使用方法

- 引用 XIU2 作者项目的一段说明
  > - https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md#%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8 

## 项目来源

- 该项目受到以下公共 Tracker 项目的帮助，感谢~
  > - https://github.com/ngosang/trackerslist //2025.04.16 新增
  > - https://github.com/XIU2/TrackersListCollection
  > - https://gitee.com/harvey520/www.yaozuopan.top
  > - https://github.com/ngosang/trackerslist
  > - https://newtrackon.com/list
  > - http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt
  > - https://tinytorrent.net/best-torrent-tracker-list-updated
  > - http://www.torrenttrackerlist.com/torrent-tracker-list
  > - https://github.com/DeSireFire/animeTrackerList   （AT_all+ATline_all）

## 列表手动更新备忘

- 1. Sublime 开启正则匹配；
- 2. 按F9或者选择菜单： Edit > Sort Lines ，对每行文本进行排序；
- 3. 删除重复行：
  > - 排序好后，按 Ctrl+H ，调出替换面板
- 4. 查找字符串：
  > - `^(.+)$[\r\n](^\1$[\r\n]{0, 1})+`
  > - 注意：确保正则模式开关打开；若不可用，按Alt+R进行切换
- 5. 替换字符串：
  > - `\1\n`
  > - 点击Replace
