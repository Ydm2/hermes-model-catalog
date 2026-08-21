# Hermes Model Catalog

自定义 Hermes 模型精选清单（Model Catalog）。

## 用法

在 `config.yaml` 中让某个 provider 使用本清单：

```yaml
model_catalog:
  providers:
    openrouter:
      url: https://raw.githubusercontent.com/<你的用户名>/<本仓库名>/main/model-catalog.json
```

## 文件

- `model-catalog.json` — 完整清单（含 `openrouter` 和 `nous` 两个 provider），格式与官方
  `https://hermes-agent.nousresearch.com/docs/api/model-catalog.json` 一致。
