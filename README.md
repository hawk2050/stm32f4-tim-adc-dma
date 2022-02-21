# stm32f4-tim-adc-dma

This is a simple example project to show a timer triggered multichannel ADC conversion (every 25ms), followed by a DMA transfer of the converted samples. It seems to work when you use STM32CubeIDE to "Run as" rather than "Debug as". For some reason if you attempt to use the debugger then the application doesn't run correctly. This was built for the STM32F407VG on the STM32F4-Discovery board.
