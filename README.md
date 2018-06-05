# LJRunLoopWork
利用CoreFoundation实现监听runloop进入等待的时机，将耗时的操作加入进入等待之前，即将UI的加载延后
这样做可以有效的减少因为刷新大量UI造成的卡顿。但是这样做也会造成在滑动的时候UI界面是不加载的，只有在交互结束后才会进行加载。
我记得还有几个三方库是异步绘制的，这几个也可以有效的减少卡顿
