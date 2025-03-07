## LumProject

### 什么是LumProject？

LumProject最终将会是一系列以Lumen命名的开源项目。

目前，LumProject将计划包含以下项目：

- **Lumen-OS**
- **Lumen-IO**
- **Lumen-LVGLpp**

目前仅仅考虑在瑞芯微平台上的可行性，主要以Lumen-OS为主。预计在未来5年内完成。



### 什么是Lumen-OS？

Lumen-OS最终将是一套基于Linux的开源操作系统。Lumen-OS将会给予那些性能足够运行Linux但是没有能力运行Android的嵌入式设备以一套便捷、易用的图形化操作系统，以便开发者能够更加轻松、以更低成本开发更加复杂的智能穿戴设备、智能家居设备、工业控制设备等等嵌入式Linux适用的场景。



### 什么是Lumen-IO？

Lumen-IO最终将是一套由C++封装的底层接口。LVGL-IO向下对接libgpiod，向上提供芯片的各类IO，包括GPIO、PWM、DAC等单引脚IO直接封装，也包括UART、I2C、SPI等一系列组合引脚IO封装，计划上最终可以包括视频、显示、摄像头等复杂接口的抽象封装，最终为开发者提供一个简便的、上层的开发环境。



### 什么是Lumen-LVGLpp？

Lumen-LVGLpp最终将是一套由C++封装的LVGL。Lumen-LVGLpp将结合Lumen-OS的特性进行封装，向下对接LVGL，向上提供面向对象版本的LVGL对象。

由于要结合Lumen-OS，因此Lumen-LVGLpp可能是一套只适用于Lumen-OS上应用开发的LVGL，更好的一种可能是使得LVGL成为Lumen-LVGLpp的一个子集，但总的来说Lumen-LVGLpp目前不会兼顾非Lumen-OS的开发。

