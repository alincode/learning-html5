# Selector 選擇器

```html
<footer id="layout-footer" class="myclass">
    <address>OOXX</adress>
</footer>
```

### 種類

**universal 通用選擇器**

```
* {...}
```

**ID 選擇器**

```
#layout-footer {...}
```

**class 類型選擇器**

```
.myclass {...}
```

**type 型態選擇器**

```
footer {...}
```

**child 子選擇器**

```
footer > address {...}
```

**descendant 後代選擇器**

```
footer address {...}
```

**attr 屬性**

```
:invalid {
  background-color: grey;
}
```

### 常見錯誤的使用

**錯誤一**

```
footer + address {...}
```

**錯誤二**

```
footer >> address {...}
```

**錯誤三**

```
footer ~ address {...}
```

### 更多範例

```css
li:nth-child(4n){
  margin-right:0px;
}
```

### 延伸閱讀

* [The 30 CSS Selectors You Must Memorize by Tutplus](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)
* [CSS4 selector 測試](http://css4-selectors.com/browser-selector-test/)
* [W3C Selectors Level 4 - W3C Working Draft 2](https://www.w3.org/TR/selectors4/)
