clockSubmitV2.0
=======================
这是一个防止重复提交Form表单的小插件;

```
<script src="clockSubmit.js"></script>
```
调用方式：
```
//多次点击添加按钮
$("add").click(function(){
  if ( clockSubmit() ) {
    return false;
  };
  // 在这里写提交的Ajax数据...
  console.log("解锁");
});
