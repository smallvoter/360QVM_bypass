# 360QVM_bypass
* 随机文件名
* 随机文件信息
* 加上sigthief签名窃取功能

`python3 icon-exe.py -h`
```
Author:pant0m & Hyyrent 修改版 v 1.3

usage: icon-exe.py [-h] -f INPUT_ICON_FILE [-n NUM_ICONS] [-maxc MAX_COLOR_CHANGE] -i INPUTFILE -s SIGTHIEF

默认会生成带签名和不带签名的文件。

options:
  -h, --help            show this help message and exit
  -f INPUT_ICON_FILE, --file INPUT_ICON_FILE
                        输入ICO文件。
  -n NUM_ICONS, --number NUM_ICONS
                        要生成的图标数量。
  -maxc MAX_COLOR_CHANGE, --maxcolorchange MAX_COLOR_CHANGE
                        最大颜色变化范围。
  -i INPUTFILE, --inputfile INPUTFILE
                        输入目标PE文件。
  -s SIGTHIEF, --sigthief SIGTHIEF
                        输入要伪造签名exe路径。(必填)
```

项目来源：https://github.com/S9MF/my_script_tools

