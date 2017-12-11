# React单页多页混用history API fallback
## 项目介绍
* React单页多页混用时防止404问题的插件。

## 目录结构
```
+lib  库目录

```

## 使用方法
```
npm install connect-history-multi-fallback

const app = express();
app.use('/', require('connect-history-multi-fallback')());
app.static('xxx');
```
