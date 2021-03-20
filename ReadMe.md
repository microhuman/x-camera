### 以前是XP的版本，修改了一下，支持WIN10，需要用VS2015编译，DDK (现在叫WDK）
## 用dShow Filter推数据进去，数据需要RGB24格式，推什么内容显示什么。 用ffmpeg推电影很爽。

## 核心逻辑在 capmain.c capmain.h capvideo.c 
## UCHAR		m_framebuffer[MAXFRAME][FRAMESIZE];
## VideoQueueAdd RtlCopyMemory(m_framebuffer[0], data, FRAMESIZE);

### 有问题可以联系 
