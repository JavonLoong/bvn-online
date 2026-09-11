# 第三方组件与历史版本

本说明适用于公开下载的 **1.0.0 原始安装包**。安装包保持原样，其中自编代码的原有 MIT 许可不因源码仓库转为私有而撤销。以包内逐项许可证和版权声明为准。

## Harman SWF 格式适配模块

`app/bvn38/vendor/harman-swf.js` 来自 JPEXS Free Flash Decompiler 的 [HarmanSwfEncrypt.java](https://github.com/jindrapetrik/jpexs-decompiler/blob/master/libsrc/ffdec_lib/src/com/jpexs/decompiler/flash/harman/HarmanSwfEncrypt.java) 的 JavaScript 适配。Copyright (C) 2010–2026 JPEXS；上游署名包含 NathaanTFM。JavaScript 适配：2026 BVN Online contributors。

该模块使用 **LGPL-3.0-or-later**，不提供担保。安装包中保留未压缩、可替换的模块及其调用文件。用户可以替换或修改该模块，并使用修改后的模块运行程序；私有维护声明不限制第三方许可证允许的修改或调试。

[第三方组件源码及许可证附件](https://github.com/JavonLoong/bvn-online/releases/download/v1.0.0/THIRD-PARTY-v1.0.0.zip) 包含该适配模块、GPL/LGPL 许可全文，以及已分发 Ruffle 音频修改的补丁与说明。原安装包中指向旧开发源码树的链接已由本附件补充。

## 运行依赖

| 组件 | 许可与来源 |
| --- | --- |
| @noble/ciphers 2.4.0 | [MIT](https://github.com/paulmillr/noble-ciphers) |
| @noble/hashes 2.4.0 | [MIT](https://github.com/paulmillr/noble-hashes) |
| Ruffle 0.6.0 | [MIT / Apache-2.0](https://github.com/ruffle-rs/ruffle)，安装包保留许可文件；音频阈值补丁见附件 |
| ws | [MIT](https://github.com/websockets/ws) |
| Node.js 22.23.2 | [MIT 及其捆绑组件声明](https://github.com/nodejs/node/tree/v22.23.2)，见安装包 `licenses/NODE-LICENSE.txt` |
| cloudflared 2026.9.0 | [Apache-2.0](https://github.com/cloudflare/cloudflared/tree/2026.9.0)，见安装包 `licenses/CLOUDFLARED-LICENSE.txt` |

原游戏程序、角色、美术、表情素材及原版 AS3 片段不属于本项目自行编写代码的授权范围。公开下载仓库与私有源码仓库均不替第三方材料另行授予许可。
