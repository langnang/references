
# Array 对象

Array 对象用于在单个变量中存储多个值：

```js
const cars = ["Tesla", "Volvo", "BMW"];
```

数组索引从零开始：数组中的第一个元素是 0，第二个元素是 1，依此类推。

**Array 方法和属性**

| 方法                                                                                                     | 描述                                               |        |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ------ |
| [\[\]](/web/javascript/obj_array.md?id= "JavaScript Array []")                                           | 创建新数组。                                       |
| [new Array()](/web/javascript/obj_array.md?id=new-array "JavaScript new Array()")                        | 创建新数组。                                       |
| [at()](/web/javascript/obj_array.md?id=at "JavaScript Array at() 方法")                                  | 返回数组的索引元素。                               |
| [concat()](/web/javascript/obj_array.md?id=concat "JavaScript Array concat() 方法")                      | 连接数组并返回连接后的数组。                       |
| [constructor](/web/javascript/obj_array.md?id=constructor "JavaScript Array constructor 属性")           | 返回创建 Array 对象原型的函数。                    |
| [copyWithin()](/web/javascript/obj_array.md?id=copywithin "JavaScript Array copyWithin() 方法")          | 将数组中的数组元素复制到指定位置或从指定位置复制。 |
| [entries()](/web/javascript/obj_array.md?id=entries "JavaScript Array entries() 方法")                   | 返回键/值对数组迭代对象。                          |
| [every()](/web/javascript/obj_array.md?id=every "JavaScript Array every() 方法")                         | 检查数组中的每个元素是否通过测试。                 |
| [fill()](/web/javascript/obj_array.md?id=fill "JavaScript Array fill() 方法")                            | 用静态值填充数组中的元素。                         |
| [filter()](/web/javascript/obj_array.md?id=filter "JavaScript Array filter() 方法")                      | 使用数组中通过测试的每个元素创建新数组。           |
| [find()](/web/javascript/obj_array.md?id=find "JavaScript Array find() 方法")                            | 返回数组中第一个通过测试的元素的值。               |
| [findIndex()](/web/javascript/obj_array.md?id=findindex "JavaScript Array findIndex() 方法")             | 返回数组中通过测试的第一个元素的索引。             |
| [findLast()](/web/javascript/obj_array.md?id=findlast "JavaScript Array findLast() 方法")                | 返回数组中通过测试的最后一个元素的值。             |
| [findLastIndex()](/web/javascript/obj_array.md?id=findlastindex "JavaScript Array findLastIndex() 方法") | 返回数组中通过测试的最后一个元素的索引。           |
| [flat()](/web/javascript/obj_array.md?id=flat "JavaScript Array flat() 方法")                            | 连接子数组元素。                                   |
| [flatMap()](/web/javascript/obj_array.md?id=flatmap "JavaScript Array flatMap() 方法")                   | 映射所有数组元素并创建新的扁平数组。               |
| [forEach()](/web/javascript/obj_array.md?id=foreach "JavaScript Array forEach() 方法")                   | 为每个数组元素调用函数。                           |
| [from()](/web/javascript/obj_array.md?id=from "JavaScript Array from() 方法")                            | 从对象创建数组。                                   |
| [includes()](/web/javascript/obj_array.md?id=includes "JavaScript Array includes() 方法")                | 检查数组是否包含指定的元素。                       |
| [indexOf()](/web/javascript/obj_array.md?id=indexof "JavaScript Array indexOf() 方法")                   | 在数组中搜索元素并返回其位置。                     |
| [isArray()](/web/javascript/obj_array.md?id=isarray "JavaScript Array isArray() 方法")                   | 检查对象是否为数组。                               |
| [join()](/web/javascript/obj_array.md?id=join "JavaScript Array join() 方法")                            | 将数组的所有元素连接成一个字符串。                 |
| [keys()](/web/javascript/obj_array.md?id=keys "JavaScript Array keys() 方法")                            | 返回 Array Iteration 对象，包含原始数组的键.       |
| [lastIndexOf()](/web/javascript/obj_array.md?id=lastindexof "JavaScript Array lastIndexOf() 方法")       | 从数组末尾开始搜索元素并返回其位置。               |
| [length](/web/javascript/obj_array.md?id=length "JavaScript Array length 属性")                          | 设置或返回数组中元素的数量。                       |
| [map()](/web/javascript/obj_array.md?id=map "JavaScript Array map() 方法")                               | 使用为每个数组元素调用函数的结果创建新数组。       |
| [of()](/web/javascript/obj_array.md?id=of "JavaScript Array Array.of() 方法")                            | 从多个参数创建一个数组。                           |
| [pop()](/web/javascript/obj_array.md?id=pop "JavaScript Array pop() 方法")                               | 删除数组的最后一个元素，并返回该元素。             |
| [prototype](/web/javascript/obj_array.md?id=prototype "JavaScript Array prototype 属性")                 | 允许您向数组添加属性和方法。                       |
| [push()](/web/javascript/obj_array.md?id=push "JavaScript Array push() 方法")                            | 将新元素添加到数组的末尾，并返回新的长度。         |
| [reduce()](/web/javascript/obj_array.md?id=reduce "JavaScript Array reduce() 方法")                      | 将数组的值减为单个值（从左到右）。                 |
| [reduceRight()](/web/javascript/obj_array.md?id=reduceright "JavaScript Array reduceRight() 方法")       | 将数组的值减为单个值（从右到左）。                 |
| [reverse()](/web/javascript/obj_array.md?id=reverse "JavaScript Array reverse() 方法")                   | 反转数组中元素的顺序。                             |
| [shift()](/web/javascript/obj_array.md?id=shift "JavaScript Array shift() 方法")                         | 删除数组的第一个元素，并返回该元素。               |
| [slice()](/web/javascript/obj_array.md?id=slice "JavaScript Array slice() 方法")                         | 选择数组的一部分，并返回新数组。                   |
| [some()](/web/javascript/obj_array.md?id=some "JavaScript Array some() 方法")                            | 检查数组中的任何元素是否通过测试。                 |
| [sort()](/web/javascript/obj_array.md?id=sort "JavaScript Array sort() 方法")                            | 对数组的元素进行排序。                             |
| [splice()](/web/javascript/obj_array.md?id=splice "JavaScript Array splice() 方法")                      | 从数组中添加/删除元素。                            |
| [toReversed()](/web/javascript/obj_array.md?id=toreversed "JavaScript Array toReversed() 方法")          | 反转数组元素的顺序（到新数组）。                   |
| [toSorted()](/web/javascript/obj_array.md?id=tosorted "JavaScript Array toSorted() 方法")                | 对数组的元素进行排序（到新数组）。                 |
| [toSpliced()](/web/javascript/obj_array.md?id=tospliced "JavaScript Array toSpliced() 方法")             | 添加或移除数组元素（到新数组）。                   |
| [toString()](/web/javascript/obj_array.md?id=tostring "JavaScript Array toString() 方法")                | 将数组转换为字符串，并返回结果。                   |
| [unshift()](/web/javascript/obj_array.md?id=unshift "JavaScript Array unshift() 方法")                   | 将新元素添加到数组的开头，并返回新的长度。         |
| [values()](/web/javascript/obj_array.md?id=values "JavaScript Array values() 方法")                      | 返回包含数组值的迭代器对象。                       |
| [valueOf()](/web/javascript/obj_array.md?id=valueof "JavaScript Array valueOf() 方法")                   | 返回数组的原始值。                                 |
| [with()](/web/javascript/obj_array.md?id=with "JavaScript Array with() 方法")                            | 返回更新元素后的新数组。                           | ES2023 |

