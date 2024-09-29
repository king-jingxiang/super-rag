# README

## 项目简介

本项目是一个基于多模型的知识库问答系统，旨在从多媒体内容（如视频）中提取有用的信息，并构建一个智能的问答系统。系统不仅能够处理视频中的音频和图像，还能将这些信息转换成易于理解和检索的形式。以下是项目的详细介绍，包括最新版本的主要更新、已解决的问题、功能改进以及详细的文档。

## 项目地址

[gitee-superrag](https://gitee.com/super-rag/super-rag)  
[github-superrag](https://github.com/king-jingxiang/super-rag)

## 版本历史

### [v1.0.0] - 2024-09-20

#### 新增功能
- **视频内容提取**：自动抓取视频中的PPT图像，帮助用户快速获取视觉信息。
- **音频转字幕**：采用ASR技术将视频中的音频转换成字幕，增加内容的可访问性。
- **字幕总结**：运用大型语言模型对字幕进行摘要，生成Markdown格式的文档，方便后续的学习与整理。
- **基于知识库的问答系统**：利用从视频中提取的数据构建一个知识库问答系统。
- **提取内容导出**：提供视频帧和Markdown课件的导出功能。

#### 修复
- 解决了若干小错误，提升了系统的稳定性与可靠性。

#### 改进
- 用户界面优化，使其更加直观且易于操作。

#### 文档
- 编写了详细的安装与使用指南。
- 更新了项目描述文档，详细解释了各功能模块的实现方式。

#### 其他
- 总体性能与响应速度得到了显著提升。

## 发展路线图

为了进一步增强系统的功能，我们制定了以下的发展计划：

### 模型能力提升

1. **验证图像和音频的embedding实现**：增强对图像和音频内容的理解和检索能力。
2. **图像特征提取及向量化存储**：使图像内容更易于检索与分析。
3. **音频特征提取及向量化存储**：提高音频内容的检索效率。
4. **LVLM图像转文本并向量化存储**：使得图像内容可通过文本搜索。
5. **LALM音频转文本并向量化存储**：增强音频内容的可读性和检索能力。
6. **基于图像/音频特征的向量检索**：提供高效的内容检索功能。
7. **多模态向量存储系统**：建立统一的多模态数据存储框架。
8. **多模态数据检索**：实现跨模态的数据检索功能。
9. **多模态模型集成**：增强系统对复杂场景的理解能力。
10. **多模态问题总结**：生成综合性的内容摘要。
11. **单卡推理与模型动态管理**：优化资源利用率，减少延迟。
12. **多卡推理与模型常驻**：提高大规模数据处理的效率。

### 交互页面改进

1. **自定义配置模型API**：提供灵活的模型配置选项。
2. **浏览器插件支持**：使用户能够在浏览器中直接使用本系统功能。
3. **桌面客户端支持**：满足用户在不同环境下的使用需求。

## 安装与使用

请参阅[ChatWithVideo]([docs/installation.md](https://gitee.com/qq764073542/chat_with_video_0917))项目，了解如何设置并运行此项目。

## 贡献指南

欢迎社区成员贡献代码、报告问题或提出改进建议。请阅读[贡献指南](docs/contributing.md)以获取更多信息。

## 许可证

本项目遵循MIT许可证协议。请参见[LICENSE](LICENSE)文件了解详细信息。