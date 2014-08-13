# grunt-init


http://www.gruntjs.org/docs/project-scaffolding.html



## install 

grunt-init依赖

- nodejs
- git

安装npm模块：grunt-init

	npm install -g grunt-init
	
## usages

安装完依赖后，执行下面的shell，就可以把grunt-init支持的插件都通过git clone下来了


	./install_grunt_init_plugins.sh 

## 插件说明

### 创建一个包含QUnit单元测试的jQuery插件

	git clone https://github.com/gruntjs/grunt-init-jquery.git ~/.grunt-init/jquery

### 创建一个包含Nodeunit单元测试的commonjs模块

	git clone https://github.com/gruntjs/grunt-init-commonjs ~/.grunt-init/commonjs

### 创建一个基本的Gruntfile

	git clone https://github.com/gruntjs/grunt-init-gruntfile ~/.grunt-init/gruntfile

### 创建一个包含Nodeunit单元测试的Grunt插件
 
	git clone https://github.com/gruntjs/grunt-init-gruntplugin ~/.grunt-init/gruntplugin

### 创建一个包含Nodeunit单元测试的Node.js模块

	git clone https://github.com/gruntjs/grunt-init-node ~/.grunt-init/node
	

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## 版本历史

- v0.1.0 初始化版本 


## 欢迎fork和反馈

在issue提问或邮件shiren1118@126.com

## License

this gem is released under the [MIT License](http://www.opensource.org/licenses/MIT).
