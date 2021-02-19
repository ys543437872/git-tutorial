# Git 安装
- 在Ubuntu上安装
```
sudo add-apt-repository ppa:git-core/ppa
sudo apt update
sudo apt install git
```

- [Git官网](https://git-scm.com)

# Git 初始化
- 初始化用户信息
    ```
    # 初始化用户名与用户邮箱
    git config --global user.name "Your Name"
    git config --global user.email Your@email.com
    ```

- 初始化文本编辑器
    ```
    # 使用VIM
    git config --global core.editor "vim"
    ```

# 获得 Git 仓库
- 初始化仓库
    ```
    git init
    ```

- 克隆仓库
    ```
    git clone <url> 
    ```

# 跟踪新文件
```
git add <files>

# 添加所有未忽略文件
git add .
```

# 检查当前文件状态
```
git status
```

# 