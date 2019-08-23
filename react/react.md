## 杂项
1. 在React里怎么打印[object object]里的属性
```
  Object.keys(e).map(key => {
    console.log(`key = ${key}, value = `);
    console.log(e[key]);
    return null;
  });
```
方法就是Object.keys()获取对象的所有key，然后再用map方法遍历。  
这里要注意console.log(e[key]) 可以打印数据详情， console.log(`e[key]`)，这种只能打印[object object]这样的。 不过也从侧面说明[object object] 是一个json类型的对象