### `[]`

> 创建新数组。

### `new Array()`

> 创建新数组。

### `at()`

> 返回数组的索引元素。

### `concat()`

> 连接数组并返回连接后的数组。

### `constructor`

> 返回创建 Array 对象原型的函数。

### `copyWithin()`

> 将数组中的数组元素复制到指定位置或从指定位置复制。

### `entries()`

> 返回键/值对数组迭代对象。

### `every()`

> 检查数组中的每个元素是否通过测试。

### `fill()`

> 用静态值填充数组中的元素。

### `filter()`

> 使用数组中通过测试的每个元素创建新数组。

### `find()`

> 返回数组中第一个通过测试的元素的值。

### `findIndex()`

> 返回数组中通过测试的第一个元素的索引。

### `findLast()`

> 返回数组中通过测试的最后一个元素的值。

### `findLastIndex()`

> 返回数组中通过测试的最后一个元素的索引。

### `flat()`

> 连接子数组元素。

### `flatMap()`

> 映射所有数组元素并创建新的扁平数组。

### `forEach()`

> 为每个数组元素调用函数。

### `from()`

> 从对象创建数组。

### `includes()`

> 检查数组是否包含指定的元素。

### `indexOf()`

> 在数组中搜索元素并返回其位置。

### `isArray()`

> 检查对象是否为数组。

### `join()`

> 将数组的所有元素连接成一个字符串。

### `keys()`

> 返回 Array Iteration 对象，包含原始数组的键.

### `lastIndexOf()`

> 从数组末尾开始搜索元素并返回其位置。

### `length`

> 设置或返回数组中元素的数量。

### `map()`

> 使用为每个数组元素调用函数的结果创建新数组。

### `of()`

> 从多个参数创建一个数组。

### `pop()`

> 删除数组的最后一个元素，并返回该元素。

### `prototype`

> 允许您向数组添加属性和方法。

### `push()`

> 将新元素添加到数组的末尾，并返回新的长度。

### `reduce()`

> 将数组的值减为单个值（从左到右）。

### `reduceRight()`

> 将数组的值减为单个值（从右到左）。

### `reverse()`

> 反转数组中元素的顺序。

### `shift()`

> 删除数组的第一个元素，并返回该元素。

### `slice()`

> 选择数组的一部分，并返回新数组。

### `some()`

> 检查数组中的任何元素是否通过测试。

### `sort()`

> 对数组的元素进行排序。

### `splice()`

> 从数组中添加/删除元素。

### `toReversed()`

> 反转数组元素的顺序（到新数组）。

### `toSorted()`

> 对数组的元素进行排序（到新数组）。

### `toSpliced()`

> 添加或移除数组元素（到新数组）。

### `toString()`

> 将数组转换为字符串，并返回结果。

### `unshift()`

> 将新元素添加到数组的开头，并返回新的长度。

### `values()`

> 返回包含数组值的迭代器对象。

### `valueOf()`

> 返回数组的原始值。

### `with()`

> 返回更新元素后的新数组。  


**定义和用法**

`with()` 方法用于更新数组中指定的元素。

`with()` 方法返回新数组。

`with()` 方法不会改变原始数组。

**实例**

ES2023 新增了 `with()` 方法，作为一种在不改变原始数组的情况下更新数组元素的安全方式：

```js
const months = ["Januar", "Februar", "Mar", "April"];
const myMonths = months.with(2, "March");
```


**语法**

```js
array.with(index, value)
```

**参数**

| 参数    | 描述                                                              |
| ------- | ----------------------------------------------------------------- |
| _index_ | 必需。要更改的元素的索引（位置）。<br/>负索引从数组末尾开始计算。 |
| _value_ | 必需。新的值。                                                    |

**返回值**

| 类型  | 描述                       |
| ----- | -------------------------- |
| Array | 包含更改后的元素的新数组。 |