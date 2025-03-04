# LFS Automated Building

自动化构建LFS。

An English version of README will be provided later on. 

## 构想

虽然LFS中并不包含一个包管理器，但是为了更加有条理地管理包，我还是（准备）设计了一个想法简单的包管理器——[`lpm`](https://github.com/Ytdpl/lpm)。经由lpm管理的构建，加上按照[LFS Book](https://linuxfromscratch.org/lfs/)中的描述来指定构建顺序和构建间过程，辅以引导，以达到自动化的效果。

在上述构想之上，我还有另一个想法：把LFS Book本身做成一个脚本。脚本会将LFS Book中的内容打印在终端上供阅读，阅读完毕后才能进行下一步，同时所有的代码都是已经编写好的，用户只需要一直按Enter（或者在阅读时用一些翻页按键，以及部分自定义选项的选择）就可以阅读所有他们应当知晓的内容并完整地完成新系统的构建。

不过设计lpm的想法和上述的想法是同时产生的。我又希望借lpm之类的包管理器来使得这部分开发更简洁，所以这个仓库现在只是记录想法，先去开发lpm了（逃