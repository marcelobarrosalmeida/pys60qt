pys60qt is an simulator for pys60 program written in pyqt/pyside. pys60qt recreates all pys60 interfaces, allowing execution of pys60 applications in PCs or other environments supported by Qt. Missing hardware, like GPS or SMS support are simulated in PCs, keeping their original interfaces and creating dummy values. The idea is to speed up (even more) the creation of pys60 applications since several test cycles in target device may be skipped. As an additional benefit, it will be possible to port pys60 applications for new devices like N900, just using Qt and pyqt/pyside.

The project is in pre-alpha state and at this moment appuifw.py is under construction. See [ProjectState](ProjectState.md) for detailed information.

![http://pys60qt.googlecode.com/files/pys60qt_alpha.png](http://pys60qt.googlecode.com/files/pys60qt_alpha.png)

You can find similar projects written in [GTK](http://code.google.com/p/pys60emulator/) and [WxWidgets](http://sourceforge.net/projects/pys60-compat/).