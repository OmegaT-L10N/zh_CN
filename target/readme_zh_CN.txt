@TRANSLATION_NOTICE@


What is OmegaT?
===============

OmegaT 是自由且开源的多平台计算机辅助翻译工具，具有模糊匹配、翻译记忆、
关键字查找、词汇表、以及为更新后的项目自动套用翻译等特性。



许可信息
=====================

OmegaT is available under the terms of the GNU General Public License as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. You can find the text of the license in
/docs/OmegaT-license.txt.

OmegaT uses a number of librairies. The license of each library is mentionned
in /lib/licenses/Licenses.txt.



安装 OmegaT 的先决条件
===================================

OmegaT 需要您的系统安装了 Java 运行环境（JRE）1.8 或者更高版本。

我们推荐使用包含 JRE 的 OmegaT 软件包，以避免选择、获取、与安装 JRE 的麻烦。



安装 OmegaT（Windows）
===========================

启动安装程序。



安装 OmegaT（Mac）
=======================

Unpack the OmegaT .zip archive to obtain a folder that contains a
documentation file and the OmegaT application. Move the folder to an
appropriate location such as the Applications folder.



安装 OmegaT（Linux）
=========================

Place the archive in any suitable folder and unpack it. OmegaT is then ready
to be launched.

You can however obtain a neater and more user-friendly installation by using
the installation script (linux-install.sh). To use this script, open a
terminal window (console), change folder to the folder containing OmegaT.jar
and the linux-install.sh script, and execute the script with ./linux-
install.sh.



安装 OmegaT（Solaris、FreeBSD、...）
=========================================

Place the archive in any suitable folder and unpack it. OmegaT is then ready
to be launched.



用 Java Web Start 安装 OmegaT（所有平台）
===========================================================

如果已在系统中安装了 Java，安装 OmegaT 的方法之一是使用 Java Web Start。

为此，需要下载以下文件并运行之：

   http://omegat.sourceforge.net/webstart/OmegaT.jnlp

It will install the correct environment for your computer and the application
itself on the first run. Later calls do not need to be online.



启动 OmegaT（Windows）
==========================

如果在安装过程中已经在桌面上创建了快捷方式，双击此快捷方式。

The install program can create shortcuts for you in the start menu, on the
desktop and in the quick launch area. You can also manually drag the file
OmegaT.exe to the start menu, the desktop or the quick launch area to link it
from there.

如果您在文件管理器（Windows 资源管理器）中能看到文件 OmegaT 但看不到
OmegaT.exe，请修改设置以显示文件扩展名。



启动 OmegaT（Mac）
======================

双击 OmegaT 应用程序。

You may drag the OmegaT application to your dock or to the tool bar of a
Finder window to be able to launch it from any location. You can also launch
it from the Spotlight search field.



启动 OmegaT（Linux）
========================

如果您用了 linux-install.sh 脚本，你应当可以这样启动 OmegaT：

  Alt+F2

然后：

  omegat

For a more user-friendly way of launching OmegaT, you can use the Kaptain
script provided (omegat.kaptn). To use this script you must first install
Kaptain. You can then launch the Kaptain launch script with:

  Alt+F2

然后：

  omegat.kaptn



从命令行启动 OmegaT（所有平台）
====================================================

启动 OmegaT 的命令是：

cd <OmegaT.jar 文件所在的文件夹>

<Java 可执行文件的路径和名称> -jar OmegaT.jar

(The Java executable file is the file java on Linux and java.exe on Windows.
If Java is installed at system level and is in the command path, the full path
need not be entered.)



贡献者
============

OmegaT 最初的工作由 Keith Godfrey 完成。

Aaron Madlon-Kay 是 OmegaT 的项目经理。

当前团队：
（按字母顺序）

  Vincent Bidaux (documentation manager)
  Marco Cevoli (Telegram community manager)
  Jean-Christophe Helary (Twitter community manager) 
  Kos Ivantsof (localisation manager)
  Concepción Martin (Facebook community manager)
  Briac Pilpré (webmaster)
  Lucie Vecerova (Facebook community manager)

对代码的贡献记录在 /docs/contributors.txt 中。

以前的贡献者包括：
（按字母顺序）

  Anthony Baldwin (localisation manager)
  Didier Briel (project manager)
  Alex Buloichik (lead developer)
  Sabine Cretella
  Dmitri Gabinski
  Jean-Christophe Helary (support group owner, localisation manager)
  Maxym Mykhalchuk (lead developper)
  Samuel Murray
  Henry Pijffers (release manager)
  Marc Prior (project co-ordinator, webmaster)
  Vito Smolej (documentation manager)
  and many, many more very helpful people

（如果您认为您对 OmegaT 项目做出了重大贡献但名字没有出现在列表中，
　请随时与我们联系。）



有用的链接
============

关于 OmegaT 的最新信息，请访问：

   http://www.omegat.org/

在 Yahoo 用户组可以获得（多语种）用户支持，无需订阅也可以对归档进行搜索：

   https://groups.yahoo.com/neo/groups/OmegaT/info

在 SourceForge 网站可以（用英语）提出改进建议与意见：

   https://sourceforge.net/p/omegat/feature-requests/

在 SourceForge 网站可以（用英语）报告 Bug：

   https://sourceforge.net/p/omegat/bugs/
