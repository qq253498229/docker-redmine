# note

#### 修改docker-compose.yml中的第7行

> 其中"8080:3000"，8080是对外开放的端口，可以修改。3000是容器内端口是默认的，如无必要最好别修改

#### 修改docker-compose.yml中的第19行

> "./mysql/data:/var/lib/mysql" 其中./mysql/data是数据库的数据文件在本地的存放位置，可以修改成自己的位置

#### 运行docker-compose up -d

#### 访问http://localhost:8080