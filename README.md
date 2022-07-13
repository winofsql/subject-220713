# subject-220713

### 氏名
```html
                required
                size="50"
                maxlength="50"
                pattern="[ 　一-\u9FA5|ァ-ンヴー|ぁ-んー]+"
```

### フリガナ
```html
                size="50"
                maxlength="50"
                pattern="[ 　ァ-ンヴー]+"
```

### 給与
```
            <input class="form-control data w100"
                required
                pattern="[0-9]+"
                maxlength="6"
```

### 手当
```
            <input class="form-control data w100"
                pattern="[0-9]+"
                maxlength="5"
```

### 管理者
```
            <input class="form-control data w100"
                pattern="[0-9]+"
                maxlength="4"
```


### jQuery : parents( セレクタ) による、先祖の直接取り出し
- parent().parent() はおじいちゃんを経路で取り出す
- parents(".body") は、おじいちゃんの特徴で取り出す
