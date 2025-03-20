# 国科大课程报告模版 modern-ucas-report

国科大课程报告 的 Typst 模板

## 使用


**你只需要修改 `thesis.typ` 文件即可，基本可以满足你的所有需求。**

导入即可。

### VS Code 本地编辑（推荐）

1. 在 VS Code 中安装 [Tinymist Typst](https://marketplace.visualstudio.com/items?itemName=myriad-dreamin.tinymist)。

TODO

### 特性 / 路线图

- **类型检查**
    - [ ] 应该对所有函数入参进行类型检查，及时报错
- **全局配置**
    - [x] 类似 LaTeX 中的 `documentclass` 的全局信息配置
    - [x] **盲审模式**，将个人信息替换成小黑条，并且隐藏致谢页面，论文提交阶段使用 
    - [x] **双面模式**，会加入空白页，便于打印
    - [x] **自定义字体配置**，可以配置「宋体」、「黑体」与「楷体」等字体对应的具体字体
    - [x] **数学字体配置**：模板不提供配置，用户可以自己使用 `#show math.equation: set text(font: "Fira Math")` 更改
- **模板**
  - [ ] 国科大报告模版迁移
    - [x] 字体测试页
    - [x] 封面
    - [x] 中文摘要
    - [x] 英文摘要
    - [x] 目录页
    - [x] 插图目录
    - [x] 表格目录
    - [x] 符号表
    - [x] 致谢
- **编号**
    - [x] 前言使用罗马数字编号
    - [x] 附录使用罗马数字编号
    - [x] 表格使用 `1.1` 格式进行编号
    - [x] 数学公式使用 `(1.1)` 格式进行编号
- **环境**
    - [ ] 定理环境（这个也可以自己使用第三方包配置）

## 参与贡献

- 在 Issues 中提出你的想法，如果是新特性，可以加入路线图！
- 实现路线图中仍未实现的部分，然后欢迎提出你的 PR。
- 同样欢迎 **将这个模板迁移至你的学校论文模板**，大家一起搭建更好的 Typst 社区和生态吧。


## 致谢

- 感谢 [modern-nju-thesis](https://github.com/CsomePro/modern-ucas-report)本模版是在此基础上修改的

## License

This project is licensed under the MIT License.
