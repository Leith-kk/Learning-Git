# Learning-Git
培训期间学习Git的使用方法，同时对Linux系统的vim工具进行学习训练。

## Git工具与Github
在[该文档](https://github.com/Leith-kk/Learning-Git/blob/main/Git%E5%B7%A5%E5%85%B7%E7%9A%84%E4%BD%BF%E7%94%A8.md)中对常见的git指令和Github的使用方法进行了详细的阐述。后期有开发需要可以直接在此处参考，也可将本文档作为知识库直接交给Agent学习掌握（或许LLM看不上我这小小的知识库:joy:）。

## vim工具的使用
在[该文档](https://github.com/Leith-kk/Learning-Git/blob/main/vim_edit_tool/vim_usage.md)中对vim的三种操作模式，每种操作模式下的操作指令按照使用频率进行详细说明。总得来说vim是一个很好用的编辑工具，我很喜欢在WSL2（Windows Support Linux）中使用vim作为编辑工具，既能轻量化编辑程序和文本，又能给人一种炫酷黑客感。这个工具本身不难，命令也不多，熟能生巧，多练多用一定能玩好！

## 补充一下
本地Git提交时最近会遇到输入username和password的情况。
注意此处的username是Github账户的username，登录/注册Github即可看到自己的username。
password是Github的token，令牌需要在[此处](https://github.com/settings/personal-access-tokens)获取。其中Fine-grained tokens在生成前要选择可访问的仓库（推荐all repo）、仓库权限（至少content必须是read and write）、token的过期时间（推荐never），Tokens（classic）可以直接点击勾选权限。

