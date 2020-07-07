文档名称|花样衣橱-产品需求文档
---|:--:|
产品名称|花样衣橱
产品描述|一款利用图像分类识别，帮你分类整理衣物，随时随地快速定位寻找每日着装的APP。
产品版本|1.0
文件现状|进行中
文件作者|余宗怡
## 一、PRD 价值主张设计 15%
### PRD1.加值宣言 3%

应用市场上已经有不少衣橱管理的 App 了，但一一体验过之后，找不出一个完全符合心意的。有的是界面和交互不忍直视，有的是年久失修不可靠，还有的是加入了过多社区和电商元素显得臃肿，这样的情况又让我重新生出了能做出一个同类产品中最简洁最好用的 App 的自信。最终才有了「花样衣橱」的诞生。其中，该App使用到的人工智能技术有计算机视觉中的图像分类api技术、图像识别api技术。

### PRD2。核心价值（最小可行产品，最小可用产品）3％

一个帮你整理衣橱d搭配每日着装的APP。分类整理你的衣物，随时随地快速定位寻找心仪搭配，让您不再为衣物无序烦恼，穿衣搭配更加方便。推送国内外最新时装资讯，让你一秒变身潮人。内设天气查看页，近期天气一目了然，让您穿衣、备衣无需烦恼。

### PRD3。核心价值与用户痛点3％
用户痛点宣言：
1. 衣物分类拍照需要大量时间
2. 衣物分类太少（应增加自行添加类别功能）
3. 各类场合衣物统计分类少
4. 穿着场合季节衣物不可通用
5. 希望断网也能使用
6. 导入淘宝等购物网站的购买记录
7. 目前相关APP广告太多
8. 国外相关APP下载复杂需收费
9. ootd抠图操作艰难

核心价值|用户痛点|API价值
---|:--:|---:
精确找到商品图|现场拍摄图片不满意|百度图像搜索api
实现图像裁剪或背景虚化等功能|ootd抠图操作艰难|百度图像主体检测api
提升手机相册图片过亮过暗问题|拍摄衣物单品颜色与实际有出入|百度图像效果增强

### PRD4.人工智能概率性与用户痛点 3% 

衣物给人带来的最直接的感受就是视觉感受。因此，花样衣橱将「图片」视为单品最基础的属性并进行人工智能化。

百度图像搜索api|百度图像主体检测api|百度图像效果增强api
---|:--:|---:
体量大：自建图库支持亿级图片量上传入库，实现实时检索，单图毫秒级响应——担心找不到单品图|准确率高：对用户输入内容进行词性标注及词汇重组——用户意图定义不准|能力丰富:提供业界最丰富的图像处理能力——图像偏小、不清晰、被拉伸
技术优：配套的图库管理后台，可对图库进行可视化增、删、改、查——商品搜索查找慢|快速：接入通用物体和场景识别接口，为图库图片批量打标签——分类时间长|算法领先：基于百度海量数据和算法积累，提供业界领先的图像处理效果——拍摄衣物单品颜色与实际有出入
稳定性强：提供企业级稳定、精确的大流量服务——用户体验差|便捷：基于相似图片搜索技术，实现以图搜图——录入单品方式单一


### PRD5.需求列表与人工智能API加值 3% 
需求列表：使用人工智能的加值是否反映到需求列表（核心功能的排序上）且PRD列出明显有可行及可用的API
优先级|用户需求|API加值
---|:--:|---:
核心|衣物分类拍照需要时间短|百度图像搜索api
重要|图片编辑多样化|百度图像效果增强api
次重要|搭配功能丰富|百度图像主体检测智能美图api

## 二、用户分析
### 1.目标用户群：
- 核心用户：18~25岁的对穿衣搭配感兴趣的大学生
- 主要用户：26~40岁之间的对穿衣搭配感兴趣的年轻上班族
### 2.用户画像及使用场景
用户场景：小薇是在校的女大学生，最近想买一件红色碎花法式上衣但不知道和自己的白色牛仔裤是否搭配，怕自己没有衣物搭配。打开“花样衣橱”APP，导入碎花上衣图片，自由组合单品创建拼图，发现非常合适，于是决定购买。
用户场景：Joey是刚毕业3年的白领，每天上班的早上穿好衣服后，打开“花样衣橱”APP记录每日穿搭，并生成图片随手分享给闺蜜，也可以作为日后灵感参考。
## 三、竞品分析

## 原型 20% 
### 原型1.交互及界面设计 5% 交互及界面设计：在PRD文件中是否有说明且原型是否有做到：交互及界面设计的某个核心交互环节使用了人工智能的加值

### 原型2.信息设计 5% 信息设计：在PRD文件中是否有说明且原型是否有做到：信息设计的某个核心信息或设计使用了人工智能的加值

### 原型3.原型文档 5% 原型文档：多少程度上有提供MVP可交互的原型文档，供它人在Github上下载使用

### 原型4.口头操作说明 5% 口头操作说明：多少程度上在2-3分钟时间限制内，对听众留下了「的确这是个可行丶可用的人工智能加值产品」的印象

## API 产品使用关键AI或机器学习之API的输出入展示 15% 
### API1.使用水平 5% 使用水平：在PRD文件中是否有说明且展示，核心功能所应用的API之输入及输出

### API2.使用比较分析 5% 使用比较分析：在PRD文件中是否有说明且提供连结证据，所使用的API是查找过最适用的（主要竞争者无或比较次），如考量其成熟度丶性价比丶等等

### API3.使用后风险报告 5% 使用后风险报告：在PRD文件中是否有说明且提供连结证据，所使用的API类别的现在及未来发展性，如API市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用API）等等

### API4.加分项 3% 使用复杂度：用了2个以上机器学习与人工智能的API之输入及输出

## 产品未来发展趋势

api期末项目：花样衣橱（智能产品PRD+原型）
新工科DFD数据流程图
新商科价值主张出PRD
新文科产品原型PRD


左：
创造效益（我的产品能协助用户创造哪些效益）：
1.每天记录穿搭反馈思考才有提高
2.发现单品之间的搭配关系，唤醒你的衣柜
3.可以学习她人衣橱单品的数量和样式，以及她人服饰搭配

解决痛点（我的产品能协助用户解决哪些困难）：
1.分类和标签功能多样化
2.对打算清简衣柜的人非常实用
3.计算衣服的穿着频率，性价比，单次价格

产品/服务（我的产品特点）：
1.顺手一拍记录每天穿搭
2.衣橱管理功能，能导入自己衣柜里现有的衣物，很好的管理衣柜
3.统计功能，统计衣物花费，喜好的品牌，常用的单品，不常用的单品
4.系统可根据用户设置的自己身材
