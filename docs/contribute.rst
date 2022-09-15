如何给此项目贡献
========================================================
第一步：安装Github并克隆此项目
--------------------------------------------------------
1.从 https://desktop.github.com/  下载安装好github desktop。

2.打开GitHub desktop。如果没有账号请点击Create your free account，如下图所示。

.. image:: /images/1.png

会弹出一个网站，填写网站所要求的信息,如下图所示。

.. image:: /images/2.png

输入邮箱收到的验证码，如下图所示。

.. image:: /images/3.png

后面的调查问卷可以不管。点击continue for free完成GitHub账号的注册。

4.注册完账户后，打开安装好的github desktop软件，点击sign in github。 会弹出一个网站，点击authorize desktop。然后会自动回到github desktop软件，点击finish。

5.接下来，点击Clone a repository from the Internet... 在弹出的框里选择URL。Repository URL中填写 https://github.com/abdusemiabduweli/CADD-tutorial  Local path选择一个你想要保存此项目的文件夹，点击Clone，如下图所示。

.. image:: /images/4.jpg

就这样在电脑上安装配置好了Github，也下载好了一份此项目，项目所在文件夹地址就是你刚才在Local path输入的地址。

第二步：安装python
----------------------------------------------------------
1.从 https://www.python.org/downloads/ 下载安装好python。

第三步：安装Visual Studio Code并搭建好环境
--------------------------------------------------------
1.从https://code.visualstudio.com/ 下载安装好visual studio code。

2.打开GitHub Desktop，在如下图1所示的地方选择此项目 CADD-tutorial， 并点击2所示的按钮Open in visual studio code，如下图所示，打开Visual studio code。

.. image:: /images/5.jpg

如果出现如下图的提示，打勾1所示的框，点击2所示的按钮。

.. image:: /images/6.jpg

3.在visual studio code中点击1所示的extensions按钮，搜索ext:rst，点击2和3所示的插件的install按钮，安装这两个插件。

.. image:: /images/7.jpg

4.同样的，点击extensions按钮，搜索python，安装第一个插件。安装完后会出现如下图所示的界面，点击1所示的按钮，再点击选择2所示的文件。

.. image:: /images/8.jpg

5.点击Visual studio code菜单栏上的Terminal-->New Terminal，下图中的1所示的按钮，在下方窗口中输入pip install sphinx sphinx-autobuild，点击Enter键，等待安装完成。一般再次出现PS D:\ 等字样时，表明安装完成。同样的操作，输入pip install furo，等待安装完成。

.. image:: /images/9.jpg

第五步：如何给此项目贡献
---------------------------------------------------------

如果完成了上面的操作，那么你的电脑上就保存着一份此项目。项目就在上面所示的Local path中的地址。如果打开文件夹，你能看到如下图一样的一堆文件和文件夹。

.. image:: /images/10.jpg

其中红色方框中显示的就是本网站（ https://cadd-tutorial.readthedocs.io） 的相关文件。改变我的Github账号上的CADD-tutorial项目中的这些文件，就等于改变本网站。浅绿色方框中的文件夹你可能看不到，这是因为我在深绿色方框中的文件（.gitignore）里列举了这个文件夹（用记事本打开此文件就能看到其内容）。.gitignore文件的详细介绍可以参考这个文章：https://www.jianshu.com/p/699ed86028c2 。剩余的文件都是我提供给你们的参考文献。这些文献大部分来自中国药科大学计算机辅助药物设计课程。因为我没有得到此课程负责老师们的同意（我没问，我怕他们不同意我上传这些文件到Github），所以我们的第一个目标是把这些文件都转换成rst文件。rst文件都在此项目docs文件夹里，后缀为.rst，这些rst文件都是遵循rst文件的语法规则，rst语法规则可以参考这个文章 https://www.sphinx-doc.org/zh_CN/master/usage/restructuredtext/basics.html#source-encoding。这些rst文件编辑完后上传到我的github账号中此项目时，会被自动 https://readthedocs.org/ 网站转换成html等文件保存在 readthedocs团队提供的服务器中。我们的此项目成果 https://cadd-tutorial.readthedocs.io （CADD教程网站）就是由它们免费提供的技术支持实现的，这里特地感谢他们。readthedocs不仅把rst文件转换成html文件，还会转换成PDF，Epub文件，这些文件可以点击下图所示的按钮下载。

.. image:: /images/11.jpg

