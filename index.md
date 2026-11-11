# 天翼云盘签到记录

[![签到状态](https://github.com/kkxx2026/189pan/actions/workflows/main.yml/badge.svg)](https://github.com/kkxx2026/189pan/actions/workflows/main.yml) [![项目主页](https://img.shields.io/badge/GitHub-项目主页-blue?logo=github)](https://github.com/kkxx2026/189pan)

**最后更新:** 2026-11-11 15:44:43 CST

## 快速导航

- 🔄 [查看Action运行记录](https://github.com/kkxx2026/189pan/actions)
- 📋 [查看最新运行](https://github.com/kkxx2026/189pan/actions/runs/42981575285)
- 🏠 [返回项目主页](https://github.com/kkxx2026/189pan)
- ⚙️ [手动触发签到](https://github.com/kkxx2026/189pan/actions/workflows/main.yml)

## 签到详情

# 天翼云盘自动签到抽奖程序

## 执行概览
- **启动时间**: 2026-11-11 15:43:50
- **账户数量**: 1 个

## 账户1

### 执行结果
- **登录状态**: 登录成功
- **签到结果**: 签到失败（无输出）
- **签到输出**: panic: runtime error: index out of range [1] with length 0
- **登录后配置**: users=0 activeUID=0 skLen=0 ckLen=0 size=355
- **链式登录输出**: 	/home/runner/go/pkg/mod/github.com/urfave/cli@v1.21.1-0.***-23c***f/command.go:174 +0x63e github.com/urfave/cli.(*App).Run(0xc00020c380, {0xc00012a000, 0x4, 0x4}) 	/home/runner/go/pkg/mod/github.com/urfave/cli@v1.21.1-0.***-23c***f/app.go:276 +0xb67 main.main() 	/home/runner/work/_temp/cloudpan-src/main.go:552 +0x28f6 
- **探测登录输出**: github.com/tickstep/cloudpan189-go/internal/command.RunLogin({0x7ffc318deb83?, 0x92ec00?}, {0x7ffc318deb99?, 0x781ce3?}) 	/home/runner/work/_temp/cloudpan-src/internal/command/login.go:144 +0x85 main.main.CmdLogin.func6(0xc00017c840) 	/home/runner/work/_temp/cloudpan-src/internal/command/login.go:50 +0x12e github.com/urfave/cli.HandleAction({0x88cc20?, 0x973698?}, 0x5?) 	/home/runner/go/pkg/mod/github.com/urfave/cli@v1.21.1-0.***-23c***f/app.go:523 +0x50 github.com/urfave/cli.Command.Run({{0x92f3fe, 0x5}, {0x0, 0x0}, {0x0, 0x0, 0x0}, {0x93c9ed, 0x18}, {0x0, ...}, ...}, ...) 	/home/runner/go/pkg/mod/github.com/urfave/cli@v1.21.1-0.***-23c***f/command.go:174 +0x63e github.com/urfave/cli.(*App).Run(0xc00020c380, {0xc00012a000, 0x4, 0x4}) 	/home/runner/go/pkg/mod/github.com/urfave/cli@v1.21.1-

---

## 执行统计
- **结束时间**: 2026-11-11 15:44:43
- **运行时长**: 53 秒

✅ **所有账户处理完成！**
