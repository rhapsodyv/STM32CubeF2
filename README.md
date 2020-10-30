# STM32CubeF2 MCU Firmware Package

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform (this repo), delivered for each series (such as the STM32CubeF2 for the STM32F2 series).
   * The CMSIS modules (core and device) corresponding to the ARM-tm core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series
   * A consistent set of middlewares components such as RTOS, USB, FatFS, LwIP, Graphics ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

The **STM32CubeF2 MCU Package** projects are directly running on the STM32F2 series boards. You can find in each Projects/*Board name* directories a set of software projects (Applications/Demonstration/Examples)

In this FW Package, the modules **Middlewares/ST/STemWin** and **Middlewares/ST/STM32_Audio** are not directly accessible. They must be downloaded from a ST server, the respective URL are available in a readme.txt file inside each module.

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/STM32CubeF2/blob/master/Release_Notes.html).

## Boards available
  * STM32F2
    * [STM3220G-EVAL](https://www.st.com/en/evaluation-tools/stm3220g-eval.html)
    * [STM3221G-EVAL](https://www.st.com/en/evaluation-tools/stm3221g-eval.html)
    * [NUCLEO-F207ZG](https://www.st.com/en/evaluation-tools/nucleo-f207zg.html)

## Troubleshooting

**Caution** : The **Issues** requests are strictly limited to submit problems or suggestions related to the software delivered in this repo 

**For any other question** related to the STM32F2 product, the hardware performance, the hardware characteristics, the tools, the environment, you can submit a topic on the [ST Community/STM32 MCUs forum](https://community.st.com/s/group/0F90X000000AXsASAW/stm32-mcus)