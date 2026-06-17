# urobot-opensdk-java
uRobot SDK 是 具身智能中枢 `/api/open/v1` REST 接口，认证采用 AccessKey/SecretKey + SHA256 签名获取 JWT Token。现有集成方式需要调用方自行处理签名、Token 刷新、错误重试、分页遍历等逻辑。 Java 8+ 兼容。 
