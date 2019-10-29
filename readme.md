在我们的QQ个人信息中，正常情况下无论是手机还是电脑，只能修改性别为 男or女，但是我们经常会看到性别为空的人，这篇文章就讲一下如何过审查元素修改自己的性别为“未填写”状态。


**直接步入正题**

首先进入QQ个人中心https://id.qq.com/index.html#info

然后我们在资料页-基本资料，点击编辑设置

然后就可以修改性别了，但是性别只有两个选项，这个时候我们将鼠标移到选项栏上，右键，点击*检查*

被打开的审查界面会自动定位在
`<select id="sex" name="sex" class="w_65">`

点击左边的*三角形标识*，展开后会变成下面这样

    <select id="sex" name="sex" class="w_65">
    
                                    	<option value="1">男</option>                                   	
                                        <option value="2">女</option>
                                        
                                    </select>

选择`<option value="1">男</option>`与`<option value="2">女</option>`

按下删除键将其*删除*。

此时在选择栏里已经没有任何性别选项了，然后我们只需要点击下方的*确认*

刷新页面，这时性别栏已经为空，设置结束。

感谢您看了这篇文章,如果在执行上述步骤时遇到问题，请通过[邮箱联系][1]或[B站联系][2]
  [1]: mailto:i@awsl.tv
  [2]: https://space.bilibili.com/64719640
