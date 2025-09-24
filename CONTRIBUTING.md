# MathAssert 贡献指南

感谢您对 MathAssert 项目的关注！我们欢迎所有形式的贡献。

## 🤝 如何贡献

### 报告问题
- 使用 [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) 模板报告问题
- 提供详细的重现步骤和环境信息
- 如有可能，提供截图或错误日志

### 建议功能
- 使用 [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md) 模板提出新功能
- 详细描述功能需求和预期行为
- 提供使用场景和用户故事

### 代码贡献
1. Fork 项目仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'feat: add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📋 开发规范

### 代码风格
- 使用 TypeScript 进行类型安全的开发
- 遵循 ESLint 和 Prettier 的代码规范
- 使用语义化的提交信息格式

### 提交信息格式
```
<type>(<scope>): <subject>

<body>

<footer>
```

#### Type 类型
- `feat`: 新功能
- `fix`: Bug 修复
- `docs`: 文档更新
- `style`: 代码格式化
- `refactor`: 重构
- `test`: 测试相关
- `chore`: 构建工具或依赖管理

#### 示例
```
feat(auth): add user login functionality

- Add login form component
- Implement authentication service
- Add user session management

Closes #123
```

### 测试要求
- 所有新功能必须包含单元测试
- 测试覆盖率不得低于 80%
- 运行 `npm test` 确保所有测试通过

### 文档要求
- 所有新功能必须更新相关文档
- 提供 API 文档和使用示例
- 更新 README 和项目文档

## 🏗️ 项目结构

```
mathassert/
├── src/                    # 源代码
│   ├── components/         # React 组件
│   ├── pages/             # 页面组件
│   ├── lib/               # 工具库
│   ├── hooks/             # React Hooks
│   ├── types/             # TypeScript 类型定义
│   ├── utils/             # 工具函数
│   └── index.ts           # 主入口文件
├── docs/                  # 项目文档
├── .github/               # GitHub 配置
├── scripts/               # 自动化脚本
└── tests/                 # 测试文件
```

## 🧪 测试

### 运行测试
```bash
# 运行所有测试
npm test

# 运行特定测试
npm test -- --testNamePattern="Auth"

# 监视模式
npm run test:watch
```

### 测试覆盖率
```bash
npm run test:coverage
```

## 🚀 开发环境

### 环境要求
- Node.js >= 18.0.0
- npm >= 8.0.0

### 安装依赖
```bash
npm install
```

### 开发模式
```bash
npm run dev
```

### 构建项目
```bash
npm run build
```

## 🔍 代码审查

### 审查清单
- [ ] 代码符合项目规范
- [ ] 测试覆盖充分
- [ ] 文档完整更新
- [ ] 提交信息格式正确
- [ ] 无明显性能问题
- [ ] 安全性检查通过

### 审查流程
1. 自动化检查（CI/CD）
2. 同伴审查（至少一人）
3. 维护者审查
4. 合并到主分支

## 📝 发布流程

### 版本号规则
遵循 [Semantic Versioning](https://semver.org/) 规范：
- `MAJOR.MINOR.PATCH`
- `MAJOR`: 不兼容的 API 更改
- `MINOR`: 向后兼容的功能添加
- `PATCH`: 向后兼容的错误修复

### 发布步骤
1. 更新版本号
2. 更新 CHANGELOG
3. 创建 Git 标签
4. 发布到 GitHub
5. 部署到生产环境

## 🎯 质量标准

### 代码质量
- **测试覆盖率**: ≥ 80%
- **代码复杂度**: 圈复杂度 ≤ 10
- **代码重复率**: ≤ 3%
- **安全漏洞**: 0 个高危/严重漏洞

### 性能标准
- **页面加载**: 首屏 ≤ 3 秒
- **构建时间**: ≤ 5 分钟
- **包大小**: 主包 ≤ 1MB

## 📞 联系方式

- **项目主页**: https://github.com/crowdownmoon/mathassert
- **问题反馈**: https://github.com/crowdownmoon/mathassert/issues
- **团队邮箱**: crowdownmoon@gmail.com

## 📄 许可证

通过贡献代码，您同意您的贡献将在 [MIT License](LICENSE) 下发布。

---

**感谢您的贡献！** 🎉