# HRTF 3D 音效（MATLAB）

用 [CIPIC HRTF 数据库](http://interface.cipic.ucdavis.edu/sound/hrtf.html) 的 KEMAR（21 号）头部数据，把单声道音频做成 3D 环绕音效。

- `HRTF/main.m`：入口，运行它就能听到效果
- `HRTF/load_CIPIC_HRIR.m`：读取 CIPIC 的 HRIR 数据
- `HRTF/audio_with_brir.m`：把音频和 HRIR 卷积
- `HRTF/doc/`：CIPIC 数据库的官方说明文档

算法讲解（中文）：

- [HRTF 3D 音效的实现原理](https://thueringerbratwurst.com/hrtf/)
- [HRTF 的 MATLAB 代码说明](https://thueringerbratwurst.com/hrtf_matlab/)

代码可以自由使用，但请勿用于商业目的。

---

Turns mono audio into 3D sound with the KEMAR (subject 21) data of the CIPIC HRTF database. Run `HRTF/main.m`. Free to use, but not for commercial purposes. Write-ups (in Chinese) are linked above.

作者 / Author：[图林根的烤肠 · Thüringer Bratwurst](https://thueringerbratwurst.com)
