Typecho Blogging Platform
=========================

Typecho is a PHP Blogging Platform. Simple and Powerful.

#### Homepage
http://typecho.org/

#### Documents
http://docs.typecho.org/

#### Community
http://forum.typecho.org/

#### Download
http://typecho.org/download


#### 设置SCSS预处理

Phpstorm 设置方法

Settings Tool > File Watchers >

添加 Compass SCSS

```
Program    C:\Ruby22-x64\bin\compass.bat
Arguments    compile
Working directory    $ProjectFileDir$
```
其他为空

Settings Tool > External Tools > Edit tool

```
Name    Compass compile manual
Program    C:\Ruby22-x64\bin\compass.bat
Parameters    compile
Working directory    $ProjectFileDir$
```

Setting > Language & Framework > Compass

Enable Compass Support

```
Compass executable file    C:\Ruby22-x64\bin\compass.bat
Config path    D:\workspaces\PhpstormProjects\typecho\config.rb
```