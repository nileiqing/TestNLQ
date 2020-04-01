# 测试

## 测试

### 测试

#### 测试

```	java
sudo apt install

git
```

` sudo apt install git` 

```java
void test 
  sudo apt install 
```

```shell
sudo apt install git
sudo apt 
class 
```

***

---

[帮助文档](http://www.baidu.com)

[我想跳转](#测试)

<http://www.baidu.com>

![sdf](https://dss0.baidu.com/6ONWsjip0QIZ8tyhnq/it/u=2246271396,3843662332&fm=85&app=79&f=JPG?w=121&h=75&s=39C718720E8EBE011B398BAC0300F024)

graph LR; 

​	 A-->B  

​	B-->C  

​	C-->A

Graph LR;

```mermaid
graph LR;
  A-->B
  B-->C
  C-->A
```

```mermaid
graph LR;
	A-->
	B(圆角矩形)-->
	C[矩形]-->
  D((圆形))-->
  E>sd]-->
  F{菱形}
```

```mermaid
graph TB
    begin(出门)--> buy[买炸鸡]
    buy --> IsRemaining{"还有没有炸鸡？"}
    IsRemaining -->|有|happy[买完炸鸡开心]--> goBack(回家)
    IsRemaining --没有--> sad["伤心"]--> goBack
    

```





```mermaid
graph TB
  A1-->B1
  A2---B2
  A3--text---B3
  A4--text-->B4
  A5-.-B5
  A6-.->B6
  A7-.text.-B7
  A8-.text.->B8
  A9===B9
  A10==>B10
  A11==text===B11
  A12==text==>B12

```

```mermaid
graph TB
	subgraph 买炸鸡前
   			 begin(出门)--> buy[出门买炸鸡]
    end
    buy --> IsRemaining{"还有没有炸鸡？"}
    IsRemaining --没有--> sad["伤心"]--> goBack(回家)
    IsRemaining -->|有|happy[买完炸鸡开心]--> goBack
```

```mermaid
sequenceDiagram
    participant 99 as 救救
    participant seller as 炸鸡店小哥
   
    99 ->> seller: 还有炸鸡吗？
    seller -->> 99: 没有，要现炸。
    99 ->> +seller:给我炸！
    loop 三分钟一次
        99 ->> seller : 我的炸鸡好了吗？
        seller -->> 99 : 正在炸
    end
    seller -->> -99: 您的炸鸡好了！

```



```mermaid
sequenceDiagram    
    participant 99 as 救救
    participant seller as 炸鸡店小哥
    99 ->> seller : 现在就多少只炸好的炸鸡？
    seller -->> 99 : 可卖的炸鸡数
    
    alt 可卖的炸鸡数 > 3
        99 ->> seller : 买三只！
    else 1 < 可卖的炸鸡数 < 3
        99 ->> seller : 有多少买多少
    else 可卖的炸鸡数 < 1
        99 ->> seller : 那我明天再来
    end

    seller -->> 99 : 欢迎下次光临

```







