运行以下代码执行添加ipv4和ipv6脚本。脚本为网络上大佬编写，我把它打包成了一键脚本。目前亲测在甲骨文服务器有效。
ipv4
~~~shell
wget -O manage_nginx.sh "https://raw.githubusercontent.com//IArvinServer/nginx-IPv6/main/manage_nginx.sh" && chmod +x manage_nginx.sh && ./manage_nginx.sh
~~~
ipv6
~~~shell
wget -O ipv6_manager.sh "https://raw.githubusercontent.com/IArvinServer/nginx-IPv6/refs/heads/main/ipv6_manager.sh" && chmod +x ipv6_manager.sh && ./ipv6_manager.sh

测速脚本

~~~shell
wget -O speedtest_manager.sh "https://raw.githubusercontent.com/IArvinServer/nginx-IPv6/main/speedtest_manager.sh" && chmod +x speedtest_manager.sh && ./speedtest_manager.sh
~~~
