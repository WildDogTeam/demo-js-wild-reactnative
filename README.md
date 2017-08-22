## Wilddog + React Native 开发示例
根据官网 ListItem 示例改造而来的简单 Demo, 我们使用 Wilddog API 让它具备了实时同步数据的能力。

### 开发环境
- React Native 0.2.0 以上版本
- Wilddog JS SDK 2.5.15 +


### 如何运行这个 Demo


+ ```react-native init <YOUR_DIR_NAME>```

+ ```cd <YOUR_DIR_NAME>```

+ ```npm install --save wilddog```

+ 拷贝 styles.js、index.ios.js 和 components 目录中的所有内容到 ``<YOUR_DIR_NAME>``

+ 将 index.ios.js 的最后一行修改为 `AppRegistry.registerComponent('YOUR_DIR_NAME', () => WilddogList);`

+ ```react-native run-ios```

### 在已有的 React Native 项目中引入 Wilddog

```
npm install --save wilddog
```

### 备注

我们这里只实现了 iOS 版本的示例,所以相关代码都在 `` index.ios.js `` 中, Android 版本上使用 Wilddog 的方式与 iOS 版本并无不同之处
