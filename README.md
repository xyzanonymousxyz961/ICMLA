# Online Appendix for "Cloud Failure Prediction with Hierarchical Temporary Memory: An Empirical Assessment"

## A.1. Prediction Effectiveness

### A.1.1 Single Resource Global Prediction

| Epsilon | n | x | Precision   | Recall      | F-measure   |
| ------- | - | - | ----------- | ----------- | ----------- |
| 0.8     | 1 | 6 | 0.5         | 0.416666667 | 0.454545455 |
| 0.8     | 1 | 5 | 0.444444444 | 0.666666667 | 0.533333333 |
| 0.8     | 1 | 4 | 0.5         | 0.916666667 | 0.647058824 |
| 0.8     | 1 | 3 | 0.52173913  | 1           | 0.685714286 |
| 0.8     | 1 | 2 | 0.5         | 1           | 0.666666667 |
| 0.8     | 1 | 1 | 0.5         | 1           | 0.666666667 |
| 0.85    | 1 | 6 | 0.384615385 | 0.416666667 | 0.4         |
| 0.85    | 1 | 5 | 0.470588235 | 0.666666667 | 0.551724138 |
| 0.85    | 1 | 4 | 0.523809524 | 0.916666667 | 0.666666667 |
| 0.85    | 1 | 3 | 0.5         | 0.916666667 | 0.647058824 |
| 0.85    | 1 | 2 | 0.5         | 1           | 0.666666667 |
| 0.85    | 1 | 1 | 0.5         | 1           | 0.666666667 |
| 0.9     | 1 | 6 | 0.5         | 0.5         | 0.5         |
| 0.9     | 1 | 5 | 0.6         | 0.75        | 0.666666667 |
| 0.9     | 1 | 4 | 0.5         | 0.75        | 0.6         |
| 0.9     | 1 | 3 | 0.52173913  | 1           | 0.685714286 |
| 0.9     | 1 | 2 | 0.5         | 1           | 0.666666667 |
| 0.9     | 1 | 1 | 0.5         | 1           | 0.666666667 |
| 0.95    | 1 | 6 | 1           | 0.166666667 | 0.285714286 |
| 0.95    | 1 | 5 | 1           | 0.333333333 | 0.5         |
| 0.95    | 1 | 4 | 0.875       | 0.583333333 | 0.7         |
| 0.95    | 1 | 3 | 0.611111111 | 0.916666667 | 0.733333333 |
| 0.95    | 1 | 2 | 0.47826087  | 0.916666667 | 0.628571429 |
| 0.95    | 1 | 1 | 0.5         | 1           | 0.666666667 |
| 0.8     | 2 | 6 | 0.666666667 | 0.333333333 | 0.444444444 |
| 0.8     | 2 | 5 | 0.625       | 0.416666667 | 0.5         |
| 0.8     | 2 | 4 | 0.533333333 | 0.666666667 | 0.592592593 |
| 0.8     | 2 | 3 | 0.55        | 0.916666667 | 0.6875      |
| 0.8     | 2 | 2 | 0.5         | 1           | 0.666666667 |
| 0.8     | 2 | 1 | 0.5         | 1           | 0.666666667 |
| 0.85    | 2 | 6 | 0.461538462 | 0.5         | 0.48        |
| 0.85    | 2 | 5 | 0.428571429 | 0.5         | 0.461538462 |
| 0.85    | 2 | 4 | 0.526315789 | 0.833333333 | 0.64516129  |
| 0.85    | 2 | 3 | 0.523809524 | 0.916666667 | 0.666666667 |
| 0.85    | 2 | 2 | 0.5         | 0.916666667 | 0.647058824 |
| 0.85    | 2 | 1 | 0.5         | 1           | 0.666666667 |
| 0.9     | 2 | 6 | 0.428571429 | 0.25        | 0.315789474 |
| 0.9     | 2 | 5 | 0.5         | 0.5         | 0.5         |
| 0.9     | 2 | 4 | 0.6         | 0.75        | 0.666666667 |
| 0.9     | 2 | 3 | 0.5625      | 0.75        | 0.642857143 |
| 0.9     | 2 | 2 | 0.545454545 | 1           | 0.705882353 |
| 0.9     | 2 | 1 | 0.5         | 1           | 0.666666667 |
| 0.95    | 2 | 6 | 1           | 0.166666667 | 0.285714286 |
| 0.95    | 2 | 5 | 1           | 0.166666667 | 0.285714286 |
| 0.95    | 2 | 4 | 1           | 0.333333333 | 0.5         |
| 0.95    | 2 | 3 | 0.875       | 0.583333333 | 0.7         |
| 0.95    | 2 | 2 | 0.611111111 | 0.916666667 | 0.733333333 |
| 0.95    | 2 | 1 | 0.47826087  | 0.916666667 | 0.628571429 |

