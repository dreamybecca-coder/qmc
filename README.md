# QMC 研究协议

QMC（Question · Map · Cognition）帮助你从一个陌生问题开始，选择适合的研究方法，根据证据修正判断。适用于需要比较解释、跨领域取材或持续跟进的问题。举例来说，研究一个联盟链项目时，可以分别核对谁宣布参与、谁实际使用、哪些材料能证明使用持续至今。

当前试用快照为 **2026-11-23**。仓库根目录的 [SKILL.md](SKILL.md) 是入口，配套的 [references](references) 提供原典解释、经验与因果、决策与价值、跨域推演和续研记录。运行内容是 Markdown 文件，无需单独配置 API 密钥或安装 Python 包。查证外部事实时，运行环境需要能读取原始材料，或由用户提供材料。

## 在另一台电脑的 Codex 中安装

在目标电脑打开 Codex，发送以下请求即可固定安装本次快照：

> 使用 skill-installer 从 GitHub 的 dreamybecca-coder/qmc 安装到我的用户级 skills 目录。ref 为 snapshot-2026-11-23，技能在仓库根目录（path 为 .），安装名为 qmc。

也可以手动安装。下载 [QMC 试用包](https://github.com/dreamybecca-coder/qmc/releases/download/snapshot-2026-11-23/qmc-workbuddy-2026-11-23.zip)，解压到下列用户目录中新建的 qmc 文件夹：

- macOS / Linux 使用 `~/.codex/skills/qmc/`
- Windows 使用 `%USERPROFILE%\.codex\skills\qmc\`
- 自定义了 `CODEX_HOME` 时使用其下的 `skills/qmc/`

安装后，直接打开该目录应能看到 SKILL.md、LICENSE 和 references/。如果已经有本地修改过的同名技能，请先备份。打开新的 Codex 对话，输入：

> $qmc 我想了解一个公开的联盟链案例。请分别核实参与方、实际使用证据和仍待验证的问题，并给出原始出处。

在技能列表中确认 qmc 已被识别，再检查实际回答是否读到了来源、是否区分了公告与使用证据。

## 在 WorkBuddy 中导入

下载上面同一个 ZIP。在「技能 → 添加技能 → 上传技能／导入本地技能包」选择 ZIP 文件。安装后在目标专家对话中明确要求使用 QMC。专家身份由自己的专家卡管理。客户端中的导入与调用需要分别验证。[WorkBuddy 技能说明](https://www.workbuddy.ai/docs/workbuddy/From-Beginner-to-Expert-Guide/Function-Description/Skills)

## 项目来源和许可

早期 QMC 受 [QBS](https://github.com/LearnPrompt/qbs) 启发。固定六阶段流程的 [v2.3 历史源码](https://github.com/dreamybecca-coder/qmc/tree/7110173092ec8d709c8eaab453a3f238ab63768c) 可供对照。项目采用 [MIT License](LICENSE)。
