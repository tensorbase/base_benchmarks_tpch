## TPC-H Benchmark

NOTE: currently, the TPC-H benchmark is just used to track the completeness of TB. The performance has not been tunned in any eye.

TPC-H Dataset, SF: 1

|Query | TensorBase (main branch)  |
|:----:|:-------------------------:|
| Q1*  | 0.702 sec                  |

* Q1 is tweaked in which "where" clause has been removed in that the Date built-ins has not been supported by TensorBase.
