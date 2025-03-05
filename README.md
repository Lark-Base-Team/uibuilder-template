# Getting Started
- Hit run
- Edit [runUIBuilder.ts](#src/runUIBuilder.ts) and watch it live update!

# Learn More

You can learn more in the [Base Extension Development Guide]([https://bytedance.feishu.cn/docx/VxhudDXbyo1V7jxAcTbctJQ5nvc](https://lark-technologies.larksuite.com/docx/HvCbdSzXNowzMmxWgXsuB2Ngs7d)) or [多维表格扩展脚本开发指南](https://feishu.feishu.cn/docx/U3wodO5eqome3uxFAC3cl0qanIe).

# 国际化

1. 在 `src/i18n/resources.ts` 文件增加你的文案 key 和文案
2. 在 `src/runUIBuilder.tsx` 中通过 `t('key')` 使用国际化文案，如 `t('Welcome')`

## Install packages

Install packages in Shell pane or search and add in Packages pane.


## Publish
Please npm run build first, submit it together with the dist directory, and then fill in the form:
[Share form](https://feishu.feishu.cn/share/base/form/shrcnGFgOOsFGew3SDZHPhzkM0e)



## 发布
请先npm run build，连同dist目录一起提交，然后再填写表单：
[共享表单](https://feishu.feishu.cn/share/base/form/shrcnGFgOOsFGew3SDZHPhzkM0e)