项目目标
总体概述
“人，想知道本喵是谁吗？”
“人，想知道本喵的成长轨迹吗？”
“人，想体验和本喵交流的温暖吗？”
以鼓楼校区流浪猫为纽带，我们致力于打造一个兼具实用性与人文关怀的数字化社区平台。通过数据聚合、用户共创与智能算法，不仅为猫咪建立数字档案，更将冰冷的代码转化为温暖的情感联结——用技术守护生命，用交互传递善意，让每一行代码都承载对流浪猫的关怀，让每一次点击都成为人与猫双向治愈的契机。

猫咪信息库采用结构化标签+自由叙事结合的设计，既通过疫苗接种状态、出没热力图等数据客观守护猫咪健康，又以"性格画像""成长日记"等栏目展现每只猫的独特灵魂，让数据成为生命故事的载体，体现了数据背后的生命关怀。

同时，治愈语录生成器融合校园热点词库，让"猫咪的话"精准抚慰学生压力，地图导航引擎关联猫咪习性时间表，让偶遇不再靠运气而靠温暖的设计，体现了算法驱动的善意连接
具体功能
猫咪档案
展示猫咪个喵信息
目的：展现校内猫咪形象，增进爱猫群众对校内猫咪的认识，从而建立起更好的人猫互动关系。
• 名字
• 出没地
• 性格
• 健康状况
    ◦ 疫苗接种情况
    ◦ 其他身体状况（肥瘦相间）
• 领养情况
猫咪日记
目的：记录猫咪成长，构建社区，增进互动，让人能够云吸猫。
• 支持用户上传文字或照片，分享趣事
• 可进行点赞、评论等交流互动
• 按猫咪名字分类（若用户不认识这只猫，提供未知分类）
猫咪地图
目的：便于人类找到小猫
鼓楼校区地图分块 显示每片区域常常出没的猫咪
猫咪的话
目的：治愈身心疲惫的大学生
随机生成猫咪第一人称的治愈段子，如“人 你可以在猫宽广的胸膛里哭泣”
周热搜
目的：为有需要的猫咪寻找领养、筹款，从而更好的帮助有需要的猫猫；分享猫咪趣事，让繁忙的人能够“一键吸猫”
• 按需发布领养、筹款信息
• 选取展示互动性强的日记内容
实用性与创新性
实用性评估
当下，校园流浪猫的相关信息（如领养、介绍等）大多由社团公众号发布，与活动信息、社团招新等相杂糅，且没有明确表明是否已成功找到领养。同时，校猫作为校园中极受欢迎的群体，常常有学生与它们互动。
然而，一方面，互动时发生的趣事往往只能分享到校园集市、小红书或朋友圈，分散在其它日常之中，并且既无法精确推送给本校的爱猫人群，也无法形成一个线性轨迹；另一方面，由于不知道猫猫的性格与疫苗接种情况，学生因强行撸猫或喂猫失误而被抓伤的情况也时有发生，不利于学生与猫猫的健康和良好关系。
综合以上现存问题，我们期望开发出一个网页，对猫猫的基本信息和成长轨迹进行汇总，从而促进人猫之间的温暖互动。
前人类似工作参考
北大猫猫图鉴小程序
创新点
本项目旨在将流浪猫管理从传统的救助层面提升至情感联结、社区共治的新高度，注重实用性与人文关怀。
相较于简单的归档管理，我们在此基础上增添了用户自主记录、社区互动、猫咪的话、周热搜等功能。它们可分别实现以下目的：
用户自主记录、社区互动：形成爱猫社群，将猫咪信息精准地推送给每一个关心小猫的群体，让所有人能共同关注、记录猫咪成长。
猫咪的话：人猫交互不止停留在学生对流浪猫的单向救助。该功能让人在无法真实接触到小猫的时候，能够从赛博场景中汲取来自猫咪的温暖与抚慰。
周热搜：高亮了急需救助或领养的猫咪信息，提高他们得到帮助的效率。其中的猫咪趣事也让人能够快速得知本周的校园猫咪发生了哪些趣事。
具体实现
技术使用
目标：完成一个可分享的网页，支持以上功能
技术栈：HTML/CSS/JavaScript + Vue.js + SpringBoot
Git 版本控制：管理源码和协同开发，可以托管在 GitHub、GitLab 等平台，便于多人协作和代码回溯。
1. 项目概述
以鼓楼校区流浪猫为纽带，打造一个兼具实用性与人文关怀的数字化社区平台，通过数据聚合、用户共创与智能算法，为猫咪建立数字档案，提供多种功能服务，实现人与猫的温暖联结。
2. 技术栈
• 前端 ：HTML/CSS/JavaScript 作为基础，Vue.js 作为前端框架。
• 后端 ：SpringBoot 作为后端框架，Java 作为后端开发语言。
3. 开发工具
• 后端开发软件 ：IntelliJ IDEA
• 前端开发软件 ：Visual Studio Code
4. 项目架构
• 前端部分 ：WordPress 作为基础平台，利用其强大的页面管理、主题定制等功能，结合 Vue.js 构建动态、交互式的前端用户界面。将 HTML/CSS/JavaScript 与 Vue.js 代码集成到 WordPress 的主题文件中，通过 WordPress 的模板系统和路由机制，实现各个功能页面的展示和跳转。
• 后端部分 ：SpringBoot 构建稳定、高效的后端服务，处理业务逻辑、数据存储与访问等任务。通过定义清晰的 RESTful API 接口，与前端进行数据交互，为前端提供所需的各种数据服务，确保项目的整体功能正常运行。
5. 开发流程
1. 在 WordPress 中创建相应的页面或模板结构，用于承载各个功能模块的内容。
2. 使用 Visual Studio Code 进行前端的 HTML/CSS/JavaScript 以及 Vue.js 代码编写，完成前端页面的静态布局和动态交互逻辑的初步实现，并将代码集成到 WordPress 主题中。
3. 通过 IntelliJ IDEA 开发 SpringBoot 后端项目，设计数据库结构，实现各类数据的存储、管理和接口服务功能，保证后端接口的稳定性和可靠性。
4. 进行前后端联调，确保前端页面能够正确获取和展示后端提供的数据，各个功能模块的交互操作能够正常执行，不断完善和优化项目的功能和性能。
5. 在本地开发环境测试通过后，将项目部署到服务器上，进行上线前的最后测试和准备工作，确保项目能够稳定运行并对外提供服务。
通过以上技术介绍和开发工具使用说明，可以按照相应规范和流程，结合 WordPress 与所选技术栈完成这个以鼓楼校区流浪猫为主题的数字化社区平台项目。
主要任务与项目分工
前端：
框架：vue
人员：胡雨晨，王子兮
后端：
框架：springboot
人员：郭恩熙，孙静怡
前后端衔接：
人员：胡雨晨，王子兮，郭恩熙，孙静怡
UI设计
主页面
猫咪档案
//todo
本周热搜
//todo
猫咪地图
//todo
代码实现
vue源码：vuejs/vue: This is the repo for Vue 2. For Vue 3, go to https://github.com/vuejs/core
vuejs/core: 🖖 Vue.js is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.
springboot实践学习样例：527515025/springBoot: springboot 框架与其它组件结合如 jpa、mybatis、websocket、security、shiro、cache等
前端


 
/* 基础样式 */
body {
font-family: '微软雅黑', sans-serif;
margin: 0;
padding: 20px;
background-color: #f9f9f9;
}
.section {
background: white;
border-radius: 15px;
padding: 20px;
margin-bottom: 30px;
box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
/* 导航样式 */
nav {
display: flex;
justify-content: space-around;
margin-bottom: 30px;
background: #ffd700;
padding: 15px;
border-radius: 10px;
}
nav a {
text-decoration: none;
color: #333;
font-weight: bold;
}
/* 猫咪档案卡片 */
.cat-card {
border: 1px solid #ddd;
padding: 15px;
margin: 10px;
border-radius: 10px;
width: 300px;
display: inline-block;
}
/* 地图样式 */
#campus-map {
width: 100%;
height: 400px;
background: url('map-placeholder.jpg') no-repeat;
background-size: contain;
}
/* 响应式布局 */
@media (max-width: 768px) {
.cat-card {
width: 100%;
}
}
 

 
猫咪档案 
猫咪日记 
猫咪地图 
猫咪的话 
周热搜 
 


 🐱 猫咪档案 
 
 


 📔 猫咪日记 


 

