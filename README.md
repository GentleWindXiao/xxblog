# My Knowledge Hub

用于记录个人学习的笔记系统，支持 Markdown 内容渲染、模块化分类、局部跳转及后续登录访问控制。

---

## ?? 项目结构

\\\
xxblog/
├── app/                         # Next.js 页面组件目录
│   ├── page.tsx                 # 网站首页
│   ├── notes/page.tsx          # 知识笔记页面
│   ├── papers/page.tsx         # 论文阅读页面
│   ├── algorithms/page.tsx     # 算法理解页面
│   └── games/page.tsx          # 游戏攻略页面
│
├── content/                     # Markdown 内容存放目录
│   ├── notes/first-note.md     # 示例笔记
│   ├── papers/os-paper.md      # 示例论文阅读内容
│   ├── algorithms/sorting.md   # 示例算法内容
│   └── games/game-guide.md     # 示例游戏攻略
│
├── public/                      # 静态资源目录
│   ├── images/                 # 图片资源
│   └── styles/                 # 额外样式
│
├── styles/globals.css           # 全局样式表
├── utils/                       # 工具函数目录
│   ├── markdownToHtml.ts       # 将 Markdown 转为 HTML
│   └── linkResolver.ts         # 实现 Markdown 内部跳转
│
├── package.json                 # 项目依赖与脚本配置
└── tsconfig.json                # TypeScript 配置文件
\\\

---

## ?? 功能说明

- ? 分类清晰，支持内容模块管理  
- ? 内容均为 Markdown，结构清晰易扩展  
- ? 兼容未来权限控制（登录锁内容）  
- ? 支持 Vercel 自动部署  
- ? 内部链接跳转便于内容交叉引用  

---

?? 持续扩展中，欢迎记录更多内容！
