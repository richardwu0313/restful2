# RESTful 2.0

RESTful 2.0 是一种新的 API 接口规范，旨在改进传统 RESTful API 的设计，提供更清晰、更一致的接口定义方式。

## 常见请求操作 URL 示例

### 资源查询
- `GET /api/v2/resources` - 获取资源列表
- `GET /api/v2/resource/{id}` - 获取单个资源
- `GET /api/v2/resources?filter=value` - 带过滤条件的查询
- `GET /api/v2/resources?page=1&limit=20` - 分页查询

### 资源创建
- `POST /api/v2/resources` - 创建多个新资源
- `POST /api/v2/resource` - 创建单个新资源

### 资源更新
- `PUT /api/v2/resource/{id}` - 完整更新资源
- `PATCH /api/v2/resource/{id}` - 部分更新资源

### 资源删除
- `DELETE /api/v2/resource/{id}` - 删除单个资源
- `DELETE /api/v2/resources` - 批量删除资源

## 规范特点

- **版本化管理**: 通过 URL 路径明确标识 API 版本
- **统一响应格式**: 标准化的响应结构，包含状态码、数据和消息
- **语义化 HTTP 方法**: 严格遵循 HTTP 方法的语义
- **资源导向**: 以资源为中心的设计，操作清晰明确
