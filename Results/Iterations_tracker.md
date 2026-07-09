# Iteration_Tracker.md

## Run Log
| Run # | Sweep Purpose | CLOCK_PERIOD (ns) | FP_CORE_UTIL (%) | PL_TARGET_DENSITY | SYNTH_STRATEGY | Notes on Change | Instance Count | Core Area (um2) | Utilization | Setup WNS (ns) | Setup TNS (ns) | Hold WNS (ns) | Hold TNS (ns) | Setup WS max corner (ns) | Max Slew Violations | Max Fanout Violations | Max Cap Violations | Route DRC Errors | Antenna Violations | Magic DRC Errors | KLayout DRC Errors | LVS Errors | Power Total (W) | Route Wirelength (um) | Pass/Fail |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Baseline run (initial config) | 30 | - | - | AREA 0 | First clean run – establishing  | 9132 | 57475.1 | 0.736002 | 0 | 0 | 0 | 0 | 16.358 | 1401 | 26 | 28 | 0 | 0 | 0 | 0 | 0 | 0.002064 | 113562 | PASS |
| 2 |  | 10 | - | - | Delay 4 | Reduced the number of max | 12899 | 68105.3 | 0.573082 | 0 | 0 | 0 | 0 | 1.97956145967242 | 599 | 24 | 0 | 0 | 0 | 0 | 0 | 0 | 0.00578680541366339 | 125040 | PASS |
| 3 | pin_config.cfg and  | 10 | 65 | - | Delay 4 | Arranged the i/p and o/p pins | 12853 | 68105.3 | 0.572917 | 0 | 0 | 0 | 0 | 1.91975329955517 | 530 | 15 | 0 | 0 | 0 | 0 | 0 | 0 | 0.00572399003431201 | 136806 | PASS |
| 4 | Added target density of 0.7 | 10 | 65 | 0.7 | DELAY 4 | Attempt to make the design more | 12878 | 68105.3 | 0.572457 | 0 | 0 | 0 | 0 | 0.60447026872616 | 368 | 26 | 0 | 0 | 0 | 0 | 0 | 0 | 0.00573303503915668 | 84645 | PASS |
| 5 | Ran the same parameters  | 10 | 65 | 0.7 | AREA 1 | To compare the final parameters | 9040 | 57365 | 0.733598 | 0 | 0 | 0 | 0 | 1.99741295823485 | 1165 | 34 | 0 | 0 | 0 | 0 | 0 | 0 | 0.00617261696606875 | 152731 | PASS |
