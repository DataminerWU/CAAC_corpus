民航机场领域专业文本处理工具：
提供民航术语精准分词、词性标注和API服务

功能特性：

🛩 民航专属词典包含5000+专业术语
⚡ FastAPI高性能后端
📦 支持Docker一键部署
📈 自动术语发现更新机制
快速开始
# 下载词典和语料库
git clone https://github.com/DataminerWU/aviation-nlp.git

# 启动API服务
docker-compose up -d

# 测试请求
curl -X POST http://localhost:8000/segment \
  -H "Content-Type: application/json" \
  -d '{"text":"飞行区场地需要符合《飞行区技术标准》的要求"}'
