简介
此脚本用于生成SEO服务，服务的功能是将含有Ajax请求的动态页面转化成静态页面，满足爬虫工具（如百度 搜狗）爬取静态页面的需求。
使用
1. 运行以下命令生成docker镜像
    docker build -t seo:0.1 .
2. 运行以下命令启动服务
    docker run -d -i -p 3000:8888 -name seo-0.1-3000 seo:0.1