# quakeF
quakeF是以终端命令行来执行查询的工具



<img width="952" alt="image" src="https://user-images.githubusercontent.com/53268974/179147334-5a2c455f-21a8-4416-9584-99befedd9f52.png">

在conf.ini中配置你的key，可以配置多个

默认会选择编号为1的key，通过：-k 2 这种方式来切换key

<img width="679" alt="image" src="https://user-images.githubusercontent.com/53268974/179149610-a6ec6f27-6d4d-49a6-8221-14395ad08bb0.png">


-d 是子域名收集 例子： -d  默认查询10条数据：

<img width="774" alt="image" src="https://user-images.githubusercontent.com/53268974/179147698-f8d9f6d5-fd16-4583-adca-3dbb1d67db32.png">

使用 -e 来增加查询数量（*注意由于360quake对网页数量的限制，最多只能获取500条数据）例子：./quakeF -d google.com -e 20 ： 

<img width="766" alt="image" src="https://user-images.githubusercontent.com/53268974/179147817-8bf96bd4-5565-4b72-b8c9-8e875992ab9d.png">


-hy 是搜索蜜罐：

<img width="745" alt="image" src="https://user-images.githubusercontent.com/53268974/179148023-33cee3b0-3d31-417a-b52e-f4f15bbff9e8.png">

-q 会遵循quake搜索语法

<img width="742" alt="image" src="https://user-images.githubusercontent.com/53268974/179148183-acf71899-197e-4a35-8395-6d9227a82ec2.png">

有任何的建议欢迎提issue。

