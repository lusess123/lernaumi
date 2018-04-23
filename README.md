# lernaumi

## 一个使用lerna + umi 的简单例子,用于测试umi是否可以编译插件项目的tsx文件，并且是否有watch功能


## Quickstart

 ### npm i

 ### npm run umi-host


 ## 测试结果


 默认情况下，无法加载react-plug 项目下的plug1.tsx文件


 当修改代码，  af-webpack/lib/getconfig.js   注释掉 396行代码

 ···
  // include: opts.cwd,
 ···

 可以加载成功，页面显示正常

 当修改plug1.tsx文件 ，可完成HRM

