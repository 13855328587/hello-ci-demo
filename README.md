# Java Hello World CI/CD 项目

## 项目简介
本项目为基础 Java HelloWorld 程序，使用 Maven 构建，结合 GitHub Actions 配置 CI/CD 自动化流水线。
实现代码提交后自动编译、自动运行、自动单元测试。

## 技术栈
- Java 8
- Maven
- JUnit 5
- GitHub Actions

## 本地使用命令
编译项目
```
mvn compile
```
运行主程序
```
mvn exec:java -Dexec.mainClass="org.example.Main"
```
执行测试
```
mvn test
```
## 流水线功能
1. 拉取仓库代码
2. 自动配置 JDK8 环境
3. 项目编译检查
4. 运行程序
5. 自动化单元测试

## 项目文件结构
- src/main/java：主程序代码
- src/test/java：单元测试代码
- pom.xml：Maven 配置
- .github/workflows/ci.yml：自动化流水线配置

## 总结
通过 GitHub Actions 完成持续集成，保障代码可正常编译、运行与测试，熟悉 CI/CD 基础流程。