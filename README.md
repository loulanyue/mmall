

| &nbsp;&nbsp;&nbsp;环境搭建&nbsp;&nbsp;&nbsp; | 数据表结构 | &nbsp;&nbsp;&nbsp;网络&nbsp;&nbsp;&nbsp; | 面向对象 | &nbsp;&nbsp;数据库&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;Java&nbsp;&nbsp;&nbsp; | 系统设计 | &nbsp;&nbsp;&nbsp;工具&nbsp;&nbsp;&nbsp; | 编码实践 |&nbsp;&nbsp;&nbsp;后记&nbsp;&nbsp;&nbsp; |  
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: | :-------:| :------:|
| [:pencil2:](#pencil2-环境搭建) | [:computer:](#computer-数据表结构)|[:cloud:](#cloud-网络) | [:art:](#art-面向对象) |[:floppy_disk:](#floppy_disk-数据库)|  [:coffee:](#coffee-java)| [:bulb:](#bulb-系统设计)| [:wrench:](#wrench-工具)| [:watermelon:](#watermelon-编码实践)| 


>##大型分布式架构
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: | :-------:| :------:|
## :pencil2: 一、环境搭建
> linux软件源配置</br>
> JDK</br>
> Tomcat</br>
> Maven</br>
> Vsftpd</br>
> Nginx</br>
> Mysql</br>
> Git</br>
> 文件服务器</br>
> 环境变量</br>
> 防火墙</br>

## :computer: 二、数据表结构
> 数据表结构设计</br>
> 数据表关系设计</br>
> 索引</br>
> 时间戳</br>

## :cloud: 三、项目初始化

> 数据库初始化</br>
> IDEA安装</br>
> IDE配置JDK、Maven、Tomcat、快捷键等</br>
> maven创建web项目并验证</br>
> Git创建仓库及初始化</br>
> Maven的POM文件讲解</br>
> 项目包结构</br>

> Mybatis三剑客</br>
>>Mybatis-generator</br>
>>Mybatis-plugin</br>
>>Mybatis-pagehelper</br>

> web.xml</br>
> Spring容器配置文件applicationContext.xml</br>
> SpringMVC配置文件dispatcher-servlet.xml</br>
> FTP服务器的配置</br>
> IDEA注入和实时编译的配置</br>
> 工具</br>

>>Restlet client</br>
>>FE助手</br>


## :art: 四、功能模块

> 接口设计详解</br>

> coding</br>

> 自测验证</br>


# :wrench: 4.1 用户模块
> 登录</br>
> 用户名验证</br>
> 注册</br>
> 忘记密码</br>
> 提交问题答案</br>
> 重置密码</br>
> 获取用户信息</br>
> 更新用户信息</br>
> 退出登录</br>					
			
>> 横向越权、纵向越权安全漏洞</br>
>> MD5明文加密及增加salt值</br>
>> Guava缓存的使用</br>
>> 高复用服务响应对象的设计思想及抽象封装</br>
>> Mybatis-plugin使用技巧</br>				


# :wrench: 4.2 分类管理模块
> 获取节点</br>
> 增加节点</br>
> 修改名字</br>
> 获取分类ID</br>
> 递归子节点ID</br>
				
>> 如何设计及封装无限层级的树状数据结构</br>
>> 递归的设计思想</br>
>> 如何处理复杂对象排重</br>
>> 重写hashcode和equals的注意事项</br>
		
		 
# :coffee: 4.3 商品模块
> </br>
> 前台功能</br>
>> 产品搜索</br>
>> 动态排序列表</br>
>> 商品详情</br>

> 后台功能</br>
>> 商品列表</br>
>> 商品搜索</br>
>> 图片上传</br>	
>> 富文本上传</br>
>> 商品详情</br>
>> 商品上下架</br>
>> 增加商品</br>	
>> 更新商品</br>

>> FTP服务的对接</br>	
>> SpringMVC文件上传</br>
>> 流读取Properties配置文件</br>
>> 抽象POJO、BO、VO对象之间的转换关系及解决思路</br>
>> 静态快</br>
>> Mybatis-pageHelper高效准确地分页及动态排序</br>
>> Mybatis对List遍历的实现方法</br>
>> Mybatis对where语句动态拼装的几个版本演变</br>

# :watermelon: 4.4 购物车模块
> 加入商品</br>
> 更新商品数</br>
> 查询商品数</br>
> 移除商品</br>
> 单选/取消</br>
> 全选/取消</br>
> 购物车列表</br>
				
>> 购物车模块的设计思想</br>
>> 如何封装一个高复用购物车核心方法</br>
>> 解决浮点型商业运算中丢失精度的问题</br>

# :cloud: 4.5 收货地址模块
> 添加地址</br>
> 删除地址</br>
> 更新地址</br>
> 地址列表</br>
> 地址分页</br>
> 地址详情</br>
				
>> SpringMVC数据绑定中对象绑定</br>
>> mybatis自动生成主键、配置和使用</br>
>> 如何避免横向越权漏洞的巩固</br>
floppy_disk

# :bulb: 4.6 支付模块
> 支付宝沙箱</br>
> 支付宝集成</br>
> 支付回调</br>
> 查询支付状态</br>
				
>> 沙箱调试环境（买家账号测试、商家账号测试）</br>
>> 支付宝扫码支付主业务流程</br>
>> 支付宝扫码支付流程</br>
>> 支付宝扫码支付重要的字段</br>
>> 支付宝扫码支付重要细节</br>
>> 支付宝扫码支付对接技巧</br>
>> 支付宝扫码支付宝官方Demo调试</br>
>> 熟悉支付宝对接核心温度，调通支付宝支付功能官方Demo</br>
>> 解析支付宝SDK对接源码</br>
>> RSA1和RSA2验证签名及加解密</br>
>> 避免支付宝重复通知和数据校验</br>
>> natapp外网穿透和tomcat remote debug</br>
>> 生成二维码，并持久化到图片服务器</br>

# :coffee: 4.7 订单模块
>> 前台功能</br>
> 创建订单</br>
> 商品信息</br>
> 订单列表</br>
> 订单详情</br>
> 取消订单</br>

>> 后台功能</br>
> 订单列表</br>
> 订单搜索</br>
> 订单详情</br>
> 订单发货</br>
			
>> 避免业务逻辑中横向越权和纵向越权等安全漏洞</br>
>> 设计实用、安全、扩展性强大的常量、枚举类</br>
>> 订单号生成规则、订单严谨性判断</br>
>> POJO和VO之间的实际操练</br>
>> mybatis批量插入</br>


## :coffee: 五、云服务器部署
> 云服务器（申请、配置）</br>
> 域名（申请、备案、配置）</br>
> 源配置</br>
> 线上环境</br>
> 自动化发布脚本</br>
> 线上验证</br>

## :watermelon: 六、展望
> Tomcat集群</br>
> Redis分布式缓存</br>
> Spring、SpringMVC进阶</br>

