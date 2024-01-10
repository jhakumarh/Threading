# Multithreaded Statistical Analysis and Prime Number Generation

This repository contains two C programs developed as part of my coursework for COMPSCI 3SH3. Both programs demonstrate the use of POSIX threads for concurrent execution.

## Statistical Analysis Program (`stats.c`)

This program calculates statistical values for a list of numbers provided on the command line. It creates three separate worker threads to determine the average, maximum, and minimum values of the numbers.

### Compilation and Execution

```bash
gcc -o stats stats.c -lpthread
./stats 90 81 78 95 79 72 85
