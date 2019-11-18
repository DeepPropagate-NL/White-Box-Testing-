# junit + jacoco  白盒测试训练

## 你需要去了解的

junit、jacoco、maven

## 你需要做的

在这个实验里，你需要完成部分简易程序的实现，并使用junit对其功能性进行单元测试，且使用jacoco对你的测试用例进行覆盖率检测，你可能需要掌握的：junit、jacoco、maven。为减少你们对环境的配置时间以及便于我们的管理，我们创建了统一的模版仓库，并已经配置好了junit、jacoco环境。

1. 首先你需要将这份maven项目克隆至本地，并进入项目工程目录使用命令`mvn test`进行测试（你也可以选择将这个项目导入到Eclipse或Intellij等工具中在导航栏选择Run as maven test）；

2. 随后你会发现在`/target/site/jacoco`目录下有一个产生了一个名字为`index.html`的文件（至于为什么会产生，请查看pom.xml配置），在浏览器打开这个文件，你会看到下图：
![image](https://github.com/2019NJUSAT/White-Box-Testing-/blob/master/IMG/image-20191115210656311.png)
  

  

以  Method3为例，在HelloWorldTest中仅对Method3进行了两次测试，导致Method3的语句覆盖率和分支覆盖率均未达到100%，如下所示：

![image-20191115210743488](https://github.com/2019NJUSAT/White-Box-Testing-/blob/master/IMG/image-20191115210743488.png)

其中绿色表示你的测试用例所覆盖的分支或语句，红色表示没有覆盖的分支或语句，黄色表示没有覆盖完全。

3. 你需要完成对Method3测试用例的更新，完成语句分支覆盖率达到100%。
4. 你需要完成对HelloWorld.java中未完成方法的实现，并对所有方法编写其测试函数，验证其功能的正确性并且保证覆盖率到达最高。

## 提交方式

将github链接分享给助教，在README里截图最后的html报告
