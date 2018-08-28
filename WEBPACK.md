
##  webpack recode and study
```
  细节记录
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack"
  },
   npm run build -- --colors ==>  webpack "--colors"
   dependencies 与  devDependencies 区别
   lodash 的 _ 加载顺序
   --save 比  --save-dev 更前
   分离 
   manifest，runtime
   webpack 实现持久化缓存
   https://juejin.im/entry/588a31f98d6d81006c0a7b37
```

## lodash Thinking

```
  此处了解到chunk
  function chunk(array, size) {
    //获取数组的长度，如果你传入的不是数组，那么获取到的就是undefined
    const length = array.length
    //判断不是数组，或者size没有设置，size小于1，就返回空数组
    if (!length || !size || size < 1) {
      return []
    }

    //核心部分
    let index = 0 //用来表示切割元素的范围start
    let resIndex = 0 //用来递增表示输出数组的下标

    //根据length和size算出输出数组的长度，并且创建它。
    let result = new Array(Math.ceil(length / size))
    //进行循环
    while (index < length) {
      //循环过程中设置result[0]和result[1]的值。该值根据array.slice切割得到。
      result[resIndex++] = array.slice(index, (index += size))
    }
    //输出新数组
    return result
  }
  //核心思想 result内的数组个数，数组包含数据
```
