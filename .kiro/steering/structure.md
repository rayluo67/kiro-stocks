# 项目结构

## 目录组织

```
├── docs/                    # 项目文档
│   ├── 技术要求.md          # 技术规范文档
│   └── 股票管理系统需求整理v2.md  # 需求文档
├── backend/                 # 后端代码 (Flask)
│   ├── app.py              # 主应用入口
│   ├── models/             # 数据模型
│   ├── routes/             # API路由
│   ├── services/           # 业务逻辑
│   ├── utils/              # 工具函数
│   └── requirements.txt    # Python依赖
├── frontend/               # 前端代码 (React)
│   ├── src/
│   │   ├── components/     # React组件
│   │   ├── pages/          # 页面组件
│   │   ├── services/       # API调用
│   │   ├── utils/          # 工具函数
│   │   └── App.js          # 主应用组件
│   ├── public/             # 静态资源
│   └── package.json        # 前端依赖
├── .venv/                  # Python虚拟环境
├── .gitignore              # Git忽略文件
└── README.md               # 项目说明
```

## 模块组织原则

### 后端结构
- **models/**: 数据库模型和数据结构定义
- **routes/**: API端点定义，按功能模块分组
- **services/**: 业务逻辑实现，与数据库交互
- **utils/**: 通用工具函数和辅助方法

### 前端结构
- **components/**: 可复用的UI组件
- **pages/**: 页面级组件，对应不同的功能模块
- **services/**: API调用封装
- **utils/**: 前端工具函数

## 命名约定

### 文件命名
- Python文件: 使用下划线命名 (snake_case)
- React组件: 使用大驼峰命名 (PascalCase)
- 普通JS文件: 使用小驼峰命名 (camelCase)

### 目录命名
- 使用小写字母和下划线
- 功能模块目录按业务逻辑分组