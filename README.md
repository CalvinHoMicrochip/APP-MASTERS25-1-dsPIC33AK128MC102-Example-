# APP-MASTERS25-1-dsPIC33AK128MC102-Example
APP-MASTERS25-1 出廠測試程式 for dsPIC33AK128MC102

  *  dsPIC33AK128MC102 是另外一個裝置於 APP-MASTERS25-1 的 Microchip MCU
  *  dsPIC33AK 系列為 Microchip 新推出的 32-bit DSC，重要的諸元如下
      *  FPU : 浮點運算單元，支援單精度及雙精度運算
      *  CPU Speed Max. 200 MHz 
      *  Secure Boot with Flash OTP
      *  6 Direct Memory Access (DMA) Channels
  *  本範例程式主要展現如何使用 MPLAB X IDE，MCC Melody 來完成一個 dsPIC33AK128MC102 的入門程式，控制以下的 MCU 資源
      *  UART 、ADC、I2C
      *  定時讀取 ADC 的數位輸出，將結果輸出至 OLED (使用 I2C 控制) 以及 UART

# 本範例程式在 MCC Melody 所需要的 Device Resource 如下圖所示
   <img width="600" height="395" alt="image" src="https://github.com/user-attachments/assets/35ae03f6-d3a9-4ada-8896-51867a8ce50c" />

# 本範例程式的執行結果如下圖所示
  * 燒錄程式以及 CPU 選擇的設定
      * 將 PICkit-5 or PICkit-BASIC or MPLAB SNAP 連接於 P3
      * Jumper P9, P10, P11, P12, P12A 要設置於將 dsPIC33AK Enable 的設定 (用 P10 來 Enable dsPIC33AK)
      * USB2 Connector (OLED 下方) 可以連接至電腦，使用 115200,N,8,1 的通信格式收送 UART 的通信數據。
    
  <img width="480" height="343" alt="image" src="https://github.com/user-attachments/assets/3297f130-9a4c-48c5-a891-70d0a1aa64e6" />

  
