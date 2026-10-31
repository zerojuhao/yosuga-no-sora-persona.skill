# 来源与致谢

## 语料来源

本仓库的人格规则由一份公开发布的语音数据集统计导出。原始出处：

| 项目 | 内容 |
| :--- | :--- |
| 标题 | 【春日野穹】GPT-SoVITS 穹妹音色模型分享 |
| 作者 | そらちゃん- |
| 平台 | 哔哩哔哩 |
| 地址 | https://www.bilibili.com/video/BV12rbs6pEgE/ |
| 发布日期 | 2026-09-06 |

数据集技术规格（语音条数、时长、采样率、标注格式等）见 `references/evidence.md` 第一节。

感谢作者的整理与公开分享。本仓库的统计工作以该数据集为前提。

## 本仓库不含数据集

本仓库不分发任何音频、标注文件或音色模型权重，仅有由语料导出的统计指标与依据其撰写的规则。

复现统计需自行获取语料；统计口径见 `references/evidence.md`。

## 授权范围

`LICENSE` 中的 MIT 授权覆盖本仓库作者撰写的全部内容：人格规则、文档、样例、统计结果。可商用、可修改、可再分发，保留版权声明即可。

该授权**不覆盖**「春日野穹 / SORA」及《缘之空》（ヨスガノソラ）的角色、设定与剧本，其版权归原作者及发行方所有，作者无权就此授权。

This MIT license covers only the original content authored in this repository: the persona rules, documentation, examples and statistics. It does not extend to the character "Kasugano Sora" or "Yosuga no Sora" (ヨスガノソラ), whose rights remain with their respective holders.

## 角色版权

「春日野穹 / SORA」出自《缘之空》（ヨスガノソラ），角色与剧本版权归原作者及发行方所有。

本仓库不含任何游戏素材（图像、语音、剧本原文），不代表官方，不得以官方名义发布。角色相关的使用需自行评估授权风险。

因使用本仓库内容产生的法律风险由使用者承担。

## 隐私

本仓库不含任何个人信息：无用户名、路径、主机名、会话标识，无凭证与密钥，无对话记录。

fork 后如需添加本地配置，请将密钥置于环境变量或本地 `.env`，并确保其不被提交。

## 参考的其他项目

本仓库的目录组织参考了开源项目 [ATRI-skills](https://github.com/GzSakura1338/ATRI-skills) 的形式（入口文件置于根目录，依据与样例分册）。仅借鉴结构，内容独立撰写。
