hcSpriteCuter
=============

a nodejs cut sprite images into single image

在学习和研究别人程序的过程中，我们需要从一个由多张小图合并而成的雪碧图中抠出其中一张或者几张图片，传统的做法是用ps直接进行抠图。
hcSpriteCuter是一个用nodejs写的一个雪碧图拆分工具。
demo
架设我有一张图片：
<img src="https://raw.githubusercontent.com/luyongfugx/hcSpriteCuter/master/copte.png"\>
运行：
node hcSpriteCuter.js copte.png 

则程序会在export目录下将copte.png切成一下多个图片：
<img src="https://raw.githubusercontent.com/luyongfugx/hcSpriteCuter/master/export/copte/copte0.png"\>
