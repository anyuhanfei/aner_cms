### aner_cms
aner后台管理模板--内置通用模块并可快速搭建数据

#### 使用框架
使用thinkphp5框架,框架版本为5.0.24;

#### 省略文件说明
runtime目录省略
thinkphp目录省略
vendor目录中省略三个目录（composer, topthink, workerman）

注：runtime目录为缓存目录，thinkphp目录为框架核心代码（可自行下载），vendor目录下省略的三个目录为thinkphp完整版安装时自动安装的库（也可自行下载）

#### 后台模块
- 管理员管理 -- 列表，添加，修改，删除，更改角色；
- 角色管理 -- 列表，添加，修改，修改可访问模块，删除；
- 后台目录管理 -- 最高二级目录，可添加修改图标，地址，排序，备注；
- 前台目录管理 -- 最高二级目录，与后台目录基本相同；
- 模块管理 -- 模块的名称，方法表的上级；
- 方法模块 -- 方法名和方法路径，角色权限控制和后台目录管理使用；
- 自定义设置 -- 可添加修改中文解释，代码标识和值；
- 网址基本设置 -- 标题，关键字，描述，版权，备案号；
- 广告管理 -- 代码标签，标题，内容，图片，排序；
- 文章分类管理 -- 一级分类，可添加修改删除
- 文章标签管理 -- 可添加修改删除；
- 文章管理 -- 一个文章分类，可多个标签，可添加修改标题，作者，关键字，图片,内容，简介，状态，文章点击率和点击量统计；可设置置顶(一个)和推荐(多个)；文章内容可选择富文本编辑或markdown编辑；
- 管理员日志 -- 记录管理员操作日志，记录管理员id，ip，操作内容，操作时间；


#### v1.0.1
1. 文章内容修改为富文本编辑器和markdown编辑器两种；
2. 文章点击量，点赞量等；
3. 文章添加一个推荐和置顶功能；


