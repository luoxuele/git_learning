# 1. help
    man gittutorial
    man git-log
    git hlep log

# 1. 初始化 
    git init [-q | --quiet] [directory]
    git config [<file-option>] name [value [value_regex]]
        --system
        --global    ~/.gitconfig
        --local     .git/config
        --worktree
        --file <filename>

    git config --global -l
    git config --system -l  //fatal: 无法读取配置文件 '/etc/gitconfig': 没有那个文件或目录

        配置文件位置
            --global              使用全局配置文件
            --system              使用系统级配置文件
            --local               使用仓库级配置文件
            --worktree            使用工作区级别的配置文件
            -f, --file <文件>     使用指定的配置文件
            --blob <数据对象 ID>  从给定的数据对象读取配置

        操作
            --get                 获取值：name [value-regex]
            --get-all             获得所有的值：key [value-regex]
            --get-regexp          根据正则表达式获得值：name-regex [value-regex]
            --get-urlmatch        获得 URL 取值：section[.var] URL
            --replace-all         替换所有匹配的变量：name value [value_regex]
            --add                 添加一个新的变量：name value
            --unset               删除一个变量：name [value-regex]
            --unset-all           删除所有匹配项：name [value-regex]
            --rename-section      重命名小节：old-name new-name
            --remove-section      删除一个小节：name
            -l, --list            列出所有

        git config --global user.name "luoxuele"
        git config --global user.email tianchang1994@gmail.com  

# 2. 本地操作
    add commit  status log reset diff

    git add - Add file contents to the index(暂存区，索引库)


# 3. 分支操作

# 4. 远程操作
