# NumberImageView
消息图标、图片消息图标
# 预览
![效果](./ic_preview.png)
# 资源
|名字|资源|
|-|-|
|AAR|[number_image_view.aar](https://github.com/RelinRan/NumberImageView/blob/master/number_image_view.aar)|
|Gitee|[NumberImageView](https://gitee.com/relin/NumberImageView)|
|GitHub |[NumberImageView](https://github.com/RelinRan/NumberImageView)|
# Maven
1.build.grade | setting.grade
```
repositories {
	...
	maven { url 'https://jitpack.io' }
}
```
2./app/build.grade
```
dependencies {
	implementation 'com.github.RelinRan:NumberImageView:2022.6.20.1'
}
```
# xml
~~~
    <com.androidx.widget.NumberImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:numberText="10"
        android:paddingHorizontal="10dp"
        android:src="@mipmap/ic_activity_03"/>
~~~
# attrs.xml
~~~
    <attr name="numbersTextSize" format="dimension|reference" />
    <attr name="numberMarginTop" format="dimension|reference" />
    <attr name="numberMarginRight" format="dimension|reference" />
    <attr name="numberText" format="string|reference" />
    <attr name="numberTextColor" format="color|reference" />
    <attr name="numberTextSize" format="dimension|reference" />
    <attr name="numberSolidColor" format="color|reference" />
    <declare-styleable name="NumberImageView">
        <attr name="numberMarginTop" />
        <attr name="numberMarginRight" />
        <attr name="numberSolidColor" />
        <attr name="numberTextColor" />
        <attr name="numberTextSize" />
        <attr name="numberText" />
    </declare-styleable>
~~~
