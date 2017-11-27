# android-listview-
android listview  去除拖动到顶部和底部时阴影效果

解释一下listview用到的各个属性
去除拖动时默认的带颜色的背景：
android:cacheColorHint="#00000000"
去除ListView滑到顶部和底部时边缘的黑色阴影：
android:fadingEdge="none"
去除下滑到底部，上拉时出现的带阴影颜色区域
android:overScrollMode="never"
