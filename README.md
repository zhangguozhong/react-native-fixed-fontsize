# react-native-fixed-fontsize

react-native中固定字体大小，不会跟随系统字体大小变化
Android中TextInput allowFontScaling={false}对 占位符placeholder的文字大小无效，还是会跟随系统字体大小变化。


## 采取办法
通过修改TextInput的render方法将style中的fontSize缩小为系统字体大小缩放的倍数即可


## 使用方式
```
npm install react-native-fixed-fontsize --save
yarn add react-native-fixed-fontsize
```
项目目录中的index.js 和 index.ios.js 导入即可
