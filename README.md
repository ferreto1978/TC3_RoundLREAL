# TwinCAT3 fnRoundLREAL
TwinCAT 3 function that rounds an LREAL (64bit REAL) to a specific number of decimal places.

Example:
```
RoundedNumber := fnRoundLREAL(2.554800000002, 3);
// Result = 2.555
```

There are 2 ethods available.
- Method 1: Uses convertion to LINT
- Method 2: Uses LTRUNC from the Tc2_Math library
