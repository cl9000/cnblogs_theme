# cnblogs_theme

[![](https://data.jsdelivr.com/v1/package/gh/cl9000/cnblogs_theme/badge)](https://www.jsdelivr.com/package/gh/cl9000/cnblogs_theme)

### 博客园主题
[cjunn](https://www.cnblogs.com/cjunn#/cnblog/works/category/all/1/1)
[yjlaugus](https://www.cnblogs.com/yjlaugus/#/cnblog/works/category/all/1/1)

### 应用建议
* 一、使用作者的 jsdelivrCDN 部署，但不太稳定，对于新手而言完全可以，运行有些耗内存，调试不太理想，主题也就过过瘾
 1、[atum - CDN](https://www.jsdelivr.com/package/gh/cjunn/atum)
 1.1、[cnblogs_theme - CDN](https://www.jsdelivr.com/package/gh/YJLAugus/cnblogs_theme)
 2、[atum - github](https://github.com/cjunn/atum)、
 2.1、[cnblogs_theme - github](https://github.com/YJLAugus/cnblogs_theme)
* 二、gitee部署，需要修改配置文件
    1. clone代码，本地可运行调试，修改调整
    2. 编译打包待部署，建议使用gitee的静态网站服务，本人试过coding，cnblog加载源文件时403。所以基本的是gitHub + jsdelivr(cdn) + gitee(giteePages)即可
    3. cnbog 配置必要的参数版本号 + 加载文件（可CDN或gitee），或不配置（前提代码中全更改配置）。建议必要配置包版本号（这样不用每次部署CDN）
    4. 
``` js
<script>
$("link").remove();$("script").remove();$(function(){$("link").remove();$("script").remove()});
window.blogCommentManager=function(){this.renderComments=function(){}};
window.loadViewCount=function(){};
window.loadNewsAndKb=function(){};
window.loadBlogSignature=function(){};
window.LoadPostCategoriesTags=function(){};
window.LoadPostInfoBlock=function(){};
window.GetPrevNextPost=function(){};
window.loadBlogCalendar=function(){};
window.loadBlogSideColumn=function(){};
window.loadBlogTopLists=function(){};
window.GetHistoryToday=function(){};
window.deliverAdT2=function(){};
window.getFollowStatus=function(){};
window.deliverAdC1=function(){};
</script>

<style type="text/css">body{margin:0;padding:0;overflow:hidden;margin-top:100%}#shade_animal_wrap{opacity:1;margin:0;padding:0;display:flex;position:absolute;top:0;left:0;right:0;bottom:0;align-items:center;justify-content:center;height:100vh;width:100%;background-color:#f2f2f2;z-index:99999;transition:all 1s ease 0s;}.lds-hourglass{display:inline-block;position:relative;width:64px;height:64px;transform:translateX(-30px) translateY(-60px);}.lds-hourglass:after{content:" ";display:block;border-radius:50%;width:0;height:0;margin:6px;box-sizing:border-box;border:60px solid #fff;border-color:#ff8d00 transparent #ff3004 transparent;animation:lds-hourglass 1.2s infinite;}@keyframes lds-hourglass{0%{transform:rotate(0);animation-timing-function:cubic-bezier(0.55,0.055,0.675,0.19);}50%{transform:rotate(900deg);animation-timing-function:cubic-bezier(0.215,0.61,0.355,1);}100%{transform:rotate(1800deg);}}
</style><div id="shade_animal_wrap"><div class="lds-hourglass"></div></div>
<script type="text/javascript">
(()=>{
let p={};
// 博客账号名
p.blogAcc = "xuxn-pro";
// 博客名称
p.blogName = "Xuxn-pro";
// 博客ID号
p.blogId = "596579";
p.blogPostId ="12712390";
// 博客账号的GUID号
p.blogUserGuid = "9665ac0a-1b37-45fc-c61c-08d4ef52ecb5";
p.blogIndexPath = "https://www.cnblogs.com/xuxn-pro/";
p.sendPage = "https://msg.cnblogs.com/send/xuxn-pro";
p.subPage= "https://www.cnblogs.com/xuxn-pro/rss";
p.headBackImg = "https://images.cnblogs.com/cnblogs_com/xuxn-pro/1716711/o_200416085133leg.jpg";
p.bigBackImg = "";
p.blogSign = "天道酬勤";
p.aboutmeHtml="<img src='https://pic.cnblogs.com/avatar/1236795/20200416142342.png'/>"
p.avatarSign = "职位";
p.ingTitle="找补回来，TMD";
p.blogFriendList = [{name: 'cl9000', url: 'https://cl9000.github.io/'}];
p.blogUsedLinks= [{name: 'cl', url: 'https://cl9000.github.io/'}];
p.musicIds = [ "26329928"];
p.qq="*****";
p.email="cl9000@126.com";
p.github="cl9000";
p.mainExtNav=[{title: "仓库", url: "https://github.com/cl9000", icon: "icongithub"}];

//扩展CSS样式URL	
p.extCss = ["https://files.cnblogs.com/files/xuxn-pro/xuxnex.css", "https://at.alicdn.com/t/font_1630741_bf02j4m9mhg.css"];
// 扩展JS脚本URL
p.extJs=[""];

//JS与CSS引用URL地址
//p.staticSrc="https://cdn.jsdelivr.net/gh/cjunn/atum@";
p.staticSrc = "https://cl9000.gitee.io/cnblog_vue/releases/";
//引用的版本号
p.staticVer ="20200418231400";
//网页Icon的URL地址
p.staticIco="https://pic.cnblogs.com/avatar/1236795/20200416142342.png";
//粉丝详情,博客文章搜索,闪存接口API
//p.extendApiPath="https://www.cjunn.xyz/cnblog-api";
//博客图片库URL地址
//p.extendStylePath="https://cl9000.gitee.io/cnblog_vue";

window.__BLOG_CONFIG__=p;
})();
</script>
<!-- <script type=text/javascript src="https://cdn.jsdelivr.net/gh/cl9000/cnblogs_theme@1.1/cnblogLoader.js"></script> -->
<script type=text/javascript src="https://cl9000.gitee.io/cnblog_vue/cnblogLoader.js"></script> 
```


### cnblog_theme_code 源代码