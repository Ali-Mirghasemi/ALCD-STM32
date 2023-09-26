# ALCD Library

This is a HD44780 ALCD library for STM32 series

## Usage

Init ALCD

```c
// For 16x2 ACD
ALCD_init(16, 2);
// For 20x1 ACD
ALCD_init(20, 1);
```

Set cursor

```c
ALCD
```

Print character

```c
// Print a character
ALCD_putChar('X');
```

Print string

```c
// Print a character
ALCD_puts("Hello World");
```


