## Gztc

本项目使用 PHP 框架 Laravel 5.5.28 进行开发 

![macbook](https://raw.githubusercontent.com/cong5/myPersimmon/master/screen.jpg)


本项目使用 PHP 框架 [Laravel 5.5](https://doc.laravel-china.org/docs/5.5/) 进行开发。 
系统后台使用 AdminLTE-2.3.0 框架

[参考Demo](https://github.com/Cong5/myPersimmon) 基于Laravel 5.4 版本开发。

### 博客功能具有以下功能

- 分类管理
- 文章管理
- 标签管理
- 评论管理
- 导航管理


更多功能欢迎大家自己挖掘，或者有好的意见和建议欢迎拍砖。


## 项目概述

* 项目名称：Gztc
* 项目运行地址：http://example.com/

[Gztc](https://github.com/Ryan-Gong/gztc) 基于Laravel 5.5 版本开发。

## 目前运行环境

- Apache 2.0+
- PHP 7.0+
- MySQL 5.5+

## 部署/安装

需要在系统上安装了基本的PHP运行环境、PHP包管理工具composer进行前端资源打包

### 基础安装

#### 1. 克隆源代码

克隆源代码到本地：

    > git clone https://github.com/Ryan-Gong/gztc.git

#### 2. 安装扩展包依赖

    > composer install

#### 4. 生成配置文件

    > cp .env.example .env

    
#### 5. 执行数据库迁移

```shell
php artisan migrate
```

#### 6. 填充初始数据

```shell
php artisan db:seed
```

### 前后台入口

> 如果要开启调试模式，请修改 `.env` 文件， `APP_ENV=local` 和 `APP_DEBUG=true` 。

* 首页地址：http://example.com/
* 管理后台：http://example.com/wms

默认用户名：admin
密码：admin

至此, 安装完成。


## License

> 使用 Gztc 构建，或者基于 Gztc 源代码修改的站点 **必须** 在页脚加上 `Powered by ryan-gong` 字样，并且必须链接到 `http://example.com/` 上。

在遵守以上规则的情况下，你可以享受等同于 MIT 协议的授权。

