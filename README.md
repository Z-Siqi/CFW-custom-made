# Clash for Windows 机场专用版

**这个版本是针对如下两个问题所发布的版本**
[#4](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/issues/4) 

### 这个特制版本将更改的内容:
* 汉化
* 去除广告
* 去除更新

***

**下载[自动替换脚本](https://github.com/Z-Siqi/CFW-custom-made/releases/tag/Auto-Script)**

**下载[已去除广告，更新版本](https://github.com/Z-Siqi/CFW-custom-made/releases/tag/Clash-for-Windows)**

***

### 这个版本不会频繁的适配Clash for Windows

> 这个版本的适配不会频繁的更新, 甚至是长时间不更新

如果你需要未兼容版本的移除广告及更新，可以下载[教程](https://github.com/Z-Siqi/CFW-custom-made/raw/main/Clash.for.Windows.remove.ads.and.update.zip)及需要的[工具](https://github.com/Z-Siqi/CFW-custom-made/raw/main/Clash-for-Windows_%20Chinese-%20tools.zip), 然后自己制作

***

如有侵权, 请私信我删除

***

### 针对机场的特殊定制版本

Clash for Windows关于中的广告内容是可以客制化的, 且及其容易实现。这意味着你可以向Clash for Windows中植入你自己的推销信息

**具体实现方法:**

将`app.asar`中的`renderer.js`文件里的`https://raw.githubusercontent.com/Fndroid/ads/master/ads_v2.json`链接替换掉及可实现

**[下载Clash for Windows v0.20.0的举例版本](https://github.com/Z-Siqi/CFW-custom-made/raw/main/Customize/CFW-0.20.0_app.7z)**

使用方法: 将文件解压至`Clash.for.Windows-0.20.0-win/resources/`中

替换的链接内容及格式:

<details><summary>ads.js</summary>

```
{
  "feedback": [
    {
      "img": "https://raw.githubusercontent.com/Z-Siqi/CFW-custom-made/main/Customize/eg-picture-ads.png",
      "click": "https://github.com/Z-Siqi/CFW-custom-made"
    },
    {
      "img": "https://raw.githubusercontent.com/Z-Siqi/CFW-custom-made/main/Customize/eg-picture-ads.png",
      "click": "https://github.com/Z-Siqi/CFW-custom-made"
    }
  ]
}
```
**注释:**

`"img"`中的链接是广告图片的链接

`"click"`中的链接是点击后跳转的网页

</details>

#### 广告

*请先查看举例版本再发送`Issues`*

如果需要我帮忙汉化和植入链接或更改一些选项, 请通过`Issues`发问题联系我

收费大概`30CNY`一个版本(仅包括植入自定义广告所需的js链接和移除更新)

如果还需要移除更改一些选项的超链接和名称, 每更改一个选项多收费`20CNY`~`50CNY`(因为复杂性较高) 

但兼容后续版本正常情况下收费`30CNY`, 无论需要更改多少个选项

***

**前往[Clash for Windows汉化版仓库](https://github.com/Z-Siqi/Clash-for-Windows_Chinese)**

**前往[Clash for Windows原版仓库](https://github.com/Fndroid/clash_for_windows_pkg)**
