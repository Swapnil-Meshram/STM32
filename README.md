# STM32H743ZI
Nucleo Dev Board Is being used for this Testing.
HAL_GPIO_WritePin(GPIOB, GPIO_PIN_0, 1); : __asm volatile ("LDR r4, =0x58020400\n" "MOV r1, #(1UL<<0)\n" "STR r1, [r4, #0x18]\n");
HAL_GPIO_WritePin(GPIOB, GPIO_PIN_0, 0); : __asm volatile ("LDR r4, =0x58020400\n" "MOV r1, #(1UL<<16)\n" "STR r1, [r4, #0x18]\n");
