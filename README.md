# Fxxk.Bilibili.ADs

一个用来屏蔽B站网页版广告和没什么用的内容的脚本，在[Greasy Fork](https://greasyfork.org/zh-CN/scripts/456127-%E5%8E%BB%E9%99%A4bilibili%E7%BD%91%E9%A1%B5%E7%89%88%E6%97%A0%E7%94%A8%E5%86%85%E5%AE%B9)下载。



### 功能

即使是特殊日子，主页也不会变黑白

#### 全局屏蔽
左上广告按钮	.v-popover-wrap.left-loc-entry
左上app下载	.download-entry.download-client-trigger
右上大会员按钮	.right-entry__outside.right-entry--vip

#### 首页屏蔽
顶部插件提示	.adblock-tips
#### 创作中心屏蔽
首页活动	div[style="display: flex;"]
首页素材	.material-wrp

#### 动态页屏蔽
公告栏	aside.right .bili-dyn-banner
广告	aside.right .bili-dyn-ads
话题（可选）	aside.right .sticky

#### 个人主页屏蔽
创作中心	.section.i-m
#### 视频播放页屏蔽
活动	#activity_vote
右侧广告	.ad-report.ad-floor-exp
#### 专栏页屏蔽
推荐文章	#readRecommendInfo
