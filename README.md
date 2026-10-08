> **本仓库是 [Flow Ring](https://github.com/Dongxibie/flow-ring-phase7-package) 的分阶段开发记录（第 2 步 · 工程脚手架）。**
> 完整产品（源码 / 截图 / 下载即用的 Windows 安装包）在 **[flow-ring-phase7-package](https://github.com/Dongxibie/flow-ring-phase7-package)**，建议从产品仓库开始了解本项目。

---

# Flow Ring · 第 2 步：工程脚手架

Flow Ring 是一个 Windows 桌面快捷环：按住鼠标侧键唤出悬浮圆环，把光标拖向某个方向后松开，即可执行常用动作，不用离开当前窗口。项目按开发阶段拆分为 7 个仓库，本仓库是其中的第 2 步。

## 本步骤完成内容

- C#/.NET 8 多项目 + React 18 + TypeScript + Vite 工程骨架：`flow-ring.sln` + 9 个 csproj + `packages/web`
- 4 个 JSON Schema 与 `docs/ring-protocol.md`（Host 与前端共享的消息协议）

## 验证结果（阶段记录）

- `dotnet build` 零警告零错误
- `dotnet test` 3 个用例全绿
- `pnpm build` 产物可被 WebView2 加载
