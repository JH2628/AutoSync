[![Page Views Count](https://badges.toozhao.com/badges/01FVFWHTPMF5JQEWK1AW75VNAE/green.svg)](https://badges.toozhao.com/stats/01FVFWHTPMF5JQEWK1AW75VNAE "Get your own page views count badge on badges.toozhao.com")

为了避免各位大佬删库或者给封库找不到组织，下面搜集备份了各位大佬的京东脚本，每1小时拉取一次，感谢各位大佬的付出。

以下脚本全无修改，原封不动的拉取原仓库。各位朋友也可以fork本仓库，然后拉取脚本到自己的仓库，以免给各位大佬添加麻烦。

自动拉取教程请看这里： https://mp.weixin.qq.com/s/gOA8PSwLfhp9bLLnBkJf-Q

下面的青龙拉取地址需改为自己的仓库地址

    ql repo https://github.com/自己的仓库地址/AutoSync.git + “参数” + "库名称”

自己本人目前在用的是 faker的日常脚本 + KingRan开卡脚本 + JDHelloWorld的几个自动上传助力码到助力池的脚本

国内机拉库需挂代理，可用本人利用CF免费资源搭建的代理 https://i.gitcf.workers.dev/

# AutoSync

https://github.com/shufflewzc/faker2/tree/main （含助力池）

    ql repo https://github.com/JH2628/AutoSync.git  "jd_|jx_|gua_|jddj_|jdCookie" "activity|backUp" "^jd[^_]|USER|function|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate|ql|JDSignValidator" "faker2"

https://github.com/shufflewzc/faker3/tree/main （不含助力池）

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|gua_|jddj_|jdCookie" "activity|backUp" "^jd[^_]|USER|function|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate|ql|JDSignValidator" "faker3"

## https://github.com/ccwav/QLScript2 （青龙2.10.3之后版本拉库命令，包含sendNotify）

    ql repo https://github.com/JH2628/AutoSync.git "jd_" "NoUsed" "ql|sendNotify|utils|USER_AGENTS|jdCookie|JS_USER_AGENTS" "ccwav"

## https://github.com/KingRan/KR

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR" "KingRan"

只拉取KingRan的开卡脚本，其他不拉取，青龙命令需更改为：

    ql repo https://github.com/JH2628/AutoSync.git "jd_opencard|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR" "KingRan"

## https://github.com/okyyds/yydspure/tree/master

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|gua_|jddj_|jdCookie" "activity|backUp" "^jd[^_]|USER|function|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate|ql|JDSignValidator" "okyyds"
    
## ~~https://github.com/bullfly666/percollect/tree/main~~ 已删库 2022/02/19

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_" "backUp|icon" "^jd[^_]|USER|sendNotify|sign_graphics_validate|JDJR|JDSign|ql" "bullfly666"

## https://github.com/JDHelloWorld/jd_scripts

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|getJDCookie" "backUp" "^jd[^_]|USER|utils|sendNotify|^TS|JD_" "JDHelloWorld"

## https://github.com/gys619/Absinthe/tree/main

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|jddj_|gua_|getJDCookie|wskey" "activity|backUp" "^jd[^_]|USER|utils|ZooFaker_Necklace|JDJRValidator_|sign_graphics_validate|jddj_cookie|function|ql|magic|JDJR|JD" "gys619"

## ~~https://github.com/passerby-b/JDDJ~~ 已删库 2022/02/23

    ql repo https://github.com/JH2628/AutoSync.git "jddj_" "_getck" "^jd[^_]|jddj_cookie|sendNotify" "passerby-b"

## https://github.com/he1pu/JDHelp

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|getJDCookie" "activity|backUp|jd_delCoupon" "^jd[^_]|USER|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate" "he1pu"

~~## faker2 backup 2022/01/29 23:34~~ faker 已重开仓库

    ql repo https://github.com/JH2628/AutoSync.git "jd_|jx_|gua_|jddj_|getJDCookie" "activity|backUp|Coupon" "^jd[^_]|USER|sendNotify|function|utils|JDJRValidator_|ZooFaker|^sign" "faker2-backup"
    
~~## ccwav backup~~ ccwav 已重开仓库

    ql repo https://github.com/JH2628/AutoSync.git "jd_" "NoUsed" "ql|sendNotify|utils|USER_AGENTS|jdCookie|JS_USER_AGENTS" "ccwav-backup"
