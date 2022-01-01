备注、notes：
|中文|eng|
|--|--|
|书源权重是必要参数，但可按照自己需求改变，建议1-9999的数量|priority of booksources is required, but you can edit based on needs, number ranging from 1-9999|
|按照文件对应的参数来填写源配置，示例：json文件里显示 `"list": "//ul/li",` 那就在列表(list)里填 `//ul/li`|fill out booksource rules based on the json file, ex: if json shows: `"list": "//ul/li",` then in list type: `//ul/li`|
|若一个参数的对象是空白("")，那就代表没有规则可填，导致有的源可能内容发现少点|if an object corresponds to empty (""), then there is nothing to fill, so less information may be parsed for|
|🏴󠁧󠁢󠁥󠁮󠁧󠁿为英文资源|🏴󠁧󠁢󠁥󠁮󠁧󠁿 represents English content source|
|🔒为正版|🔒 represents official raws site|
|🍪为可登录，可自行修改httpHeaders or 登录url，不一定会带来更多功能![](https://z3.ax1x.com/2021/10/17/5YnSdf.gif)|🍪represents source can login with cookies in httpHeaders or login url, may or may not bring additional functions|
|🪧||
currrently incomplete; 目前未完

# 源-sources
## 文本-text

|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|晋江文学城-Jinjiang Literature City|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/jjwxc.json`|🔒🍪|章节内容请求头可选填，不填反而快点但有的书籍内容显示不了；若不想看到VIP，章节标题规则可修改；高高级搜索若使app崩溃或导致使用体验慢可以修改moreKeys和请求头||
|豆腐小说-Doufu Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/doufu.json`|🔒|||
|书耽小说-Shudan Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shubl.json`|🔒🍪|||
|长佩文学-Changpei Literature|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/gongzicp.json`|🔒🍪|发现板块有点内容获取缺失的问题，但大部分应该能用|discover rules have a slight content problem, but most of it should work|
|笔趣阁xswang|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/biqugexswang.json`|🍪|||
|笔下文学|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bxwxorg.json`|🍪|||
|腐小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/xpsam.json`|🍪|||
|梦阮小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mengruan.json`||||
|All Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/allnovel.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|书宝网|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shubaow.json`|🍪|||
|Collins English Dictionary|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/collinsdictionary.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|字典，额，随便拿来玩玩呗|for fun, because why would you have a source just for dictionaries?|
|NovelUpdates|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/novelupdates.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|资源导航网站，章节内容需按网址修改|resource navigation, content rules should be edited based on what site is redirected to|
|60看书|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/60ks.json`|🍪|网址搜索功能无法用，没规则|no search function|
|101小说典藏网|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/novel101.json`||繁体字，没搜索|traditional characters, no search|
|镇魂小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/zhenhunxiaoshuo.json`||||
|358小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/35851.json`||||
|维基阅读|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/wikiyuedu.json`||书籍也可从书单寻|books can be searched for from the booklist|
|sparknotes|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/wikiyuedu.json`||你用这个app看学习资料干啥？？？|what are you doing reading study guides in this app for???|
||||||
## 图片-images
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|哔哩哔哩漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bilibilimanga.json`|🔒|||
|Bilibili Comics|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bilibilicomics.json`|🔒🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|腾讯动漫|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/macqq.json`|🔒🍪|||
|Mangaowl|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangaowl.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|网站采用cloudflare浏览器检查，所以我使用了Google网页快照：代表更新可能检索不到，且较新的漫画使用不了|the site is using cloudflare browser checks so a Google webpage cache is used to bypass it, which means content may not update and newer releases are not accessible QAQ|
|漫蛙|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manwa.json`|🍪|||
|mangadex|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangadex.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|365Manga|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/365manga.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|Manga4Life|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manga4life.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|Lilymanga|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/lilymanga.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|Suburban Fairy Tales|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/francisbonnet.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|没多少但是三格漫我挺推荐的|there's not much but the comic is one i recommend|
|快看漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/kkmh.json`|🔒🍪|||
|香香腐宅|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/boylove.json`|🍪|||
|包子漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/baozimh.json`||||
||||||
## 音频-audio
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|New Temp Drama House|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/tempyuriradiohouse.json`||单个音频为一个书籍|single audio equates one sole book|
|水哥故事会|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shuige.json`||QAQ 弄不懂maxPage分页规则需求，导致内容缺陷|sob cant figure out maxpage rules for separate pages thus some content will be lost|
|Mixes.Cloud|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mixescloud.json`||单个音频为一个书籍|single audio equates one sole book|
|猫耳fM|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/missevan.json`|🔒|||
||||||
## 视频-video
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
||||||
