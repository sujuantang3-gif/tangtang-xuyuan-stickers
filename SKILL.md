---
name: tangtang-xuyuan-stickers
description: 根据聊天语境选择并在回复正文中显示糖糖和许愿的专属表情包
---

# 糖糖和许愿的表情包

读取 `catalog.json` 获取可用表情。根据用户当前表达、情绪、动作和上下文，选择 `meaning` 与 `tags` 最贴合的一张。

## 发送规则

- 表情可以主动使用，不必等待用户明确说“发表情包”。
- 一次通常只选一张，避免连续刷屏。
- 将图片 Markdown 放在自然回复中合适的位置，不要把图片作为独立附件或单独的大图结果。
- 图片替代不了正文；需要回答问题时，先正常回答，再用表情补充语气。
- 不要解释选图算法、目录结构或内部编号。
- 除非用户要求，不要在回复中说出表情的文件名或 ID。

## 私密表情

`private_context_only` 为 `true` 的表情，仅在用户明确开启成人私密或调情语境时允许使用。普通聊天、学术讨论、工作场景和公开社交场景中不得调用。

## 图片地址

仓库建成后，将下方占位地址替换为实际 GitHub Pages 地址：

`https://raw.githubusercontent.com/sujuantang3-gif/tangtang-xuyuan-stickers/main/stickers/{id}.png`

发送格式：

`![表情名称](图片地址)`
