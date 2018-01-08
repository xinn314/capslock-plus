## 原作者：[capslock-plus](https://github.com/wo52616111/capslock-plus)

很感谢作者能将软件开源，当然软件并不是免费的，请自行根据使用时间和频率向[原作者](http://cjkis.me/payment/)付费，金额不限。

软件的运行方法可以查看 [capslock-plus](https://github.com/wo52616111/capslock-plus) ，我就不重复了。根据自己的使用习惯做了一些改动，改动的方法都很简单粗暴，所以没有Pull回原仓库。

1. **修改有道翻译函数**

   换成了新版的有道 API，加了记录查询过的单词的功能，方便导入背单词的软件。翻译功能应该是用的最频繁的了，翻译软件有挺多，但最方便快捷的还是这个。

2. **禁止调用 IE 引擎**

   由于默认浏览器锁定了非 IE 内核，软件启动的时候总会报个错误，JavaScript 相关的功能平时几乎不用，所以暂时禁止了。

3. **修改 `PrintScreen` 键为 QQ 截图的快捷键**

   其实这个没怎么用到，还是习惯直接 `Ctrl + Alt + A` ，考虑过把 QQ 截图的提取版放进软件调用的时候直接运行，但不太放心提取版的安全，而且都是几百 k 的比工具本身还大就放弃了。

4. **增加记事本快捷键**

   习惯把一些信息保存到记事本，所有将  `CapsLock + ~` 改为打开特定的记事本，同时如果活动窗口是笔记本的时候可以通过 `Esc` 或 `Ctrl + W` 快速的关闭。

5. **增加鼠标快捷操作**

   - 点击屏幕左上角开/关静音
   - 点击屏幕上边缘部分区域播放/暂停音乐（原本是上边缘都生效，但切换浏览器标签的时候容易误触发就改成偏右侧的一部分区域）
   - 鼠标位于屏幕上边缘滚轮调节音量
   - 鼠标位于任务栏滚轮切换 Win10 虚拟桌面，个人习惯把音乐播放器放到另一个虚拟桌面
