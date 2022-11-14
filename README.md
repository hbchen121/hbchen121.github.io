本项目 fork 自[klovien](https://github.com/klovien/klovien.github.io)，现为[hbchen121](https://hbchen121.github.io/)个人主页。


## windows 本地调试教程(有问题)

按照这个[教程](https://www.jianshu.com/p/f500675895e9) 先安装一下 jeklly

1. 其中的 [这个](https://cn.yizeng.me/2013/05/10/setup-jekyll-on-windows/#install-ruby) 安装一下 ruby, 
   `ruby -v`
    看一下效果
   
2. 然后**在本文件夹下** `gem install jekyll bundler`，`jekyll -v, bundle -v`

3. 进入本文件夹，参考[这里](https://www.jianshu.com/p/20ea66b43e21) 的方法二，
   **在本文件夹下** `bundle install`
   
4. `bundler init`, `gem "jekyll", "~> 4.3.1"`


## MacOS 安装教程(已解决)

参考这个 [github](https://github.com/qiubaiying/qiubaiying.github.io) 学习使用教程，
其中 jelly 参考 [这里](http://jekyllcn.com/).

1. 先安装 `brew` 来安装 `brew install ruby`
2. 进入到本文件夹下，然后 `gem install jekyll bundler` 安装, `jekyll -v, bundle -v` 检查
3. `bundle init` 初始化一下
4. `bundle add jekyll` 添加一下
5. `bundle install` 安装一下
6. `bundle exec jekyll serve`，最后 `http://127.0.0.1:4000/`

## other tricks

- 封面图如果导致上面文字不够显眼，可以ppt遮挡33%的浅黑色遮挡，降低暗度，例如 `files/template_of_imgs`

### 致谢

1. 这个模板是从这里 [klovien](https://github.com/klovien/klovien.github.io) fork 的, 感谢作者klovien。
1. klovien的模板是从这里 [BY](https://github.com/qiubaiying/qiubaiying.github.io) fork 的, 感谢作者BY。
2. BY的模板应该是从这个模板 [Hux](https://github.com/Huxpro/huxpro.github.io) fork 的, 也一起感谢一下。
3. 感谢 Jekyll、Github Pages 和 Bootstrap!

### License

遵循 MIT 许可证。有关详细,请参阅 [LICENSE](https://github.com/klovien/klovien.github.io/blob/master/LICENSE)。
