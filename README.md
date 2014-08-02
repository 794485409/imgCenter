imgCenter
=========

让图片自适应宽高而不拉伸

### 1.1.7 修改

```js
  $img$.imgBolt(imgElement[, backgroundSize][, data-imgCenter]);
```

### 1.1.6 新增接口

```js
  $img$.imgBolt(imgElement);
```

### 1.1 版本使用方法

将本页全部图片自适应宽高而不拉伸

```js
  $img$();
```

选中 ID 的图片自适应宽高而不拉伸，如选中 ID 非 IMG 标签，则遍历其所有子元素

```js
  $img$(['ID1', 'ID2', 'ID3']);
```


### 1.0 版本使用方法

将本页中第一个图片自适应宽高而不拉伸

```js
  $img$();
```