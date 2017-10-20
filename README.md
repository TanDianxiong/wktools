* wktools个人开发环境工具集
* 预装工具:`git`
* 首先把库clone下来:`git clone https://github.com/TanDianxiong/wktools ~/wktools` 

## vim配置方法
1. `cd ~` 
2. `ln -s wktools/.vimrc .vimrc`
3. `ln -s wktools/vim .vim`
4. `cd ~/wktools && git submodule init && git submodule update`
5. 打开vim,命令模式执行`PluginInstall`

## git相关配置
* 颜色: `git config --global color.ui true`
