## windows 本地调试教程(有问题)

按照这个[教程](https://www.jianshu.com/p/f500675895e9) 先安装一下 jeklly

1. 其中的 [这个](https://cn.yizeng.me/2013/05/10/setup-jekyll-on-windows/#install-ruby) 安装一下 ruby, 
   `ruby -v`
    看一下效果
   
2. 然后**在本文件夹下** `gem install jekyll bundler`，`jekyll -v, bundle -v`

3. 进入本文件夹，参考[这里](https://www.jianshu.com/p/20ea66b43e21) 的方法二，
   **在本文件夹下** `bundle install`
   
4. `bundler init`, `gem "jekyll", "~> 4.3.1"`


## MacOS 安装教程

参考这个 [github](https://github.com/qiubaiying/qiubaiying.github.io) 学习使用教程，
其中 jelly 参考 [这里](http://jekyllcn.com/).

1. 先安装 `brew` 来安装 `brew install ruby`
2. 进入到本文件夹下，然后 `gem install jekyll bundler` 安装, `jekyll -v, bundle -v` 检查
3. `bundle init` 初始化一下
4. `bundle add jekyll` 添加一下
5. `bundle install` 安装一下
6. `bundle exec jekyll serve`，最后 `http://127.0.0.1:4000/`

## other tricks

- 封面图如果导致上面文字不够显眼，可以ppt遮挡33%的浅黑色遮挡，降低暗度