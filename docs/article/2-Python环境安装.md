# <center>2 Python 环境安装

## 2.1 Python 解释器

### 2.1.1 解释器的作用

- Python解释器作用：运行文件
- Python解释器种类
  - CPython：C语言开发的解释器(官方)，应用广泛的解释器
  - IPython：基于CPython的一种交互式解释器
  - 其他解释器
    - PyPy：基于Python语言开发的解释器
    - Jython：运行在Java平台的解释器，直接把Python代码编译成Java字节码执行
    - IronPython：运行在微软.Net平台上的Python解释器，可以直接把Python代码编译成.Net的字节码

### 2.1.2 下载解释器

- 下载地址：https://www.python.org/downloads/release/python-372/
- 单击上述链接→查找目标文件：Windows x86-64 executable installer →单击即可下载

    ![图 3](../images/c1b131f72a8b4f1177223b3b2f2750d624ca605ae1a7ac717f3731d34df3b8b7.png)  



### 2.1.3 安装解释器

1. 选择在path中配置python3.6环境变量，然后尊则现在安装

    ![图 12](../images/720102883ba2480c1e0e4b6f3ed5aeeb18e45a6bc9c08d6b9611af2d0983635c.png)  

2. 等待程序安装

    ![图 13](../images/672d6b8347a1288d2a740d61a60dfae9fa65702cc31b3cff44bbd015e5ac19ff.png)  

3. 选择关闭

    ![图 14](../images/c500b4d3c3b49973df762f493ec64fbcc3727ee67536ad5bae1195e473569db6.png)  


 
- **注意：如果第一步未选择Add python 3.6 to Path，则需要手动配置环境变量**


- **手动配置环境变量步骤**

  1. 右键点击此电脑，选择属性选项

    ![图 1](../images/f564233484570db370a9c314cde7ca6c5d0239ce9e03880ecba562102641be54.png)  

  2. 选择高级系统设置

    ![图 3](../images/dd8d12005da6e410f2d3a332172c027450af537d458c191b0b544f5a265f0f32.png)  

  3. 选择环境变量

    ![图 4](../images/705fbc3a6376d1d587cbe1985ffbc52ce9b2e0136ab449e0ad8646b7973357d1.png)  

  4. 选择用户变量中的Path变量，点击编辑

    ![图 5](../images/a395c3ebce1ce2278585d0e517ba520b2ad1b61f532c76f27653e2344ed85902.png)  

  5. 双击打开我的电脑，在搜索栏输入python.exe并搜索找到对应搜索结果，有点选择打开文件所在位置

    ![图 6](../images/0c81412fe43d9b0330ed1a242da562995312b1c7410a5bcbe590976fa7887acc.png)  

  6. 赋值python文件所在位置的完整路径

    ![图 7](../images/f915a8b560ec73dddd91641722e63202a6ce924cc6e7f1c9d0766fd91cb64d30.png)  

  7. 回到环境变量，选择新建，并将刚才赋值的路径填入其中

    ![图 8](../images/54292ba42e44c6015f6b1a42023aa27cd5725b7f8995a6ad5583dd23f5449b19.png)  

  8. 再次点击新建，将刚才的路径粘贴到其中，并在结尾添加`\Scripts`

    ![图 9](../images/e232b734059e5acde997582e88f36c259df061ee835fc247ad8d8b86be22281a.png)  

  9.  使用windows + R键调出运行窗口，输入cmd命令，点击确定

    ![图 10](../images/5f920f3283ff5200907449f9600f869f95dc65527bc0fe3ecc6683c7bc7480a3.png)  

  10. 在命令行中输入python，并回车，如果出现如图所示版本信息即为配置完成

    ![图 11](../images/c1a467af111097d0f32e08066fd199b2304d4ce63fbdd0b2b21390fcf3fb3a55.png)  



## 2.2 PyCharm

### 2.2.1 PyCharm 的作用

- PyCharm是一种Python IDE（集成开发环境），带有一整套可以帮助用户在使用Python语言开发时提高其效率的工具，内部集成的功能如下：
  - Project管理
  - 智能提示
  - 语法高亮
  - 代码跳转
  - 调试代码
  - 解释代码(解释器)
  - 框架和库
  - ......

### 2.2.2 PyCharm 下载

- 下载地址：http://www.jetbrains.com/pycharm/download/#section=windows
- 下载专业版

### 2.2.3 PyCharm 破解教程

1. 破解文件下载：链接：https://pan.baidu.com/s/1zNjCkSgYQ9q1Fk5IL1AonA?pwd=p55x 
2. 破解教程：https://www.exception.site/essay/how-to-free-use-pycharm-2020
3. 设置中文：https://www.zcscl.com/p/5869.html
4. 关闭自动更新：https://www.csdn.net/tags/MtTaAg3sNTA5NDM3LWJsb2cO0O0O.html
5. 新建项目：https://blog.csdn.net/lehocat/article/details/123579981