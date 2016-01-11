## 目录
[toc]

## 脚注
先定义在使用
[^name]: 本文作者

我[^name]是一个成长中的菜鸟。

## 表格
|姓名|性别|年龄|学历|
|:--|:--|:--|:--|
|Quex|男 |21	 |本科|
|QueJay|男|21 |硕士|

## 公式 基于MathJax语法
行内公式
圆面积公式：$ S=\pi r^2 $
陈列公式
$$
\Gamma=\int_0^\infty t^{z-1} e^{-t} dt
$$

## 序列图
``` sequence
Title:早上起床
小明-->小华:起床啦
note left of 小明: 闹钟响
小华-->小红: 你先起
小红->>小华:收到
note right of 小红: 起床
小红-->小华:我起来了
小华-->小明:我也起来了
小明->>小明:看来我也该起了
```
## 流程图
``` flow
start=>start: 开始
login=>operation: 用户登录
check=>condition: 账号密码正确？
success=>operation: 登录成功
error=>operation: 重新登录
load=>operation: 加载信息
show=>operation: 显示信息
end=>end: 结束

start->login->check
check(yes)->success->load->show
check(no)->error->check
show->end
```
