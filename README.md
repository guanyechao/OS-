# OS-
os --- 操作系统接口模块
### 使用列表推导式可以将所需要翻译的文字全部打印出来
**列表推导式：各语句之间是嵌套关系。左边第二个语句是最外层，依次往右进一层。左边第一条语句是最后一层**
<br>如：<br>
`[x*y for x in range(1,5) if x > 2 for y in range(1,4) if y < 3]`
<br>执行顺序：<br>
```
for x in range(1,5)
    if x > 2
        for y in range(1,4)
            if y < 3
                x*y
                
```
