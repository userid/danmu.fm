# danmu.fm 

这是一个用来获取斗鱼TV指定主播的弹幕的命令行小工具.

使用参见
http://www.jianshu.com/p/2e0d14978ae9

原理参见
http://www.jianshu.com/p/ef0225b6bb0e

## 如何使用


如果你是MacOSX的用户,你只需要
```bash
brew install mplayer
pip3 install danmu.fm
# danmu.fm -q 1 -v 1 [url]
# 比如
danmu.fm -q 2 -v 1 http://www.douyutv.com/16789
# -q 参数 0为不调用mplayer进行播放,1为使用mplayer进行普清视频的播放,2为使用mplayer进行高清视频的播放,3为使用mplayer进行超清视频的播放
```

如果你是Ubuntu 用户,你只需要

```bash
pip3 install danmu.fm
# danmu.fm  -v 1 [url]
# 比如
danmu.fm  -v 1 http://www.douyutv.com/16789
#ubuntu上mplayer播放器貌似有些问题,弹幕部分应该没有问题.
```

## 感谢

往事如风
douban.fm (Python版本)

## License

MIT


