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
* 不要在以前的tag上直接修改，而需要根据当前的数据，切换并创建分支来提交新的tag

#### 自定义过滤器
* 功能：筛选数据
* 过滤器可以多个连续使用，前一个过滤器最终return的数据不仅仅是显示的数据，还是下一个过滤器collection接受的参数,如果多个过滤器，那最终的return值才是显示的数据
* `app.filter('名称',function(){   return function(arr,...argv){   return 最终数组 }  });`
* `{ 数组 | 过滤器名称:参数1:参数2}`

#### 自定义指令
* scope属性

#### transclude属性应用场景

#### 总结link属性和controller的区别


