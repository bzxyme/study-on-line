# Note

## GIT 命令

### 创建分支

```
git checkout -b xxxx
```

### 删除分支

```
git branch -d xxxx
```

### 切换分支

切换主分支

```
git checkout master
```

### 合并分支

在 master 分支下

```
git merge xxxx
```

### 添加远程仓库

```
git remote add 别名 仓库地址
```

### 更新远程仓库地址

```
git remote set-url 别名 仓库地址
```

### 提交远程仓库

```
git add .
git commit -m 'xxx'
第一次提交：
git push -u xxx xxxx
```

---

## CSS 书写顺序

```
1.布局定位属性：display/position/float/clear/visibility/overflow(建议display第一个写，关系到模式)
2.自身属性：width/height/margin/padding/border/
3.文本属性：color/font/text-decoration/text-align/vertical-align/white-space/break-word
4.其他属性(CSS3)：content/cursor/border-radius/box-shadow/text-shadow/background:linear-gradient...
```

---

## 导航栏注意点

**实际开发中，不会直接使用 a 链接而是使用 ul 标签包含链接（ul+li+a）的做法**

```
1.ul+a语义更清晰，一看就是有条理的列表型内容
2.如果直接使用a标签，搜索引擎容易判别有堆砌关键字嫌疑（有降权风险）
```

```
1.给li加浮动，因为li是块级元素，需要一行显示。
2.nav导航栏可以不给宽度，将来可以继续添加其与文字
3.导航栏文字不一样多，所以给a标签左右padding撑开盒子，而不是指定宽度
```

---
