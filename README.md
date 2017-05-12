# [Mr.Liang's blog](https://liangrengongzuoshi.github.io/liangren.com/ "良先生的博客")

https://liangrengongzuoshi.github.io/liangren.com/

---
# markdown test
---

# 标题：这是H1：#x1
## 这是H2：#x2
### 这是H3：#x3
#### 这是H4：#x4
##### 这是H5：#x5
###### 这是H6：#x6


## 无序列表：*、+、-

* 无序号一
* 无序号二
* 无序号三

+ 一
+ 二
+ 三

- 一
- 二
- 三

1. 这是1.
2. 这是2.
3. 这是3.

* 阅读开始
  > 第一章
  >> 第二章

## 区块引用

> 这是一个块>,
> 还是一个块>
>> 这是两个块>>
>>> 这是三个块>>>
>> #### 这是两个块>>，并加了####

## 强调，一个星号包括是斜体，两个星号包括是加粗

这里有*强调词用星号包括*，

这里有**强调词用两个星号包括**；

## 超链接

This is an [baidu.com](http://baidu.com/ "这是title").

> 格式：\[baidu.com\]\(http://www.baidu.com “这是title”\)

#### 图像格式 ！\[图像\](http://....jpg "图像")
![这是图像](https://avatars1.githubusercontent.com/u/19851699?v=3&s=460 "这是title")



## 代码块```或一个tab键缩进
```java
/*
 *这是注释
 */
public static void main(String[] args){
    System.out.println("Hello world.");
}
```
    // 这是注释
    public static void main(String[] args){
        System.out.println("Hello world.");
    }
    

### 分割线使用三个-或三个*
---
***


## 表格

 姓名 | 性别 | 年龄
-----|-----|------
 张三 | 男  | 11 
 王五 | 男  | 22 


```
格式：
 姓名 | 性别 | 年龄
-----|-----|------
 张三 | 男  | 11 
 王五 | 男  | 22 
```



## 流程图
#### 这个是有道笔记的markdown流程图语法,好像github不支持
```
graph XXX       指定流程图类型：TB/BT/RL/LR。
    TB - top bottom（自上而下）
    BT - bottom top（自下而上）
    RL - right left（从右到左）
    LR - left right（从左到右）
指定形状（同时，括号里内容也是流程图中显示的内容,A/B相当于别名）：
    A[这是四边形]
    A((这是圆形))
    A{这是菱形}
A-->B           指定流程
A-->|是|B       ||表示连接线上的插入内容
A---B           无方向连接
```

```
#### 示例代码
graph TB
    A[四边形]
    B{菱形}
    C((圆形))
    
    
    O[图形]
    O-->|包括|A
    O-->|包括|B
    O-->|包括|C
    
    B-->|属于|A
    C---|没啥关系|A
```

```
graph TB
    A[四边形]
    B{菱形}
    C((圆形))
    
    
    O[图形]
    O-->|包括|A
    O-->|包括|B
    O-->|包括|C
    
    B-->|属于|A
    C---|没啥关系|A
```


