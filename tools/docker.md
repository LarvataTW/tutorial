{{toc}}

h1. Docker Doc

# http://campus.codeschool.com/courses/try-docker
# https://scotch.io/tutorials/getting-started-with-docker
# https://prakhar.me/docker-curriculum/
# https://yq.aliyun.com/articles/65145

* Docker for PHP http://open.daocloud.io/tag/php-kai-fa-zhe-de-docker-zhi-lv/
* Docker for Python http://open.daocloud.io/tag/python-kai-fa-zhe-de-docker-zhi-lv/

* Larvata 教學文件 https://drive.google.com/drive/folders/0B-Xz59zuRovPM2pVa2IxZUN3dEU
* Docker 運維經驗 https://thehftguy.com/2016/11/01/docker-in-production-an-history-of-failure/
* Docker 網路架構 http://blog.daocloud.io/docker-bridge/
* Docker 進階應用 http://open.daocloud.io/tag/allen-tan-docker/
* Docker 源碼分析 http://open.daocloud.io/tag/yuan-ma-fen-xi/
* K8S 介紹 http://www.bilibili.com/video/av10087636/

h2. Dockerfile

https://docs.docker.com/engine/reference/builder/

h2. docker-compose.yml

h1. docker 常用情境

* 情境：列出主機上的 Docker Images。
<pre>docker images</pre>


* 情境：取得 Ubuntu 的 Docker Image。
<pre>docker pull ubuntu</pre>


* 情境：啟動一個 Ubuntu Image 的 Container 並進入它的 bash 環境。
<pre>docker run -it ubuntu bash</pre>


* 情境：離開上一步驟進入的 Container 但是不讓它 (docker process) 結束。
<pre>先按 Ctrl + p，再按 Ctrl + q</pre>


* 情境：查詢目前 Docker Server 中運行的「所有」Container 以及它們的 Name。
<pre>docker ps -a</pre>


* 情境：進入一個正在「運行中」的 Container 的 bash 環境。
<pre>docker exec -it your_running_container_name bash</pre>


* 情境：離開 Container 的 bash 環境。
<pre>exit</pre>


* 情境：停止「運行中」的 Container。
<pre>docker stop your_running_container_name</pre>


* 情境：重啟「停止中」的 Container。
<pre>docker restart your_stopped_container_name</pre>


* 情境：移除「停止中」的 Container。
<pre>docker rm your_stopped_container_name</pre>


* 情境：啟動一個 Nginx Image 的 Container，並讓它在背景執行。
<pre>docker run -d nginx</pre>


* 情境：啟動一個 Nginx Image 的 Container，並將主機的 8080 port 對應到 Container 的 80 port。
<pre>docker run -p 8080:80 nginx</pre>


* 情境：啟動一個 Nginx Image 的 Container，並將主機的 /tmp 目錄掛載到 Container 的 /usr/share/nginx/html 目錄。
<pre>docker run -v /tmp:/usr/share/nginx/html nginx</pre>

h1. docker-compose 常用指令

*docker-compose 預設會讀取當前目錄下的 docker-compose.yml 作為設定檔。*

* 情境：啟動所有的 Containers
<pre>docker-compose up</pre>

* 情境：啟動所有的 Containers 在背景執行
<pre>docker-compose up -d</pre>

* 情境：顯示當前的運作情況
<pre>docker-compose ps</pre>

* 情境：查看所有 Containers 的 logs
<pre>docker-compose logs</pre>

* 情境：停止所有的 Containers
<pre>docker-compose stop</pre>

* 情境：移除所有停止中的 Containers
<pre>docker-compose rm</pre>
