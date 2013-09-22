Ansible role to install the Oracle JDK/JRE
==========================================

Description
-----------

By default Debian and Ubuntu only provide OpenJDK, but sometimes you may want to use the official Oracle JRE/JDK.

This uses the Ubuntu PPA maintained by [Webupd8](http://www.webupd8.org/). It works without problems on Debian too.

How to use
----------

Override the list *java_versions* wherever you want to choose what to install.

The valid values are:

  * java7 (Oracle JRE 7)
  * java8 (Oracle JRE 8 Preview)
  * jdk7 (Oracle JDK 7)
  * jdk8 (Oracle JDK 8 Preview)
