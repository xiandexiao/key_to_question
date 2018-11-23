# Sass安装

> 安装Ruby

**下载地址：** [Ruby](http://rubyinstaller.org/downloads)
> Ruby cmd下执行以下命令

`gem install sass`

-------------------

## 若安装不成功

1. 移动默认的源

  `gem sources --remove https://rubygems.org/`

2. 指定淘宝的源

  `gem sources -a https://ruby.taobao.org/`

3. 查看指定的源是不是淘宝源

  `gem sources -l`

> 返回以下结果

  `*** CURRENT SOURCES ***
https://ruby.taobao.org`

4. 确保只有 ruby.taobao.org。如果无误之后，执行下面的命令

  `gem install sass`
