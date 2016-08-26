

CSDN: http://blog.csdn.net/zxt0601

包含且不仅包含以下功能

1 侧滑拉出菜单。

2 点击除了这个item的其他位置，菜单关闭。

3 侧滑过程中，不许父控件上下滑动。

4 多指同时滑动，屏蔽后触摸的几根手指。

5 不会同时展开两个侧滑菜单。

6 侧滑菜单时 拦截了长按事件。


需要效果一 ：直接拷贝 view包下的 CstSwipeDelMenu 

需要效果二 ：直接拷贝 view包下的 CstIOSSwipeDelMenu 


`<mcxtzhang.swipedelmenu.view.CstIOSSwipeDelMenu xmlns:android="http://schemas.android.com/apk/res/android"`
` android:layout_width="match_parent"`
` android:layout_height="wrap_content"`
` android:clickable="true">`

    <TextView
        android:id="@+id/tv"
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:gravity="center"
        android:text="试试看" />

    <Button
        android:id="@+id/btnDelete"
        android:layout_width="60dp"
        android:layout_height="match_parent"
        android:background="@color/red_ff4a57"
        android:text="删除" />
`</mcxtzhang.swipedelmenu.view.CstIOSSwipeDelMenu>`

