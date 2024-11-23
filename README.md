# Contact Manager

一个使用Flask框架开发的简单联系人管理应用，支持添加、编辑、删除、导出和导入联系人信息。

## 功能

- 添加和编辑联系人信息
- 删除联系人
- 导出联系人信息为Excel文件
- 从Excel文件导入联系人信息

## 技术栈

- **前端**：HTML, CSS, JavaScript, Font Awesome
- **后端**：Flask (Python)
- **数据库**：SQLite

## 安装和部署

### 环境要求

- Python 3.x
- Flask
- SQLite

### 安装步骤

1. 克隆项目到本地

2.进入项目目录：
   ```bash
cd contact_manager
```
3.创建虚拟环境（可选，但推荐）：
   ```bash
python3 -m venv venv
source venv/bin/activate  # 在Unix或Mac上
venv\Scripts\activate  # 在Windows上
```
4.安装依赖：
   ```bash
pip install -r requirements.txt
```
5运行应用：
   ```bash
python app.py
```
