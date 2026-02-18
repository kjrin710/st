# st - 简单终端

## 关于 st

st 是一款适用于 X 系统的简单终端模拟器，相比其他同类产品，它的表现要好得多。  
这是对 [st](https://st.suckless.org/) 项目的个人分支，该项目源自 [suckless.org](https://suckless.org/) 。  

### 要求
要构建该项目，您需要 Xlib 头文件。  

### 安装
请编辑 config.mk 文件以适应您的本地设置（默认情况下，st 会被安装到 /usr/local 命名空间中）。  
之后，请输入以下命令来构建并安装 st（如果需要的话，请以 root 身份运行）：  

`make clean install`  

### 运行 st
如果您未通过“make clean install”命令来安装 st，那么您必须使用以下命令来编译 st 的 terminfo 项：  

`tic -sx st.info`  

请查看手册页以获取更多详细信息。  

## 自定义配置

在原版 st 基础上进行了以下个性化调整：  

### 补丁
- alpha
- anysize
- scrollback-reflow-standalone-extended

### 外观
- **字体**：使用“hack”字体，字号 24
- **主题**：深蓝色配色
