# human-ui

用于网页和应用 UI 开发、改造与审查的 Codex skill。重点是减少模板化视觉，保持清晰层级、产品辨识度和可用性。JEV 判定仅在密钥和服务可用时执行。

## 安装

使用 Codex 的 skill 安装器：

```bash
python3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" \
  --repo unicornboat/human-ui-skill --path human-ui
```

安装后，在下一轮任务中使用 `$human-ui`，或让 Codex 在适用的 UI 任务中自动选用。

也可手动将 `human-ui/` 复制到 `$CODEX_HOME/skills/`（未设置时为 `~/.codex/skills/`）。

JEV 可选：使用前设置 `TYPESAFE_API_KEY`。未设置或服务不可用时，skill 仍可正常用于 UI 开发。
