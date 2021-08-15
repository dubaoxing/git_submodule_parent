git clone包含子模块的代码仓库

正常的使用git clone命令，然后再使用 git submodule init 和git submodule update来获取子模块
git clone projectA.git
cd projectA
git submodule init
git submodule update

或者加上递归参数，下载所有包含的子模块
git clone --recursive projectA.git