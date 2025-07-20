# fast-llm-template

一个简单的基于 fast-api 的 llm 模板

## 目录

- main.py 主程序
- app 业务逻辑
- log 日志
- tests 测试

## 技术栈

langchain + openai

fastapi + uvicorn + poetry + uv

## env

uv + poetry

### 安装 uv

下载 https://github.com/astral-sh/uv/releases

```bash
which uv
```

### 项目环境:

```bash
uv venv
source .envrc
uv pip install -r uv.poetry.txt
uv pip install -r requirements.txt

python main.py
```

## QA
