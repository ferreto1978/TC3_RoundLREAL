# TwinCAT3 fnRoundLREAL
TwinCAT 3 function that rounds an LREAL (64bit REAL) to a specific number of decimal places.

Example:
```
RoundedNumber := fnRoundLREAL(
	NumberToRound := 2.554800000002,
	Decimals := 3
);
// Result = 2.555
```

There are 2 methods available.
- Method 1: Uses convertion to LINT
- Method 2: Uses LTRUNC but requires the **Tc2_Math** library
