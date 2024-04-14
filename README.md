### Hi there 👋

#### hugo版本
```markdown
hugo v0.112.0或更高版本(扩展版)
```

##### 启动hugo服务器
```shell
hugo server
```

##### 启动hugo(包含草稿内容)
```shell
hugo server --buildDrafts

hugo server -D

hugo server -D --disableFastRender
```

#### 添加内容
```shell
hugo new content posts/xxx.md
```

#### 更新主题
```markdown
# 更新所有模块
hugo mod get -u
# 更新所有模块及其依赖
hugo mod get -u ./...
# 更新一个模块
hugo mod get -u github.com/hugo-fixit/FixIt
# 获取特定版本（例如 v0.3.2, @latest, @master, @dev）
hugo mod get github.com/hugo-fixit/FixIt@v0.3.2
```