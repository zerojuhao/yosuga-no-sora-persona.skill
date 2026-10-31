# 来源与致谢

## 语料与音色的来源

本仓库的人格规则是从一份公开分享的语音数据集统计出来的。数据集与音色模型的原始出处：

- **视频**：【春日野穹】GPT-SoVITS 穹妹音色模型分享
- **UP 主**：そらちゃん-
- **平台**：哔哩哔哩
- **地址**：https://www.bilibili.com/video/BV12rbs6pEgE/
- **发布**：2026-09-06

感谢 UP 主的分享。这份人格统计能成立，前提就是有人把语料整理出来并公开。

## 本仓库不含数据集

**没有**随仓库分发任何音频、标注文件或音色模型权重。

仓库里只有从语料**统计出来的数字**，以及据此写的规则。想复现统计，请自行获取语料，统计方法写在 `references/evidence.md` 第一节。

## 授权范围

`LICENSE` 里的 MIT 授权覆盖本仓库作者自己撰写的全部内容：人格规则、文档、样例、统计数字。可以商用、可以改、可以再分发，保留版权声明即可。

它**不覆盖**「春日野穹 / SORA」及《缘之空》（ヨスガノソラ）的角色、设定、剧本 —— 那些版权归原作者及发行方，作者无权授权。

This MIT license covers only the original content authored in this repository: the persona rules, documentation, examples and statistics. It does not extend to the character "Kasugano Sora" or "Yosuga no Sora" (ヨスガノソラ), whose rights remain with their respective holders.

## 角色版权

「春日野穹 / SORA」出自《缘之空》（ヨスガノソラ），角色与剧本版权归原作者及发行方所有。

本仓库的 MIT 授权只覆盖作者自己撰写的内容，不延伸至原作素材。仓库本身：

- 不含任何游戏素材（图像、语音、剧本原文）
- 不代表官方，不得冒充官方
- 角色相关的使用请自行评估授权风险

因使用本仓库内容产生的法律风险由使用者承担。

## 隐私

本仓库不包含任何个人信息：

- 没有用户名、路径、主机名、聊天 ID
- 没有 API key、token、cookie
- 没有对话记录

如果 fork 后要加自己的配置，请把密钥放进环境变量或本地 `.env`，不要提交。

## 其他人的作品

本仓库结构参考了开源项目 [ATRI-skills](https://github.com/GzSakura1338/ATRI-skills) 的组织方式（技能文件在根目录、依据放 `references/`、样例放 `examples/`）。仅借鉴排版形式，内容独立撰写。
