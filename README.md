# not-open-source

在 Github 上 不开源/不完全开源 的具有一定知名度的项目(markdown 型不计入，需要项目主体构成是代码)

## 声明

1. 不开源是作者的权力，除所有者外任何组织或个人不得强制其开源。（因此本仓库不叫 fake-open-source，某些项目因为情况特殊不宜开源可以理解）
2. 在 Github 上存放项目不等于项目开源，release 与仓库代码不一定有关联。
3. 公开源代码但不开放源码许可也不等于项目开源。
4. 源码开源，文档收费将另行列出。

## 补充说明
1. 开源，但代码编译出的程序与 release 版本程序不一致（指外观、功能上的不一致，参考 [Reproducible_builds](https://en.wikipedia.org/wiki/Reproducible_builds)）也视为不完全开源（如 [VS Code](https://github.com/microsoft/vscode) ）
2. 开源，但携带不影响其功能实现的二进制程序视为完全开源（如 [Calci-kernel](https://github.com/Iraka-C/Calci-kernel)，仓库名称与描述显式声明了是 Calci 的组件，不易混淆，因此携带 Calci 的二进制程序不视为不完全开源）
3. 开源，但其为闭源程序的开源实现或部分视为完全开源，但名称应有区分，且开源部分能独立工作。（如 Chromium，名称与 Chrome 有明显区分，Chrome 不开源但 Chromium 仍视为完全开源）
4. 开源，如果有引入的外部功能或 SDK 依赖闭源的第三方服务需要显式声明，如文件转换服务依赖在线的网站 API 实现，但部分不属于代码实现范畴的数据类服务不计算在其中，如某网站的第三方客户端依赖原网站 API，天气程序程序调用第三方天气 API。
5. 不开源，但借助开源社区的力量完善翻译、汇报 Bug 等将不计入，例如 Typora 的 [Typora-i18n](https://github.com/typora/Typora-i18n) 和 [typora-issues](https://github.com/typora/typora-issues)，无论的仓库名称还是仓库描述都不会让人产生其本体开源的错误认知。
6. 因为众所周知的原因，私搭信道进行国际联网的软件基本都不开源，且仓库容易被和谐不便记录，因此不记录在本仓库。
7. 项目开源，但是项目嵌入埋点，广告不视为不开源。
8. 对于未指定开源许可证，但作者承认开源的视为开源，例如 学无止下载器 的 [Wiki 8.该软件开源了吗？](https://github.com/PyJun/Mooc_Downloader/wiki#8%E8%AF%A5%E8%BD%AF%E4%BB%B6%E5%BC%80%E6%BA%90%E4%BA%86%E5%90%97) 中，作者用“软件所有源代码已经上传至 GitHub”作为回应，可视为作者做出了肯定答复，即承认开源。

## 正文

| 名称 | 开源许可证 | 类型 | 理由 |
| - | - | - | - |
| [sablejs](https://github.com/sablejs/sablejs) | [sablejs JavaScript Engine](https://github.com/sablejs/sablejs/blob/master/LICENSE) | 核心代码不开源 | ./runtime.js 文件存在压缩混淆 | 
| [edusoho](https://github.com/edusoho/edusoho) | [EduSoho开源协议V1.0版本](https://github.com/EduSoho/EduSoho/wiki/EduSoho%E5%BC%80%E6%BA%90%E5%8D%8F%E8%AE%AEV1.0%E7%89%88%E6%9C%AC) | 前端代码不开源 | ./web/h5/ 目录下代码存在压缩混淆 |
| [miniblink49](https://github.com/weolar/miniblink49.git) | Apache-2.0 License | 后续版本不开源 | 作者声明暂停开源 |
| [WebRunLocal](https://github.com/wangzuohuai/WebRunLocal) | MIT License/[PluginOK(牛插)中间件(以下简称PluginOK)软件使用授权协议](https://github.com/wangzuohuai/WebRunLocal/blob/master/license.txt) | 核心代码以及 SDK 不开源 | 仅二进制构建产物 |
| [JimuReport](https://github.com/jeecgboot/JimuReport) | Apache-2.0 License | 核心代码以及 SDK 不开源 | pom.xml 核心依赖 org.jeecgframework.jimureport 不开源 |
| [学无止下载器](https://github.com/PyJun/Mooc_Downloader) | 未指定具体开源许可证，但等同开源([Wiki 8.该软件开源了吗？](https://github.com/PyJun/Mooc_Downloader/wiki#8%E8%AF%A5%E8%BD%AF%E4%BB%B6%E5%BC%80%E6%BA%90%E4%BA%86%E5%90%97)) | 后续版本不开源 | 作者声明暂停在 GitHub 上更新后续代码 |
| [VS Code](https://github.com/microsoft/vscode) | MIT License | 仓库编译产物与仓库名称存在分歧 | VSCode 可视为微软在 Code-OSS 基础上进行二次开发的产品，既然如此那 Code-OSS 的仓库名称应该叫做 code-oss 而非 vscode，虽然微软在 README 中进行了详细说明但仍有误导性 |
| [videoWater](https://github.com/suifengqjn/videoWater) | Apache-2.0 license | 核心代码未开源 | 经审查无法编译出与宣传相符的预期产物 |
| [LarkMidTable](https://github.com/birdLark/LarkMidTable) | GPL-3.0 license | 前端代码不开源 | larkmidtable-web/admin/src/main/resources/static/ 目录下代码存在压缩混淆 |
| [proximabilin](https://github.com/alibaba/proximabilin) | Apache-2.0 license | 核心代码未开源 | 函数库 libproxima.so 未开源 |
| [jumpserver](https://github.com/jumpserver/jumpserver) | GPL-3.0 license | 核心组件未开源 | [lion](https://github.com/jumpserver/lion-release.git) 和 [magnus](https://github.com/jumpserver/magnus-release.git) 不开源 |
| [沉浸式双语网页翻译扩展(immersive-translate)](https://github.com/immersive-translate/immersive-translate) | [EULA](https://github.com/sablejs/sablejs/blob/master/LICENSE) | 有且仅构建产物 | 误导开源，但仅发布构建产物 |
| [卷王(SurveyKing)](https://github.com/javahuang/SurveyKing) | MIT License | 前端代码不开源 | 缺少 /client 目录下的代码 |
| [wgcloud](https://github.com/tianshiyeben/wgcloud) | Apache-2.0 license | 后续版本不开源 | 来源 [不再开源了](https://www.v2ex.com/t/679704)，后续 3.x 版本不开源，但 release 仍在发布 |
| [sqlflow](https://github.com/sqlparser/sqlflow_public) | Apache-2.0 license | 迷惑性开源 | [官网](https://sqlflow.gudusoft.com/#/)右上角放了个 Github 的链接，点过来却只有 demo 和材料 |

### 不开源的 VSCode 插件

+ [FnMap - 函数地图](https://marketplace.visualstudio.com/items?itemName=chensuiyi.fn-map)，付费插件，Repository 指向 [yicode](https://gitee.com/yicode-team/yicode)，但经核查未发现相关性。

## 点名批评

+ Mars3D，开源 demo 也能自称开源真是够了。
