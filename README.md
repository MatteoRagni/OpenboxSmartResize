OpenboxSmartResize
==================

Smart resize and move keybinds for OpenBox

This project is composed by only a snipplet of xml that can be used in your ``$HOME/.config/openbox/rc.xml`` to get:

  * resize
  * move
  * smart resize and move in grid
  
Here keybinding are explained:

### Move ######

To move windows you must use ``Alt`` modifier
```
Alt + KP_N

 ↖  ↑  ↗
  7 8 9 
← 4 5 6 → 
  1 2 3
 ↙  ↓  ↘  

```

### Resize ######

To get windows resized you must use ``Ctrl`` modifier to expand (``Shift + Ctrl`` modifier to compress)
```
Ctrl + KP_N

 ⇖  ⇑  ⇗
  7 8 9 
⇐ 4 5 6 ⇒
  1 2 3
 ⇙  ⇓  ⇘
 
Ctrl + Shift + KP_N

 ⇘  ⇓  ⇙
  7 8 9 
⇒ 4 5 6 ⇐
  1 2 3
 ⇗  ⇑  ⇖

```

### Smart move and resize ######

To use "Smart move and resize" you must use ``Ctrl + Alt`` modifier

```
Ctrl + Alt +

╔══════════════════════╗
║┌──────────┬─────────┐║
║│KP_4      │KP_6     │║
║│          │         │║
║│          │         │║
║│          │         │║
║│          │         │║
║└──────────┴─────────┘║
╚══════════════════════╝

╔══════════════════════╗
║┌────────────────────┐║
║│KP_8                │║
║│                    │║
║├────────────────────┤║
║│KP_2                │║
║│                    │║
║└────────────────────┘║
╚══════════════════════╝

╔══════════════════════╗
║┌────────────────────┐║
║│KP_5*               │║
║│      ┌──────┐      │║
║│      │KP_5* │      │║
║│      └──────┘      │║
║│                    │║
║└────────────────────┘║
╚══════════════════════╝

╔══════════════════════╗
║┌──────────┬─────────┐║
║│KP_7      │KP_9     │║
║│          │         │║
║├──────────┼─────────┤║
║│KP_1      │KP_3     │║
║│          │         │║
║└──────────┴─────────┘║
╚══════════════════════╝

═ Screen 
─ Window
* Toggle
```
 and ``Ctrl + Alt + Shift`` modifier
 
```
Ctrl + Alt + Shift +

╔══════════════════════╗
║┌──────┬──────┬──────┐║
║│KP_7  │KP_8  │KP_9  │║
║├──────┼──────┼──────┤║
║│KP_4  │KP_5* │KP_6  │║
║├──────┼──────┼──────┤║
║│KP_1  │KP_2  │KP_3  │║
║└──────┴──────┴──────┘║
╚══════════════════════╝

╔══════════════════════╗
║┌────────────────────┐║
║│KP_5*               │║
║│      ┌──────┐      │║
║│      │KP_5* │      │║
║│      └──────┘      │║
║│                    │║
║└────────────────────┘║
╚══════════════════════╝

═ Screen 
─ Window
* Toggle
```
