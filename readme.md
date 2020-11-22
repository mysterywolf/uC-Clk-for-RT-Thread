# uC/Clk for RT-Thread

https://github.com/SiliconLabs/uC-Clk

µC/Clk is a module that implements a Year 2000 compliant clock/calendar module. The clock/calendar module offers the following features:

* Maintains time in seconds starting from 2000/01/01 (January 1st, 2000) at 00:00:00 UTC until 2134/12/31 (December 31st, 2134) 23:59:59 UTC; but supports conversions to/from two other timestamps:

  * NTP (Network Time Protocol) timestamps, starting from 1900/01/01 (January 1st, 1900) at 00:00:00 UTC until 2034/12/31 (December 31st, 2034) 23:59:59 UTC;

  * Unix timestamps, starting from 1970/01/01 (January 1st, 1970) at 00:00:00 UTC until 2104/12/31 (December 31st, 2104) 23:59:59 UTC.

* Allows your application to obtain timestamps to mark the occurrence of events. A µC/Clk timestamp is a copy of its internal timestamp.

* Allows your application to get the current date and time into a structured data type named CLK_DATE_TIME containing Year, Month, Day, Day-of-Year, Day-of-Week, Hour, Minute, Second, and Timezone Offset. Can convert timestamps to dates/times or vice versa.

* Allows your application to get and set the clock date/time using any of the supported timestamps or a CLK_DATE_TIME structure and allows conversion to/from all supported timestamps and the CLK_DATE_TIME structure.



## 配置文件 `clk_cfg.h`



## 依赖项

本软件包会自动开启以下软件包作为依赖项，用户无需介入：

- [RT-Thread的uCOS-III兼容层软件包](https://github.com/mysterywolf/RT-Thread-wrapper-of-uCOS-III) (系统会自动初始化兼容层)



#### For the complete documentation, visit https://doc.micrium.com/pages/viewpage.action?pageId=10753188
