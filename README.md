# tools-website
自用网站
取颜色
```
https://photokit.com/colors/eyedropper/?lang=zh
```

```
data
|_ mask_png_dir  待转换的mask png
|  |_ 1.png
|  |_ 2.png
|  |_ ...
|  |_ 1000.png
|_ target_txt_dir  转换后的txt
|  |_ 1.txt
|  |_ ...
.......
```
png 内容： 0 背景  1~n 为对应的类别的实例掩码

代码逻辑比较冗余，凑活用吧。本人用的yolov8测的可以用。