### A.1.2 Vote-based Global Prediction

| Epsilon | n | y | Precision   | Recall      | F-measure   |
| ------- | - | - | ----------- | ----------- | ----------- |
| 0.8     | 1 | 3 | 0.545454545 | 0.5         | 0.52173913  |
| 0.8     | 1 | 2 | 0.470588235 | 0.666666667 | 0.551724138 |
| 0.8     | 1 | 1 | 0.47826087  | 0.916666667 | 0.628571429 |
| 0.8     | 2 | 3 | 0           | 0           | 0           |
| 0.8     | 2 | 2 | 1           | 0.333333333 | 0.5         |
| 0.8     | 2 | 1 | 0.5         | 0.416666667 | 0.454545455 |
| 0.85    | 1 | 3 | 0.666666667 | 0.666666667 | 0.666666667 |
| 0.85    | 1 | 2 | 0.588235294 | 0.833333333 | 0.689655172 |
| 0.85    | 1 | 1 | 0.52173913  | 1           | 0.685714286 |
| 0.85    | 2 | 3 | 1           | 0.083333333 | 0.153846154 |
| 0.85    | 2 | 2 | 0.571428571 | 0.333333333 | 0.421052632 |
| 0.85    | 2 | 1 | 0.666666667 | 0.666666667 | 0.666666667 |
| 0.9     | 1 | 3 | 1           | 0.333333333 | 0.5         |
| 0.9     | 1 | 2 | 0.857142857 | 0.5         | 0.631578947 |
| 0.9     | 1 | 1 | 0.647058824 | 0.916666667 | 0.75862069  |
| 0.9     | 2 | 3 | 0           | 0           | 0           |
| 0.9     | 2 | 2 | 0           | 0           | 0           |
| 0.9     | 2 | 1 | 0.6         | 0.25        | 0.352941176 |
| 0.95    | 1 | 3 | 1           | 0.166666667 | 0.285714286 |
| 0.95    | 1 | 2 | 0.75        | 0.25        | 0.375       |
| 0.95    | 1 | 1 | 0.75        | 0.75        | 0.75        |
| 0.95    | 2 | 3 | 0           | 0           | 0           |
| 0.95    | 2 | 2 | 1           | 0.083333333 | 0.153846154 |
| 0.95    | 2 | 1 | 1           | 0.083333333 | 0.153846154 |.

## A.1. List of monitored componenent KPIs

io.Avg_req_queue_length

io.Avg_wait_time

io.Read_bytes_per_sec

io.Write_bytes_per_sec

network.Bytes_received_per_sec

network.Bytes_send_per_sec      

network.Loss_rate_5s

network.Pkts_received_5s_python

network.Pkts_sent_5s_python

network.Retransmission

vm_stats.Memory_Used

vm_stats.Memory__Cached

vm_stats.Memory_in_Buffers

vm_stats.Swap_Space_Used

sockets.Sockets_in_use

system.Cxt_Switches_per_sec

system.Pages_Faults_per_sec

system.Pages_Swapped_in

system.Pages_Swapped_out

system.Pages_paged_out_per_sec

system.Total_Number_Processes

cpu.Busy_CPU

cpu.System_CPU

cpu.User_CPU