发布 
 
 
 


 🗺️ 猫咪地图 
 
 


 💬 猫咪的话 

 
 
获取新消息 



 🔥 周热搜 
 
 
 
// 猫咪数据
const cats = [{
name: "大橘",
location: "食堂门口",
personality: "亲人贪吃",
health: {
vaccine: true,
body: "肥胖"
},
adopted: false
}];
// 治愈语录
const messages = [
"两脚兽，你可以在本喵宽广的胸膛里哭泣",
"今天也是认真监督你学习的一天喵～",
"你的小鱼干分我一半，我的快乐分你一半",
"不开心的时候记得摸摸我的肚皮呀",
"我会一直陪着你，直到你找到属于自己的幸福",
"无论发生什么，我都会在你身边",
"你是我心中最闪亮的星星",
"生活就像一盒猫罐头，永远不知道下一罐是什么味道",
"每一只猫咪都是你生命中的小天使",
"我会用我的毛发温暖你的心",
"无论你走到哪里，我的心都会跟随你",
"你是我生命中最重要的存在",
"我会用我的爪子守护你",
"生活就像一场猫咪的冒险，充满惊喜和乐趣",
];
const catImages = [
"lineCat.jpg",
"eatCat.jpg",
"sadCat.jpg",
"coolCat.jpg"
];
// 初始化猫咪档案
function initProfiles() {
const container = document.getElementById('cat-profiles');
cats.forEach(cat => {
container.innerHTML += `

 ${cat.name} 
 📍 ${cat.location} 
 性格：${cat.personality} 
 疫苗：${cat.health.vaccine ? '✅' : '❌'} 
 领养状态：${cat.adopted ? '已领养' : '等待家'} 
 
`;
});
}
// 生成随机语录
function generateMessage() {
const msg = messages[Math.floor(Math.random()*messages.length)];
document.getElementById('cat-message').innerHTML =
<blockquote>"${msg}"</blockquote>;
const img = catImages[Math.floor(Math.random()*catImages.length)];
document.getElementById('cat-words-img').src = img;
}
// 日记表单提交
document.getElementById('diary-form').addEventListener('submit', function(e) {
e.preventDefault();
// 这里需要添加实际提交逻辑
alert('日记已提交（需后端支持）');
});
// 初始化
window.onload = function() {
initProfiles();
generateMessage();
}
 


教程汇总
网页开发教程：qianguyihao/Web: 千古前端图文教程，超详细的前端入门到进阶知识库。从零开始学前端，做一名精致优雅的前端工程师。
B站前端开发教程：前端Web开发HTML5+CSS3+移动web视频教程，前端web入门首选黑马程序员_哔哩哔哩_bilibili
【WordPress建站教程67集（全） 零基础新手搭建外贸网站 企业官网 个人博客  跨境电商独立站】 https://www.bilibili.com/video/BV1AG4y1Q7sV/?p=2&share_source=copy_web&vd_source=58ab5a0c5df37169469c3d2a0dacea4c
