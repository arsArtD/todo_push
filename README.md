# todo_push
个人待办事项推送服务

暂时有如下目标：
 
    1. 提供一个简单登录注册系统
    2. 用户登录系统后可以添加任务
    3. 后台管理系统也可以添加任务
    4. 用户可以在前台接收到后台发来的任务（使用websocket）
    
# Usage

初始化composer
```
composer install
```
创建配置文件.env
```
cp .env.example .env
```
构建环境
```
docker-compose up -d 
```
访问
>localhost:8099