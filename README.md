
# Audio Explorer 鸟类音频系统


Audio Explorer 是一款数据可视化工具，来帮助研究人员分析特定位置的录音
           并可以随着时间的推移并验证其真实性。
挑战：Kasios Furniture（一家具公司）被指控在其工厂中使用违禁物质，并将废料倾倒在附近野生动植物保护区的东北地区。
           鸟类学家说，这直接导致了当地玫瑰凤冠蓝鸟的数量减少。 Kasios 驳斥了这一说法，并提供了 15 个记录在保护区内的音频文件，
           他们坚称这些文件证明了玫瑰冠蓝鸟鹭种群状况良好。 提供大量带有准确识别信息的记录鸟类叫声，
           我们的目标是检查 Kasios 声明的有效性，并表征保护区内所有物种随着时间的推移的模式。
## 网站在线运行地址 
http://119.3.227.48/ 
初始页为导航页 点击mc1、mc2进入相应的页面

#### 如需在个人电脑上运行此项目 请按如下说明运行

### Prerequisites 依赖环境 必须有node.js和Yarn环境才可以运行

Install [Node.js](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com) (if haven't already)

### Installing 安装 在依赖项的前提下进行项目运行

Clone the repository. Open terminal/commmand prompt and `cd` to root directory of the repo:
#### 进入项目目录
```
cd [repo directory] 
```
#### 安装依赖项
Type `yarn install` to install dependencies:
```
yarn install
```
## Deployment 运行

To view a development build of Audio Explorer, run: 
#### 本地运行
```
yarn serve
```

Alternatively, to create a production build:
#### 打包发布版本
```
yarn build
```
### 本地运行后网页打开
The web app can then be viewed at http://localhost:8080/
## Built With 我们的项目使用以下框架与包

* [Vue.js](https://vuejs.org/) - Front-end framework
* [Vue CLI](https://cli.vuejs.org/) - Standard tooling for Vue.js development
* [D3.js](https://d3js.org/) - Data processing library
* [Vue2Leafet](https://rometools.github.io/rome/) - Vue wrapper for [Leaflet](https://leafletjs.com/) interactive map library
* [Leatlet.heat](https://github.com/Leaflet/Leaflet.heat) - Heatmap plugin for Leaflet maps
* [wavesurfer.js](https://wavesurfer-js.org/) - Audio visualization and playback plugin
* [vue-slider-component](https://nightcatsama.github.io/vue-slider-component/example/) - Vue slider components
* [vue-sweetalert2](https://github.com/avil13/vue-sweetalert2) - Vue wrapper for [SweetAlert2](https://sweetalert2.github.io/)

## Authors 二次开发作者

### 孔启超 杨镐 二次开发

## 原作者
**Colin Scruggs** - [Github](https://github.com/colinscruggs)

**Cameron Henkel** - [Github](https://github.com/cameron-henkel)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details.
