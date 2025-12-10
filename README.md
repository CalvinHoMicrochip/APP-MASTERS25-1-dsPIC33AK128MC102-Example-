# APP-MASTERS25-1-dsPIC33AK128MC102-Example
APP-MASTERS25-1 出廠測試程式 for dsPIC33AK128MC102

  *  dsPIC33AK128MC102 是另外一個裝置於 APP-MASTERS25-1 的 Microchip MCU
  *  dsPIC33AK 系列為 Microchip 新推出的 32-bit DSC，重要的諸元如下
      *  FPU:Yes
      *  CPU Speed Max MHz (megahertz)
      *  Multiple Flash Panels:No
      *  Secure Boot with Flash OTP
      *  6 Direct Memory Access (DMA) Channels
  *  本範例程式主要展現如何使用 MPLAB X IDE，MCC Melody 來完成一個 dsPIC33AK128MC102 的入門程式，控制以下的 MCU 資源
      *  UART 、ADC、I2C
      *  定時讀取 ADC 的數位輸出，將結果輸出至 OLED (使用 I2C 控制) 以及 UART
  
