| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `cpp -O2 -march=x86-64` | 234.6 ± 0.0 | 234.5 | 234.7 | 1.77 ± 0.01 |
| `cpp -O3 -march=x86-64` | 235.2 ± 1.0 | 234.2 | 237.4 | 1.77 ± 0.01 |
| `cpp -Ofast -march=x86-64` | 230.0 ± 0.4 | 229.7 | 230.9 | 1.73 ± 0.01 |
| `cpp -O2 -march=native` | 174.9 ± 0.4 | 174.2 | 175.5 | 1.32 ± 0.01 |
| `cpp -O3 -march=native` | 142.1 ± 5.4 | 139.5 | 164.4 | 1.07 ± 0.04 |
| `cpp -Ofast -march=native` | 132.9 ± 0.7 | 132.0 | 134.3 | 1.00 |
