### doch
类似与docz的一个文档服务，基于nextjs，易于集成，目前还在开发过程中

### 使用

#### 安装
```
npm i doch
```

#### 初始化
```
npx doch init
```
#### 启动
```
npx doch dev
```

#### 配置文件
这个不是必须的，项目根目录创建`.doch.json` 文件

```json
{
  "src": "./src/components"
}
```
配置scr为文档扫描目录，可以不配置，精确配置只是为了提升性能

## 之后的开发计划
[x] 提供类似docz那种可以复制源码的功能

[]添加搜索

[]添加标题

[x]过滤掉node_modules和隐藏文件夹
