# calendar

- [calendar_todo](https://github.com/taihangg/calendar_todo)修改版

日历 农历算法源自许剑伟先生的寿星万年历。
万年历的代码移植自HongchenMeng先生的c#移植项目，地址：https://github.com/HongchenMeng/SharpSxwnl
感谢许剑伟先生！感谢HongchenMeng先生!


## todo部分删除不用

- calendar部分剥离出来单独使用

- 节日内容字数过多将会滚动显示。


# build apk

```bash
flutter build apk --obfuscate --split-debug-info=build --release --build-name=1.1.6 --build-number=8
```
## 添加内容

1. 日干支
2. 日建除
3. 二十八宿(日禽)
4. 宗教节日

# 待修正

1. 阳历日期节日滚动显示不完整
2. 宗教节日显示到页面底部

![calendar](./calendar.png)

