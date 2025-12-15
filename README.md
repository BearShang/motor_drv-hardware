1. 加一路ldo
2. 换MOS驱动芯片
3. 预留反向导通二极管
4. 把TMR1CH4预留出来，配套的换一些引脚
	添加了TMR1CH4在PA11;
	TMR1CH1N换到了PB7；
	LED_R换到了PA1，LED_G换到了PB10；
	UART_TX换到了PA2，UART_RX换到了PA3。相应的从uart1换到了uart2