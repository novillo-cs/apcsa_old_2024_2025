---
title: CW 33 - Hanoi
due_date: 2025-01-17
---

## Tower of Hanoi

`Save your work here: .../APCSA_1/apcsa-assignments-YourUsername/classwork/33_hanoi/Hanoi.java`

### Mild

Write a function to move n rings from source rod to destination rod, print the moves of each ring. 
```
public static void hanoiMild(int n, char source_rod, char destination_rod, char aux_rod){
	YOUR CODE HERE
}
```

Output with 3 rings:
```
Move ring 1 from source A to destination C
Move ring 2 from source A to destination B
Move ring 1 from source C to destination B
Move ring 3 from source A to destination C
Move ring 1 from source B to destination A
Move ring 2 from source B to destination C
Move ring 1 from source A to destination C
```

### Medium

Write a function to move n rings from source rod to destination rod, print the moves of each ring, and the total number of moves. Check if your solution used the least possible number of moves.

```
public static int hanoiMedium(int n, char source_rod, char destination_rod, char aux_rod){
	YOUR CODE HERE
}
```

Output with 3 rings:

```
(Print moves as shown in previous method)
Total number of moves: 7
The total number of moves (7) is equal to 2^n - 1 (2^3 - 1)
```

### Spicy

Write a function to move n rings from source rod to destination rod, print the moves of each ring, and the list of rings on each rod after each move.

```
public static void hanoiSpicy(int n, char source_rod, char destination_rod, char aux_rod){
	YOUR CODE HERE
}
```

Example:

```
Current state of rods:
Rod A: 3 2 1
Rod B:
Rod C:
-----------------------
Move disk 1 from Rod A to Rod C
Current state of rods:
Rod A: 3 2
Rod B:
Rod C: 1
….
```
