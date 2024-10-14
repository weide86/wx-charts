

# 如何使用
1、直接引用编译好的文件 `dist/wxcharts.js` 或者 `dist/wxcharts-min.js`

2、自行编译

```
git clone https://github.com/xiaolin3303/wx-charts.git
npm install rollup -g
npm install
rollup src/app.js -o dist/wxcharts.js  -f cjs


