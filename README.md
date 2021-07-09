# download-git-repo-for-vite

从node下载并提取一个git库(GitHub, GitLab, Bitbucket)。

移植自[download-git-repo](https://gitlab.com/flippidippi/download-git-repo#readme) 因为在vite环境下download-git-repo依赖的download依赖不能正常工作而导致download-git-repo引入时报错,而download-git-repo已经两年没更新了,所以创建了这个库,仅修改了导出方式和依赖版本,全部用法同download-git-repo.

## 安装

    $ npm install git-repo-down-for-vite



## 引入
``import {download} from "git-repo-down-for-vite";``

### 使用

同[download-git-repo](https://gitlab.com/flippidippi/download-git-repo#readme) 的使用方法

## 协议

MIT

