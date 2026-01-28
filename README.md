# WatermarkForJYN
为WzserJYNX准备的java版数据包水印

<img width="400" height="71" alt="屏幕截图 2026-01-28 111053" src="https://github.com/user-attachments/assets/733b9a06-6b82-48ab-8124-c78964975ae6" />

这是可以在actionbar上显示水印的java版数据包，会一直显示，可以作为视频水印。其中的[tick.mcfunction](https://github.com/gdxuwjwg/WatermarkForJYN/blob/main/data/watermark/function/tick.mcfunction)文本显示部分可被修改。

例如`title @a actionbar {"text":"Example"}`其中的`Example`可被修改。默认的文本是`bilibili@WzserJYNX 严禁转载`，显示效果如图

<img width="539" height="230" alt="屏幕截图 2026-01-28 111250" src="https://github.com/user-attachments/assets/e1c485fe-6a18-4596-b337-e6756497032a" />

# pack.mcmeta
该文件是JSON文件，其中`description`是数据包的描述，可被修改

支持版本：supported_formats第一个数是最小支持版本，**第二个数是最大支持版本**；min_format是最小支持版本，**max_format是最大支持版本**。两者都是数据包版本(可在[zh.minecraft.wiki](https://zh.minecraft.wiki)查到)，应随快照版本更新而改变`最大支持版本`

# 下载
只需在[Releases](https://github.com/gdxuwjwg/WatermarkForJYN/releases)下载最新版本，版本号会随着数据包版本而变化，里面会说明是为哪个版本及其以前的版本准备的
