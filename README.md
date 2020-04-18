# cnblogs_theme

[![](https://data.jsdelivr.com/v1/package/gh/cl9000/cnblogs_theme/badge)](https://www.jsdelivr.com/package/gh/cl9000/cnblogs_theme)

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


