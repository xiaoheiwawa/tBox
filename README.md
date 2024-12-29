## 建议将仓库转存到自己的github，不定期删除。

## 温馨提示
夸克网盘需最低88会员观看、UC网盘+天翼云盘无需会员。由于网盘自身限制，夸克+UC切换剧集时建议间隔最少10秒。（播放网盘资源时，建议设置中调整播放器缓存为128M）

搜索影片之前，请关闭不常用的站源。

## 点播源： [api.json](https://ghproxy.cn/https://raw.githubusercontent.com/alantang1977/tBox/refs/heads/main/api.json)

## 规则或APP更新
天翼云盘：首次使用在设置中登录天翼云盘及打开一次雷鲸。
天翼云盘的cookie有IP验证,切换IP后cookie会无效，且ipv4和ipv6的cookie无法混用。建议在电信的WIFI环境下使用(ipv4)。
如雷鲸无返回数据，请在设置中打开一次该站点，该站点有时需效验。

### 12月20日：增加bili.js(哔哩哔哩) 可自行转存后修改变量拓展为：儿童教育、地方戏曲等。
##
### V1.0.11版更新：优化搜索、增加豆瓣、酷我音乐（请在设置中登录哔哩哔哩，VIP歌曲通过该站解析）

1.0.11版以上请搭配new.json配置使用：

IOS影视点播源： new.json

IOS听书听歌源：music.json

##
应大家要求，补充安卓端。（音频播放器不适配安卓端，音乐+听书默认使用：推荐播放器）

安卓端视频源： new.json

##
## 配置中：
recommend为1时为推荐源，点击影片时会跳转搜索页面。
```
{
	"key": "douban",
	"name": "👍豆瓣┃推荐",
	"type": 5,
	"searchable": 0,
	"filterClass": "",
	"firstClass": "",
	"filterPlay": "",
	"firstPlay": "",
	"ext": "https://ghproxy.cn/https://raw.githubusercontent.com/leevi0709/tBox/refs/heads/main/newjs/douban.js",
	"flagable": 0,
	"filterPlayFileKeywords": "",
	"keepPlayFileKeywords": "",
	"recommend": "1"
}
```
## selectedPlayer为2时打开详情页后自动选择音频播放器。

酷我音乐搜索方法：

1：直接输入歌曲名称（例如：爱在西元前）

2：输入歌手文字及姓名（例如：歌手周杰伦）

3：输入专辑文字及名称（例如：专辑叶惠美、周杰伦专辑）
```
{
	"key": "kuwosong",
	"name": "🎵酷我┃音乐",
	"type": 5,
	"searchable": 1,
	"filterClass": "",
	"firstClass": "",
	"filterPlay": "",
	"firstPlay": "",
	"ext": "https://ghproxy.cn/https://raw.githubusercontent.com/leevi0709/tBox/refs/heads/main/newjs/kuwosong.js",
	"flagable": 0,
	"filterPlayFileKeywords": "",
	"keepPlayFileKeywords": "",
	"selectedPlayer": "2"
}
```
## 该直播源大部分频道需要ipv6访问，其他源请自行从github搜索。
```
直播源名称：电视直播

源链接：https://tv.iill.top/m3u/Gather

User-Agent: okHttp

直播源名称：网络直播

源链接：https://tv.iill.top/m3u/Live

User-Agent: okHttp
```

 
 ##
 
 酷我音乐搜索方法：
 
 1：直接输入歌曲名称（例如：爱在西元前）
 
 2：输入歌手文字及姓名（例如：歌手周杰伦）
 
 3：输入专辑文字及名称（例如：专辑叶惠美、周杰伦专辑）
 
## APP简介
tBox是一款多功能APP空壳，支持导入直播源、影视和听书源。

在影视点播方面，用户可播放4K网盘资源，也可自行编写简单的规则实现嗅探网页播放; 听书模式则允许后台熄屏播放。

tBox虽然在UI设计上借鉴了猫影视的风格，但其源码是完全不同的。
猫影视作为一款经典应用，我个人作为业余开发者，自认为难以超越。
我从猫影视的安卓低版本就开始使用，后来也见证了tvbox的诞生。非常感谢各位开发者，让我们能够实现观影自由。

##
**关于tBox的更新：**

* 由于个人工作繁忙，我并未计划频繁更新tBox，只要APP能正常使用，满足基本的观影需求即可。
* 我个人的要求比较简单，能流畅观影就好，从未想过与其他软件进行比较。

**最后，感谢大家的理解和支持！** 