我提供的文献都是PDF格式的，除非在电脑上阅读，但是其他设备上阅读起来非常差，也不能编辑。如果我们把我们的文献全部转换成了rst文件，我就能把这些pdf文件都删掉，这样也不会有任何版权问题。我们的此项目遵循GNU协议，包括我们的rst文件，详情请阅读项目中的LICENSE文件。

那么怎么编辑我们的项目成果 https://cadd-tutorial.readthedocs.io （CADD教程网站）？ 
前面提到了只要我们编辑此项目中docs文件夹中的文件和.readthedocs.yaml并上传到我的GitHub账号中的CADD-tutorial项目，CADD教程网站就会自动地被改变。.readthedocs.yaml文件是CADD教程网站的配置文件，可以先不管，若感兴趣，详情请阅读这个文章 https://docs.readthedocs.io/en/stable/config-file/index.html 。打开docs文件夹，你能看到以下文件

.. image:: /images/12.jpg

其中images保存此网站中用到的图片。Conf.py和requirements也是此网站的配置文件，也可以先不管，详情请阅读这些文章 https://www.sphinx-doc.org/en/master/usage/configuration.html https://pip.pypa.io/en/latest/user_guide/#requirements-files。其他的rst文件就是CADD-tutorial网站中各网页的内容，需要用rst语法规则编辑。rst语法规则可以参考这个文章 https://www.sphinx-doc.org/zh_CN/master/usage/restructuredtext/basics.html#source-encoding。打开我们的此项目成果-CADD教程网站 https://cadd-tutorial.readthedocs.io 就能看到首页，首页对应的rst文件是index.rst。在左侧能看到分子力学、分子动力学、定量构效关系、人工智能、基于结构的药物设计、基于配体的药物设计、如何给此项目贡献等网页。这些网页所对应的rst文件分别是   MolecularMechanics.rst MolecularDynamics.rst QSAR.rst AI.rst SBDD.rst LBDD.rst contribute.rst。编辑相应的rst文件就相当于编辑了相对应的网站。最后只需上传到我的github账号中CADD-tutorial项目中。

下面我给你们演示编辑“如何给此项目贡献”网页。
打开Github Desktop，选择CADD-tutorial，如下图所示

.. image:: /images/13.png

点击open in visual studio code打开visual studio code
点击docs,双击打开contribute.rst，如下图所示

.. image:: /images/14.png

编辑完此文件后要保存。如果想要看网页效果的话，点击右上角的如下图所示的按钮就能显示网页效果。

.. image:: /images/15.png

最终打开github desktop就能发现跟如下图相似的界面。

.. image:: /images/16.png

点击1所示的commit to master，再点击如下图所示的push origin

.. image:: /images/17.png

如果你账号没有此项目的fork的话，就会出现如下图所示的提示，需要点击fork this repository。这操作意味着你在你的账号中复制粘贴了我github中此项目的文件

.. image:: /images/18.png

如果你想要给此项目贡献，那你需要选择如下图中的第一个选项to continue to the parent project并点击continue。如果你想要独立建立此项目的克隆项目，那你选择第二个选项for my own purpuses并点击continue。 当然这里我希望你选择第一个。

.. image:: /images/19.png

然后你需要重新点击push origin。
然后，打开浏览器，打开github.com，登录你的账号，你账号里就能看到此项目的克隆项目，如下图所示

.. image:: /images/20.png

点击打开此项目，点击contribute，再点击open pull requesat，如下图所示。

.. image:: /images/21.png

最后点击create pull request，如下图所示，

.. image:: /images/22.png

按照如下图所示的填写表格 点击create pull request，你就能对此项目做出贡献了。当然你做出的贡献需要我的审核，等你擅长使用github等软件技术后，我就给你权限，这时你不需要等待我的审核就能给此项目做出贡献。

.. image:: /images/23.png

如果想要添加新的网页或者删除网页，只需添加或删掉对应的rst文件并在index.rst文件中.. toctree::的下面添加或删除相应rst文件名称。

非常感谢大家对此项目的支持，如果有任何问题可以联系我。我推荐使用github的isuues来提出问题，大家也可以帮你解决问题，我也会用我的第一时间去回答你的问题。

如果想要进一步学习相关技术软件，请阅读以下文章，教程视频。
关于git：
关于vs code:
关于sphinx：https://www.sphinx-doc.org/en/master/index.html。
关于rst：