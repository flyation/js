# js类型转换
## xxx 2 boolean
```javascript
if (xxx) {
    alert(true)
} else {
    alert(false)
}
```
### undefined、null 2 boolean
undefined: false  
null: false  
### number 2 boolean
非0: true  
Infinity/-Infinity: true  
0: false  
NaN: false
### string 2 boolean
非'': true  
'': false
### [ ] 2 boolean
always true  
**结论：数组无法通过转布尔来判断属性的数量是否为0**
### { } 2 boolean
always true  
**结论：对象无法通过转布尔来判断长度是否为0**
