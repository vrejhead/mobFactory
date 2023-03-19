# mobFactory
basic stats and random stuff for mob factory demo


Assemblers
---
It starts with the assembler visually intaking items, which renders them uninteractable, which means you can't pick them up. After the item is moved to the center of the assembler, the assembler waits for a timer of 75 frames(1.25s) to count down, then add said item into its inventory, and the 75 frames timer is reset. When an assembler has all the necessary materials, it lights its outer ring then fades, and after 75 frames(again), it spawns the item.

 Spawners
 ---
They wait 10 seconds and 10 frames, then spawn the first enemy, the second, third, and fourth enemy spawn 45(or 46 due to what i assume frame issues) frames apart, and repeat.
