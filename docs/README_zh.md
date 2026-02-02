# st - 简单终端

## 关于这个分支
这是对 [st（简易终端）](https://st.suckless.org/) 项目的一个个人分支，该分支源自 [suckless.org](https://suckless.org/) 。
**原文链接：** https://git.suckless.org/st/
**原始项目地址：** https://st.suckless.org/

### 应用补丁与修改内容
- 添加一些补丁
- 自定义配色方案

## 关于 st
st 是一款适用于 X 系统的简单终端模拟器，相比其他同类产品，它的表现要好得多。

### 要求
要构建该项目，您需要 Xlib 头文件。

### 安装
请编辑 config.mk 文件以适应您的本地设置（默认情况下，st 会被安装到 /usr/local 命名空间中）。
之后，请输入以下命令来构建并安装 st（如果需要的话，请以 root 身份运行）：
执行“清理安装”操作

### 运行 st
如果您未通过“make clean install”命令来安装 st，那么您必须使用以下命令来编译 st 的 terminfo 项：
tic -sx st.info
请查看手册页以获取更多详细信息。

## 资料来源/致谢

### 原项目
该项目由“无赖”社区开发。有关所有贡献者的完整名单，请参阅 LICENSE 文件。
