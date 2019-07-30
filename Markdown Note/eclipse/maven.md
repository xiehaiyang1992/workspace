# Maven使用教程
## 使用阿里Maven源
> 编辑文件 C:\Users\user\.m2\settings.xml
> 
> eclipse-->窗口-->首选项-->maven-->user settings选中上一步的xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
	<pluginGroups>
	</pluginGroups>
	<proxies>
	</proxies>
	<servers>
	</servers>
	<mirrors>
		<mirror>
			<id>aliyunmaven</id>
			<mirrorOf>*</mirrorOf>
			<name>阿里云公共仓库</name>
			<url>https://maven.aliyun.com/repository/public</url>
		</mirror>
	</mirrors>
	<profiles>
	</profiles>
</settings>
```
