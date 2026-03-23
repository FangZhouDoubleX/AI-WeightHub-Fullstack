# 🚀 WeightHub (Weight Management System)

> **项目目标**：打造一个全能体重管理系统，支持多端数据同步，实现独立交付。

## 🛠️ 技术栈 (Tech Stack)

| 领域         | 技术选型         | 备注                     |
| :----------- | :--------------- | :----------------------- |
| **全栈框架** | **Nuxt 3**       | Vue 3.5+ / Nitro Server  |
| **数据库**   | **PostgreSQL**   | 容器化部署 (Docker)      |
| **ORM**      | **Prisma**       | 现代化类型安全数据库交互 |
| **PC 端 UI** | **Element Plus** | 极致开发体验             |
| **移动端**   | **Uni-app**      | Vue 3 版本，跨端触达     |
| **包管理**   | **pnpm**         | 高效依赖管理             |

## 📈 路线图 (Roadmap)
- [🏗️] **M1: 后端基石** - Nuxt Server + Prisma 核心接口实现
- [⏳] **M2: PC 终端** - Vue 3 业务管理看板开发
- [⏳] **M3: 移动触达** - Uni-app 跨端开发与对接
- [⏳] **M4: 工业部署** - Docker + Linux 自动化部署

## 🚀 快速开始
1. `pnpm install` 安装依赖
2. `docker-compose up -d` 启动数据库
3. `npx prisma db push` 同步数据库模型
4. `pnpm dev` 启动开发服务器
