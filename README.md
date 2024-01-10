# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.


## get vim from GPT
- 要使用 nvim-linux64.tar.gz 文件进行安装 Neovim，请按照以下步骤进行操作：

- 首先，从 Neovim 的官方 GitHub 页面（https://github.com/neovim/neovim/wiki/Installing-Neovim#install-from-download）下载最新的 nvim-linux64.tar.gz 压缩包。确保选择与你的操作系统架构（64位）相对应的版本。

    解压 nvim-linux64.tar.gz 文件。在终端中执行以下命令：
    ```
    shell
    tar xzf nvim-linux64.tar.gz
    ```
    
    进入解压后的 Neovim 目录：
    ```
    shell
    cd nvim-linux64
    ```
- 将 Neovim 可执行文件复制到一个你喜欢的位置。例如，将其复制到 /usr/local/bin 目录中：
    ```
    shell
    sudo cp -r * /usr/local/bin/
    ```
    这将需要管理员权限，因此可能需要输入密码。

- 添加 Neovim 到系统的环境变量。编辑你的 .bashrc、.bash_profile 或其他 shell 配置文件，并添加以下行：

    ```
    shell
    export PATH="/usr/local/bin:$PATH"
    ```
    保存文件并关闭。

- 确认安装是否成功。在终端中输入以下命令：
    ```
    shell
    nvim --version
    ```
    如果成功安装，会显示 Neovim 的版本信息。

```bash
git clone https://github.com/xxx ~/.config/nvim
```