# 🖨️ ft_printf

Recreation of the famous `printf()` function from the C standard library as part of the Milestone 01 projects at 42 common core.

<img align="right" src="https://github.com/danielleseragioli/42_duck_badges/blob/main/badges/printf_pin.png" width="180">

This project helped me deepen my understanding of:

- Variadic functions (`va_list`, `va_start`, `va_arg`, `va_end`)
- Data formatting and conversion
- Low-level output handling with `write()`
- Modular and reusable code design
- Memory management and edge cases
- Reproducing standard library behavior

---

<table>
  <tr>
    <td width="70%">

## 🚀 Supported Format Specifiers

| Specifier | Description |
|---|---|
| `%c` | Character |
| `%s` | String |
| `%p` | Pointer address |
| `%d` / `%i` | Signed integer |
| `%u` | Unsigned integer |
| `%x` / `%X` | Hexadecimal |
| `%%` | Percent sign |

   </td>
   <td width="30%" align="center">
      <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWU2dmNsb3h2ZTNnYnV4aWh4dHdzbGsxdDJiYjE5dzZ0eTNybGY0dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/S60FmbC13E0tlsNp3N/giphy.gif" width="220">
   </td>
  </tr>
</table>

---

## 💻 Usage

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello %s! Number: %d Hex: %x\n", "world", 42, 42);
    return (0);
}
```

---

## 🛠️ Compilation

```bash
make
```

---

## 📚 What I Learned

- Handling variadic arguments in C
- Converting numbers between bases
- Implementing formatted output functions
- Managing edge cases and return values
- Writing cleaner and modular C code

---

✅ Project completed successfully as part of my 42 journey.
