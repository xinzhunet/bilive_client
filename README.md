# bilive_client

此分支是一个次分支，特别感谢[主分支](https://github.com/lzghzr/bilive_client)所有参与者的基础奠定

## 关于git pull的那些事
由于本人强迫症发作，我将我的所有commit全部整理了一遍，并且加上了gpg签名，所以童鞋们遇到`git pull`时各种`Auto merge fail`的话，请尝试：
1. `git reset --hard HEAD~25`
2. `git pull`
3. 按一般步骤进行编译运行

不便之处，深感抱歉，可以打我xd

## 使用releases
不存在的，不存在的，永远也不会发release的

## 自行编译
1. 安装[git](https://git-scm.com/downloads)
2. 安装[Node.js](https://nodejs.org/)
3. `git clone https://github.com/Vector000/bilive_client.git` (第一次使用先clone，或直接使用GitHub的Download ZIP)
4. `cd bilive_client`
5. `git pull` (获取项目更新)
6. `npm install`
7. `npm run build`
8. `npm start`

[点此进行设置](http://github.halaal.win/bilive_client/)\
[国内设置地址](http://lzoczr.gitee.io/bilive_client_view/)\
可使用`/doc/index.html`进行本地设置，推荐\

* 感谢大佬的推荐！趴 _(:3」∠)_

## 增添功能
* 定时查询挂机效益和用户各类信息，sc推送支持Markdown
* 根据亲密度赠送礼物
* 添加entry_action以部分规避封禁（玄学）
* 多分区监听，每个分区默认监听3个房间以减少漏抽
* 检测到用户被封禁后发送MSG通知并停抽(采用12h判别，每天检测两次)
* ~~可通过查询服务器来获取提督、舰长信息并领取亲密度奖励~~(已废弃，即时性不好且容易403，感谢 @Dawnnnnnn 项目中的上船监控代码)
* 增添主站任务，适合我这种懒得手动投币的
* 利用[bilive_server](https://github.com/lzghzr/bilive_server)可实现上船和节奏风暴的实时获取
* 自定义监听，在无有效监听服务器填入时使用本地监听
* 用户礼物、上船亲密度统计，已与用户信息合并为全局统计，并可查看当日挂机成果
* 分用户控制四类礼物的领取，可自主设置优先级
* 节奏风暴多次发包以提高中奖率

## TO-DO

咕咕咕，咕咕咕，咕咕咕咕\
