# 【原创项目】
基于基于Springboot+Vue+协同过滤算法的【电商系统】，系统代码全部原创，并提供带敲视频和笔记  
大家好，我是武哥，最近给大家手撸了一个基于Springboot+Vue+协同过滤算法的电商系统，网上商城，二手交易商城，可用于毕业设计，系统全部原创，如有遇到网上抄袭站长的，欢迎联系博主~  

#### 项目在线体验地址  
体验地址：**（请电脑端浏览器访问）**：[http://106.54.221.16:85/](http://106.54.221.16:85/)  
管理员账号：**admin 123456**    
用户账号：**zhangsan 123456**    
可自行注册用户账号体验  
#### 项目技术栈  
> 前后端分离  
> 后端：Springboot2 + Mybatis  
> 前端：Vue2 + ElementUI + Axios  
> 数据库： MySQL  

#### 项目功能描述  

>**管理员**  
>登录、个人信息、修改密码、管理后台管理系统所有数据  
>1、**商品分类管理**：管理系统的商品分类信息  
>2、**商品信息管理**：管理所有店铺的商品信息、商品详情  
>3、**评论管理**：管理所有店铺商品的评论信息  
>4、**订单管理**：管理所有店铺的订单信息  
>5、**公告管理**：管理系统公告信息  
>6、**管理员信息**：管理系统管理员的相关信息  
>7、**商家信息**：管理系统商家的信息，审核商家  
>8、**用户信息**：管理系统用户的信息  
>####   
>**商家**  
>登录、注册、个人信息、修改密码、管理后台管理自己店铺相关数据  
>1、**商品信息管理**：管理自己店铺的商品信息、商品详情  
>2、**评论管理**：管理自己店铺商品的评论信息  
>3、**订单管理**：管理自己店铺的订单信息，包括发货  
>####   
>**用户**  
>注册、登录、个人信息、修改密码  
>系统前台首页浏览商品分类、商品信息、系统推荐商品（协同过滤推荐算法）、个人信息入口  
>1、**收藏的宝贝**：浏览自己收藏的商品信息  
>2、**我的地址**：管理自己的收货地址  
>3、**我的购物车**：浏览自己购物车里的商品，支持多选，支持下单  
>4、**我的订单**：查看自己的订单信息，包括确认收货、评价  


#### 创新点  
> 1、基于多商户，不同的商户管理自己的数据  
> 2、仿天猫商城，基本上与其一模一样，亮点十足，不担心重复  
> 3、加入协同过滤推荐算法，个性化推荐  
> 4、推荐算法内部，多线程异步处理不同用户的数据  
#### 部分关键页面截图  
登陆页面:![请添加图片描述](https://img-blog.csdnimg.cn/direct/68adca8a095f4d04b8b831739a87edba.png)  
#### 系统前台  
前台首页![请添加图片描述](https://img-blog.csdnimg.cn/direct/350052cb3dd74d24a907ab93d477bcd0.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/a8d076aecde9470f98033fb42b403f8a.png)按分类查看：![请添加图片描述](https://img-blog.csdnimg.cn/direct/2add36f748f348bf9d9ff19d3578905d.png)搜索商品：![请添加图片描述](https://img-blog.csdnimg.cn/direct/f623b1ca54df47369126ebbe94dfea92.png)商品详情和评价：![请添加图片描述](https://img-blog.csdnimg.cn/direct/cdd161759ae647ec8158848297ac70e7.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/1d17df62e67447ba9e95eb2c3456cec6.png)查看店铺：![请添加图片描述](https://img-blog.csdnimg.cn/direct/5a7088af6b704f5b9412788de2e68625.png)我的收藏：![请添加图片描述](https://img-blog.csdnimg.cn/direct/842c83b975e4497eb4b8bbcc9c3f5641.png)我的购物车：![请添加图片描述](https://img-blog.csdnimg.cn/direct/94014a046cd74abeacd5ee06108ecebe.png)我的地址：![请添加图片描述](https://img-blog.csdnimg.cn/direct/69c2b760c29b4e02a0b3005c6cf72ee5.png)我的订单：![请添加图片描述](https://img-blog.csdnimg.cn/direct/1cba089c1ed04a03a34f5383424f78ec.png)
#### 管理后台  
商品分类：![请添加图片描述](https://img-blog.csdnimg.cn/direct/eaf4572e1e654edc84cbdb1ff5c5438f.png)商品详情：![请添加图片描述](https://img-blog.csdnimg.cn/direct/e5e369e7ca2e4b0594051f334d0dd850.png)
评论管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/a6e4a2c6d46b4b00aeecf00f6a339dab.png)
订单管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/a554d3e574a346c6a39870342e984e77.png)
系统公告：![请添加图片描述](https://img-blog.csdnimg.cn/direct/ca2fcc1903f54f4289418ffcd73f9328.png)

资料获取方式：加入知识星球：【项目训练营】即可  
<img src="https://img-blog.csdnimg.cn/direct/44f688415c0c47cc81ad08a1f275e6a4.png" width="300px" />

**星球提供**：  

1. （**价值**）星球内部的所有实战项目均提供脚手架、详细的笔记和完整的带敲视频，可以跟着完整学习视频敲出来，学习过程中提供一对一答疑。  
2. 星球内部的实战项目会一直更新，星球成员可以学习所有项目，具体项目列表如下（长期更新）：[https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf](https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf)  
3. 星球内部会提供不同的专栏，其中除了上述实战项目外，还有学习资料，比如经典学习笔记、超全面试题等  
4. 星球内部会不定期分享学习经验，开发经验，工作经验，如果你有需要，也可以提供相应文档    
