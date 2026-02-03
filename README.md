# multi-ocr
一个支持AI OCR和OCR服务商的Obsidian插件

支持添加多个AI供应商和自动抓取所有模型并进行选择或者自己添加模型，自定义提示词，自定义json参数。

支持七大OCR服务商，包括PDF Craft、MinerU、TextIn、Paddle OCR-VL、Mistral OCR、Gitee AI的HunyuanOCR和GLM OCR。支持OCR服务商OCR参数设置。

支持本地其他文件夹文件的选择，支持单独粘贴url。

返回的Markdown内容可以返回当前笔记，可以返回其他特定笔记，也可以新建笔记。

![1000179073](https://github.com/user-attachments/assets/86332ce0-6dc3-4d33-8e44-d38e88e2a86c)
![1000179072](https://github.com/user-attachments/assets/964a348f-48fb-494d-a720-934763bf8857)
![1000179071](https://github.com/user-attachments/assets/e5def192-21d9-41f1-bd0e-2c3157fa87f7)
![1000179070](https://github.com/user-attachments/assets/3eae8c48-6764-4280-a06c-5ff6bacf8b0f)
![1000179069](https://github.com/user-attachments/assets/40838e27-4c76-466d-957e-ba5152f39daa)

开始使用

Multi OCR 目前尚未上架 Obsidian 社区插件商店，请按照以下步骤手动安装。

手动安装

前往 Releases 页面下载最新版本的zip

在你的 Vault 插件目录下创建文件夹：<vault>/.obsidian/plugins/obsidian-multi-ocr/

将下载的文件解压缩复制到该文件夹中

打开 Obsidian 设置 → 社区插件

在插件列表中启用 "Multi OCR"

在插件设置中配置你的相关设置

注意事项

AI OCR只支持图片的ocr，本地和url都可以。

PDF Craft只支持pdf的ocr，只支持url。

Gitee AI模型选择HuanyuanOCR只支持图片的ocr，本地和url都可以。

GLM OCR支持图片和pdf的ocr，本地和url都可以。

TextIn支持图片和pdf的ocr，本地和url都可以。

Mistral OCR支持图片和pdf的ocr，本地和url都可以。

Paddle OCR-VL支持图片和pdf的ocr，只支持本地。

MinerU支持图片和pdf的ocr，只支持url。

更多支持的格式，以各个ocr服务商官网为准。

url建议带jpg或pdf的长链。

致敬

感谢下面两个项目提供的灵感来源：

https://github.com/jritzi/ocr-extractor

https://github.com/rootiest/obsidian-ai-image-ocr

没有这两个项目就没有这个项目。
