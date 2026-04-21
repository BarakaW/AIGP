# AI生成PRD文档（清晰需求版本）

## 使用场景
用于已经和AI在上下文中明确了需求，或有过往PRD文档迭代，或发送页面截图生成PRD

不要在需求不明确时使用这个skill

## 使用方法
1. 下载zip包
2. 将skills放入IDE的目录中
   |工具|目录|
|---|---|
|**trae-cn**|`.trae-cn/skills/`| 
|**Antigravity**|`.gemini/skills/`|
|**Cursor**|`.cursor/skills/`|
|**Codex**|`.codex/skills/`|
4. 确保skill正确加载并处于启用状态，必要时可能需要重启IDE
5. 在会话窗口中输入@AIGCC+输出PRD，确保该skill被调用
   eg：@AIGCC，帮我输出PRD
