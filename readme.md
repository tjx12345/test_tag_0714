### 准备开始
---

#### git补充
* tag 标签，打标签
    - 开发新的项目还未上线的时候，使用分支，最终项目稳定以后合并分支
    - 项目稳定以后的升级，就需要打标签，tag
* 1:提交后添加tag标签 
    - 1：提交
        - git commit -m "提交信息" 
     2:打标签
        - git tag -a v1.1.1 -m "标签的信息"
* 将tag推送到服务器
    - git push  origin master --tags
* 查看tag
    - git tag 
* 删除tag
    - 删除tag需要是在当前本地的时候，比如有tag1、tag2，如果觉得当前的tag1是无用的，可以进行删除，然后就将剩余的tag2进行推送
* 根据tag下载指定的项目版本代码
* 克隆指定版本的项目代码
    - `clone origin -b v3.3.3`

#### 自定义过滤器
* 功能：筛选数据


#### 自定义指令
* scope属性

#### transclude属性应用场景


#### 总结link属性和controller的区别


#### 全局共享数据方式
