---
name: java-backend-rules
description: Java后端规范，校验.java文件、Controller/Service层、异常处理、SQL安全
---
# Java 后端强制规范
1. 所有接口入参必须参数校验
2. IO、数据库操作必须try-catch，禁止空catch
3. 禁止直接拼接SQL字符串防止注入