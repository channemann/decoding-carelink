## START analysis/ianj/raw/ReadHistoryData-page-1.data
#### RECORD 0 UnabsorbedInsulinBolus unknown head[29], body[0] op[0x5c]
###### DECODED
```python
[{'age': 34, 'amount': 1.8, 'curve': 4},
 {'age': 44, 'amount': 3.0, 'curve': 4},
 {'age': 144, 'amount': 1.3, 'curve': 4},
 {'age': 174, 'amount': 0.3, 'curve': 5},
 {'age': 78, 'amount': 1.0, 'curve': 20},
 {'age': 128, 'amount': 1.5, 'curve': 20},
 {'age': 148, 'amount': 1.3, 'curve': 20},
 {'age': 158, 'amount': 2.2, 'curve': 20},
 {'age': 218, 'amount': 3.5, 'curve': 20}]
```
    op hex (29)
    0000   0x5c 0x1d 0x48 0x22 0x04 0x78 0x2c 0x04    \.H".x,.
    0008   0x34 0x90 0x04 0x0c 0xae 0x05 0x28 0x4e    4.....(N
    0010   0x14 0x3c 0x80 0x14 0x34 0x94 0x14 0x58    .<..4..X
    0018   0x9e 0x14 0x8c 0xda 0x14                   .....
    decimal
             92   29   72   34    4  120   44    4
             52  144    4   12  174    5   40   78
             20   60  128   20   52  148   20   88
            158   20  140  218   20
    datetime (unknown)

    body (0)

#### RECORD 1 Bolus 2013-09-09T19:02:43 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 9.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x5c 0x00 0x5c 0x00 0xf4 0x00    ..\.\...
    decimal
              1    0   92    0   92    0  244    0
    datetime (2013-09-09T19:02:43)
    0000   0xab 0x42 0x53 0x69 0x0d                   .BSi.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 BolusWizard 2013-09-09T19:20:03 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-09T19:20:03)
    0000   0x83 0x54 0x13 0x69 0x0d                   .T.i.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x00 0x00 0x00 0x00 0x00 0x00 0x36         ......6
    decimal
              0  144    0  110   23   54    0    0
              0    0    0    0    0    0   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 3 UnabsorbedInsulinBolus unknown head[29], body[0] op[0x5c]
###### DECODED
```python
[{'age': 22, 'amount': 2.3, 'curve': 4},
 {'age': 52, 'amount': 1.8, 'curve': 4},
 {'age': 62, 'amount': 3.0, 'curve': 4},
 {'age': 162, 'amount': 1.3, 'curve': 4},
 {'age': 192, 'amount': 0.3, 'curve': 5},
 {'age': 96, 'amount': 1.0, 'curve': 20},
 {'age': 146, 'amount': 1.5, 'curve': 20},
 {'age': 166, 'amount': 1.3, 'curve': 20},
 {'age': 176, 'amount': 2.2, 'curve': 20}]
```
    op hex (29)
    0000   0x5c 0x1d 0x5c 0x16 0x04 0x48 0x34 0x04    \.\..H4.
    0008   0x78 0x3e 0x04 0x34 0xa2 0x04 0x0c 0xc0    x>.4....
    0010   0x05 0x28 0x60 0x14 0x3c 0x92 0x14 0x34    .(`.<..4
    0018   0xa6 0x14 0x58 0xb0 0x14                   ..X..
    decimal
             92   29   92   22    4   72   52    4
            120   62    4   52  162    4   12  192
              5   40   96   20   60  146   20   52
            166   20   88  176   20
    datetime (unknown)

    body (0)

#### RECORD 4 Bolus 2013-09-09T19:20:03 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x28 0x00 0x28 0x01 0x30 0x00    ..(.(.0.
    decimal
              1    0   40    0   40    1   48    0
    datetime (2013-09-09T19:20:03)
    0000   0x83 0x54 0x53 0x69 0x0d                   .TSi.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 5 NoDelivery 2013-09-09T20:19:51 head[4], body[0] op[0x06]

    op hex (4)
    0000   0x06 0x67 0x01 0x55                        .g.U
    decimal
              6  103    1   85
    datetime (2013-09-09T20:19:51)
    0000   0xb3 0x53 0xb4 0x89 0x0d                   .S...
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0]
#### RECORD 6 PumpSuspend 2013-09-09T20:19:51 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x02                                  ..
    decimal
             30    2
    datetime (2013-09-09T20:19:51)
    0000   0xb3 0x53 0x14 0x09 0x0d                   .S...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 7 ClearAlarm 2013-09-09T20:20:04 head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x67                                  .g
    decimal
             12  103
    datetime (2013-09-09T20:20:04)
    0000   0x84 0x54 0x14 0x09 0x0d                   .T...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 8 PumpSuspend 2013-09-09T20:20:07 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x43                                  .C
    decimal
             30   67
    datetime (2013-09-09T20:20:07)
    0000   0x87 0x54 0x14 0x09 0x0d                   .T...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 9 PumpResume 2013-09-09T21:15:25 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x66                                  .f
    decimal
             31  102
    datetime (2013-09-09T21:15:25)
    0000   0x99 0x4f 0x15 0x09 0x0d                   .O...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 10 BasalProfileStart 2013-09-09T21:15:25 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2013-09-09T21:15:25)
    0000   0x99 0x4f 0x15 0x09 0x0d                   .O...
    body (3)
    hex
    0000   0x1a 0x26 0x00                             .&.
    decimal
             26   38    0
    HOUR BITS: [0, 1, 0]
#### RECORD 11 PumpResume 2013-09-09T21:15:26 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0xc0                                  ..
    decimal
             31  192
    datetime (2013-09-09T21:15:26)
    0000   0x9a 0x4f 0x15 0x09 0x0d                   .O...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 12 BolusWizard 2013-09-09T21:15:40 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 20,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 72}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-09T21:15:40)
    0000   0xa8 0x4f 0x15 0x69 0x0d                   .O.i.
    body (15)
    hex
    0000   0x14 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x48 0x00 0x00 0x00 0x00 0x48 0x36         H....H6
    decimal
             20  144    0  110   23   54    0    0
             72    0    0    0    0   72   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 13 UnabsorbedInsulinBolus unknown head[23], body[0] op[0x5c]
###### DECODED
```python
[{'age': 117, 'amount': 1.0, 'curve': 4},
 {'age': 137, 'amount': 2.3, 'curve': 4},
 {'age': 167, 'amount': 1.8, 'curve': 4},
 {'age': 177, 'amount': 3.0, 'curve': 4},
 {'age': 21, 'amount': 1.3, 'curve': 20},
 {'age': 51, 'amount': 0.3, 'curve': 21},
 {'age': 211, 'amount': 1.0, 'curve': 20}]
```
    op hex (23)
    0000   0x5c 0x17 0x28 0x75 0x04 0x5c 0x89 0x04    \.(u.\..
    0008   0x48 0xa7 0x04 0x78 0xb1 0x04 0x34 0x15    H..x..4.
    0010   0x14 0x0c 0x33 0x15 0x28 0xd3 0x14         ..3.(..
    decimal
             92   23   40  117    4   92  137    4
             72  167    4  120  177    4   52   21
             20   12   51   21   40  211   20
    datetime (unknown)

    body (0)

#### RECORD 14 Bolus 2013-09-09T21:15:40 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x50 0x00 0x50 0x00 0x5c 0x00    ..P.P.\.
    decimal
              1    0   80    0   80    0   92    0
    datetime (2013-09-09T21:15:40)
    0000   0xa8 0x4f 0x55 0x69 0x0d                   .OUi.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 15 BolusWizard 2013-09-09T22:27:40 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-09T22:27:40)
    0000   0xa8 0x5b 0x16 0x69 0x0d                   .[.i.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x00 0x00 0x00 0x00 0x00 0x00 0x36         ......6
    decimal
              0  144    0  110   23   54    0    0
              0    0    0    0    0    0   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 16 UnabsorbedInsulinBolus unknown head[23], body[0] op[0x5c]
###### DECODED
```python
[{'age': 79, 'amount': 2.0, 'curve': 4},
 {'age': 189, 'amount': 1.0, 'curve': 4},
 {'age': 209, 'amount': 2.3, 'curve': 4},
 {'age': 239, 'amount': 1.8, 'curve': 4},
 {'age': 249, 'amount': 3.0, 'curve': 4},
 {'age': 93, 'amount': 1.3, 'curve': 20},
 {'age': 123, 'amount': 0.3, 'curve': 21}]
```
    op hex (23)
    0000   0x5c 0x17 0x50 0x4f 0x04 0x28 0xbd 0x04    \.PO.(..
    0008   0x5c 0xd1 0x04 0x48 0xef 0x04 0x78 0xf9    \..H..x.
    0010   0x04 0x34 0x5d 0x14 0x0c 0x7b 0x15         .4]..{.
    decimal
             92   23   80   79    4   40  189    4
             92  209    4   72  239    4  120  249
              4   52   93   20   12  123   21
    datetime (unknown)

    body (0)

#### RECORD 17 Bolus 2013-09-09T22:27:40 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x3c 0x00 0x3c 0x00 0x4c 0x00    ..<.<.L.
    decimal
              1    0   60    0   60    0   76    0
    datetime (2013-09-09T22:27:40)
    0000   0xa8 0x5b 0x56 0x69 0x0d                   .[Vi.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 18 CalBGForPH 2013-09-09T23:38:48 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 173}
```
    op hex (2)
    0000   0x0a 0xad                                  ..
    decimal
             10  173
    datetime (2013-09-09T23:38:48)
    0000   0xb0 0x66 0x57 0x09 0x0d                   .fW..
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 19 BolusWizard 2013-09-09T23:39:03 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 173,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 6.8,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 20.4,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xad                                  [.
    decimal
             91  173
    datetime (2013-09-09T23:39:03)
    0000   0x83 0x67 0x17 0x69 0x0d                   .g.i.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0xcc 0x00    ...n.6..
    0008   0x00 0x00 0x00 0x44 0x00 0x88 0x36         ...D..6
    decimal
              0  144    0  110   23   54  204    0
              0    0    0   68    0  136   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 20 UnabsorbedInsulinBolus unknown head[29], body[0] op[0x5c]
###### DECODED
```python
[{'age': 71, 'amount': 1.0, 'curve': 4},
 {'age': 81, 'amount': 0.5, 'curve': 4},
 {'age': 151, 'amount': 2.0, 'curve': 4},
 {'age': 5, 'amount': 1.0, 'curve': 20},
 {'age': 25, 'amount': 2.3, 'curve': 20},
 {'age': 55, 'amount': 1.8, 'curve': 20},
 {'age': 65, 'amount': 3.0, 'curve': 20},
 {'age': 165, 'amount': 1.3, 'curve': 20},
 {'age': 195, 'amount': 0.3, 'curve': 21}]
```
    op hex (29)
    0000   0x5c 0x1d 0x28 0x47 0x04 0x14 0x51 0x04    \.(G..Q.
    0008   0x50 0x97 0x04 0x28 0x05 0x14 0x5c 0x19    P..(..\.
    0010   0x14 0x48 0x37 0x14 0x78 0x41 0x14 0x34    .H7.xA.4
    0018   0xa5 0x14 0x0c 0xc3 0x15                   .....
    decimal
             92   29   40   71    4   20   81    4
             80  151    4   40    5   20   92   25
             20   72   55   20  120   65   20   52
            165   20   12  195   21
    datetime (unknown)

    body (0)

#### RECORD 21 Bolus 2013-09-09T23:39:04 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 13.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x88 0x00 0x88 0x00 0x44 0x00    ......D.
    decimal
              1    0  136    0  136    0   68    0
    datetime (2013-09-09T23:39:04)
    0000   0x84 0x67 0x57 0x69 0x0d                   .gWi.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 22 BasalProfileStart 2013-09-10T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-09-10T00:00:00)
    0000   0x80 0x40 0x00 0x0a 0x0d                   .@...
    body (3)
    hex
    0000   0x00 0x20 0x00                             . .
    decimal
              0   32    0
    HOUR BITS: [0, 1, 0]
#### RECORD 23 MResultTotals 2013-09-10T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x09 0x8a                   .....
    decimal
              7    0    0    9  138
    datetime (2013-09-10T00:00:00)
    0000   0x89 0x8d                                  ..
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0
    HOUR BITS: [1, 0, 0]
#### RECORD 24 Sara6E 2013-09-10T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2013-09-10T00:00:00)
    0000   0x89 0x8d                                  ..
    body (49)
    hex
    0000   0x06 0x20 0xde 0x7f 0x1b 0x0f 0x00 0x00    . ......
    0008   0x09 0x8a 0x02 0x5e 0x19 0x07 0x2c 0x4b    ...^..,K
    0010   0x00 0xcd 0x01 0xfc 0x03 0x7c 0x01 0xb4    .....|..
    0018   0x00 0x00 0x08 0x06 0x03 0x00 0x04 0x84    ........
    0020   0x00 0x64 0x00 0xfc 0x28 0x00 0x00 0x6c    .d..(..l
    0028   0x38 0x00 0x00 0x00 0x00 0x00 0x00 0x00    8.......
    0030   0x00                                       .
    decimal
              6   32  222  127   27   15    0    0
              9  138    2   94   25    7   44   75
              0  205    1  252    3  124    1  180
              0    0    8    6    3    0    4  132
              0  100    0  252   40    0    0  108
             56    0    0    0    0    0    0    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 25 BasalProfileStart 2013-09-10T04:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2013-09-10T04:00:00)
    0000   0x80 0x40 0x04 0x0a 0x0d                   .@...
    body (3)
    hex
    0000   0x08 0x2e 0x00                             ...
    decimal
              8   46    0
    HOUR BITS: [0, 1, 0]
#### RECORD 26 CalBGForPH 2013-09-10T05:22:51 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 191}
```
    op hex (2)
    0000   0x0a 0xbf                                  ..
    decimal
             10  191
    datetime (2013-09-10T05:22:51)
    0000   0xb3 0x56 0x45 0x0a 0x0d                   .VE..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 27 BolusWizard 2013-09-10T05:22:56 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 191,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 23.6,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xbf                                  [.
    decimal
             91  191
    datetime (2013-09-10T05:22:56)
    0000   0xb8 0x56 0x05 0x6a 0x0d                   .V.j.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0xec 0x00    ...n.6..
    0008   0x00 0x00 0x00 0x00 0x00 0xec 0x36         ......6
    decimal
              0  144    0  110   23   54  236    0
              0    0    0    0    0  236   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 28 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 88, 'amount': 3.4, 'curve': 20},
 {'age': 158, 'amount': 1.0, 'curve': 20},
 {'age': 168, 'amount': 0.5, 'curve': 20}]
```
    op hex (11)
    0000   0x5c 0x0b 0x88 0x58 0x14 0x28 0x9e 0x14    \..X.(..
    0008   0x14 0xa8 0x14                             ...
    decimal
             92   11  136   88   20   40  158   20
             20  168   20
    datetime (unknown)

    body (0)

#### RECORD 29 Bolus 2013-09-10T05:22:56 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 25.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0xfc 0x00 0xfc 0x00 0x00 0x00    ........
    decimal
              1    0  252    0  252    0    0    0
    datetime (2013-09-10T05:22:56)
    0000   0xb8 0x56 0x45 0x6a 0x0d                   .VEj.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 30 CalBGForPH 2013-09-10T06:02:42 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 172}
```
    op hex (2)
    0000   0x0a 0xac                                  ..
    decimal
             10  172
    datetime (2013-09-10T06:02:42)
    0000   0xaa 0x42 0x46 0x0a 0x0d                   .BF..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 31 BolusWizard 2013-09-10T06:02:46 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 172,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 22.8,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 20.4,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xac                                  [.
    decimal
             91  172
    datetime (2013-09-10T06:02:46)
    0000   0xae 0x42 0x06 0x6a 0x0d                   .B.j.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0xcc 0x00    ...n.6..
    0008   0x00 0x00 0x00 0xe4 0x00 0x00 0x36         ......6
    decimal
              0  144    0  110   23   54  204    0
              0    0    0  228    0    0   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 32 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 44, 'amount': 6.3, 'curve': 4},
 {'age': 128, 'amount': 3.4, 'curve': 20},
 {'age': 198, 'amount': 1.0, 'curve': 20},
 {'age': 208, 'amount': 0.5, 'curve': 20}]
```
    op hex (14)
    0000   0x5c 0x0e 0xfc 0x2c 0x04 0x88 0x80 0x14    \..,....
    0008   0x28 0xc6 0x14 0x14 0xd0 0x14              (.....
    decimal
             92   14  252   44    4  136  128   20
             40  198   20   20  208   20
    datetime (unknown)

    body (0)

#### RECORD 33 CalBGForPH 2013-09-10T06:03:00 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 194}
```
    op hex (2)
    0000   0x0a 0xc2                                  ..
    decimal
             10  194
    datetime (2013-09-10T06:03:00)
    0000   0x80 0x43 0x46 0x0a 0x0d                   .CF..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 34 CalBGForPH 2013-09-10T06:36:50 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 147}
```
    op hex (2)
    0000   0x0a 0x93                                  ..
    decimal
             10  147
    datetime (2013-09-10T06:36:50)
    0000   0xb2 0x64 0x46 0x0a 0x0d                   .dF..
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 35 BolusWizard 2013-09-10T06:36:55 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 147,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 18.4,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 16.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x93                                  [.
    decimal
             91  147
    datetime (2013-09-10T06:36:55)
    0000   0xb7 0x64 0x06 0x6a 0x0d                   .d.j.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0xa0 0x00    ...n.6..
    0008   0x00 0x00 0x00 0xb8 0x00 0x00 0x36         ......6
    decimal
              0  144    0  110   23   54  160    0
              0    0    0  184    0    0   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 36 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 78, 'amount': 6.3, 'curve': 4},
 {'age': 162, 'amount': 3.4, 'curve': 20}]
```
    op hex (8)
    0000   0x5c 0x08 0xfc 0x4e 0x04 0x88 0xa2 0x14    \..N....
    decimal
             92    8  252   78    4  136  162   20
    datetime (unknown)

    body (0)

#### RECORD 37 BolusWizard 2013-09-10T08:56:42 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 35,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 124}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T08:56:42)
    0000   0xaa 0x78 0x08 0x6a 0x0d                   .x.j.
    body (15)
    hex
    0000   0x23 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    #..n.6..
    0008   0x7c 0x00 0x00 0x00 0x00 0x7c 0x36         |....|6
    decimal
             35  144    0  110   23   54    0    0
            124    0    0    0    0  124   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 38 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 218, 'amount': 6.3, 'curve': 4}]
```
    op hex (5)
    0000   0x5c 0x05 0xfc 0xda 0x04                   \....
    decimal
             92    5  252  218    4
    datetime (unknown)

    body (0)

#### RECORD 39 Ian69 2013-09-10T08:56:42 head[2], body[2] op[0x69]

    op hex (2)
    0000   0x69 0x08                                  i.
    decimal
            105    8
    datetime (2013-09-10T08:56:42)
    0000   0xaa 0x78 0x08 0x0a 0x0d                   .x...
    body (2)
    hex
    0000   0x0a 0x1e                                  ..
    decimal
             10   30
    HOUR BITS: [0, 1, 1]
#### RECORD 40 Bolus 2013-09-10T08:56:42 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 12.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x7c 0x00 0x7c 0x00 0x18 0x00    ..|.|...
    decimal
              1    0  124    0  124    0   24    0
    datetime (2013-09-10T08:56:42)
    0000   0xaa 0x78 0x48 0x6a 0x0d                   .xHj.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 41 BasalProfileStart 2013-09-10T09:30:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2013-09-10T09:30:00)
    0000   0x80 0x5e 0x09 0x0a 0x0d                   .^...
    body (3)
    hex
    0000   0x13 0x1e 0x00                             ...
    decimal
             19   30    0
    HOUR BITS: [0, 1, 0]
#### RECORD 42 BolusWizard 2013-09-10T09:49:18 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 12,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 40}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T09:49:18)
    0000   0x92 0x71 0x09 0x6a 0x0d                   .q.j.
    body (15)
    hex
    0000   0x0c 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x28 0x00 0x00 0x00 0x00 0x28 0x36         (....(6
    decimal
             12  144    0  110   23   54    0    0
             40    0    0    0    0   40   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 43 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 51, 'amount': 1.2, 'curve': 4},
 {'age': 61, 'amount': 1.9, 'curve': 4},
 {'age': 15, 'amount': 6.3, 'curve': 20}]
```
    op hex (11)
    0000   0x5c 0x0b 0x30 0x33 0x04 0x4c 0x3d 0x04    \.03.L=.
    0008   0xfc 0x0f 0x14                             ...
    decimal
             92   11   48   51    4   76   61    4
            252   15   20
    datetime (unknown)

    body (0)

#### RECORD 44 Bolus 2013-09-10T09:49:18 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x28 0x00 0x28 0x00 0x68 0x00    ..(.(.h.
    decimal
              1    0   40    0   40    0  104    0
    datetime (2013-09-10T09:49:18)
    0000   0x92 0x71 0x49 0x6a 0x0d                   .qIj.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 45 CalBGForPH 2013-09-10T10:18:40 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 75}
```
    op hex (2)
    0000   0x0a 0x4b                                  .K
    decimal
             10   75
    datetime (2013-09-10T10:18:40)
    0000   0xa8 0x52 0x4a 0x0a 0x0d                   .RJ..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 46 BolusWizard 2013-09-10T10:18:49 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 75,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 12.4,
 'carb_input': 7,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 3.6,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 24}
```
    op hex (2)
    0000   0x5b 0x4b                                  [K
    decimal
             91   75
    datetime (2013-09-10T10:18:49)
    0000   0xb1 0x52 0x0a 0x6a 0x0d                   .R.j.
    body (15)
    hex
    0000   0x07 0x90 0x00 0x6e 0x17 0x36 0x24 0x00    ...n.6$.
    0008   0x18 0x00 0x00 0x7c 0x00 0x18 0x36         ...|..6
    decimal
              7  144    0  110   23   54   36    0
             24    0    0  124    0   24   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 47 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 30, 'amount': 1.0, 'curve': 4},
 {'age': 80, 'amount': 1.2, 'curve': 4},
 {'age': 90, 'amount': 1.9, 'curve': 4},
 {'age': 44, 'amount': 6.3, 'curve': 20}]
```
    op hex (14)
    0000   0x5c 0x0e 0x28 0x1e 0x04 0x30 0x50 0x04    \.(..0P.
    0008   0x4c 0x5a 0x04 0xfc 0x2c 0x14              LZ..,.
    decimal
             92   14   40   30    4   48   80    4
             76   90    4  252   44   20
    datetime (unknown)

    body (0)

#### RECORD 48 Bolus 2013-09-10T10:18:49 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 1.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x0c 0x00 0x0c 0x00 0x7c 0x00    ......|.
    decimal
              1    0   12    0   12    0  124    0
    datetime (2013-09-10T10:18:49)
    0000   0xb1 0x52 0x4a 0x6a 0x0d                   .RJj.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 49 BolusWizard 2013-09-10T10:24:13 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 75,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 12.8,
 'carb_input': 17,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 3.6,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 60}
```
    op hex (2)
    0000   0x5b 0x4b                                  [K
    decimal
             91   75
    datetime (2013-09-10T10:24:13)
    0000   0x8d 0x58 0x0a 0x6a 0x0d                   .X.j.
    body (15)
    hex
    0000   0x11 0x90 0x00 0x6e 0x17 0x36 0x24 0x00    ...n.6$.
    0008   0x3c 0x00 0x00 0x80 0x00 0x3c 0x36         <....<6
    decimal
             17  144    0  110   23   54   36    0
             60    0    0  128    0   60   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 50 UnabsorbedInsulinBolus unknown head[17], body[0] op[0x5c]
###### DECODED
```python
[{'age': 6, 'amount': 0.3, 'curve': 4},
 {'age': 36, 'amount': 1.0, 'curve': 4},
 {'age': 86, 'amount': 1.2, 'curve': 4},
 {'age': 96, 'amount': 1.9, 'curve': 4},
 {'age': 50, 'amount': 6.3, 'curve': 20}]
```
    op hex (17)
    0000   0x5c 0x11 0x0c 0x06 0x04 0x28 0x24 0x04    \....($.
    0008   0x30 0x56 0x04 0x4c 0x60 0x04 0xfc 0x32    0V.L`..2
    0010   0x14                                       .
    decimal
             92   17   12    6    4   40   36    4
             48   86    4   76   96    4  252   50
             20
    datetime (unknown)

    body (0)

#### RECORD 51 Bolus 2013-09-10T10:24:13 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x3c 0x00 0x3c 0x00 0x80 0x00    ..<.<...
    decimal
              1    0   60    0   60    0  128    0
    datetime (2013-09-10T10:24:13)
    0000   0x8d 0x58 0x4a 0x6a 0x0d                   .XJj.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 52 BolusWizard 2013-09-10T10:36:04 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 6,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 20}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T10:36:04)
    0000   0x84 0x64 0x0a 0x6a 0x0d                   .d.j.
    body (15)
    hex
    0000   0x06 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x14 0x00 0x00 0x00 0x00 0x14 0x36         ......6
    decimal
              6  144    0  110   23   54    0    0
             20    0    0    0    0   20   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 53 UnabsorbedInsulinBolus unknown head[17], body[0] op[0x5c]
###### DECODED
```python
[{'age': 18, 'amount': 1.8, 'curve': 4},
 {'age': 48, 'amount': 1.0, 'curve': 4},
 {'age': 98, 'amount': 1.2, 'curve': 4},
 {'age': 108, 'amount': 1.9, 'curve': 4},
 {'age': 62, 'amount': 6.3, 'curve': 20}]
```
    op hex (17)
    0000   0x5c 0x11 0x48 0x12 0x04 0x28 0x30 0x04    \.H..(0.
    0008   0x30 0x62 0x04 0x4c 0x6c 0x04 0xfc 0x3e    0b.Ll..>
    0010   0x14                                       .
    decimal
             92   17   72   18    4   40   48    4
             48   98    4   76  108    4  252   62
             20
    datetime (unknown)

    body (0)

#### RECORD 54 Bolus 2013-09-10T10:36:04 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x14 0x00 0x14 0x00 0xb0 0x00    ........
    decimal
              1    0   20    0   20    0  176    0
    datetime (2013-09-10T10:36:04)
    0000   0x84 0x64 0x4a 0x6a 0x0d                   .dJj.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 55 Ian0B 2013-09-10T10:38:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x69 0x00                             .i.
    decimal
             11  105    0
    datetime (2013-09-10T10:38:00)
    0000   0x80 0x66 0x4a 0xaa 0x0d                   .fJ..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 56 Ian0B 2013-09-10T11:38:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2013-09-10T11:38:00)
    0000   0x80 0x66 0x4b 0xaa 0x0d                   .fK..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 57 CalBGForPH 2013-09-10T11:38:55 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 48}
```
    op hex (2)
    0000   0x0a 0x30                                  .0
    decimal
             10   48
    datetime (2013-09-10T11:38:55)
    0000   0xb7 0x66 0x4b 0x0a 0x0d                   .fK..
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 58 BolusWizard 2013-09-10T12:23:26 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T12:23:26)
    0000   0x9a 0x57 0x0c 0x6a 0x0d                   .W.j.
    body (15)
    hex
    0000   0x00 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x00 0x00 0x00 0x00 0x00 0x00 0x36         ......6
    decimal
              0  144    0  110   23   54    0    0
              0    0    0    0    0    0   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 59 UnabsorbedInsulinBolus unknown head[20], body[0] op[0x5c]
###### DECODED
```python
[{'age': 115, 'amount': 0.5, 'curve': 4},
 {'age': 125, 'amount': 1.8, 'curve': 4},
 {'age': 155, 'amount': 1.0, 'curve': 4},
 {'age': 205, 'amount': 1.2, 'curve': 4},
 {'age': 215, 'amount': 1.9, 'curve': 4},
 {'age': 169, 'amount': 6.3, 'curve': 20}]
```
    op hex (20)
    0000   0x5c 0x14 0x14 0x73 0x04 0x48 0x7d 0x04    \..s.H}.
    0008   0x28 0x9b 0x04 0x30 0xcd 0x04 0x4c 0xd7    (..0..L.
    0010   0x04 0xfc 0xa9 0x14                        ....
    decimal
             92   20   20  115    4   72  125    4
             40  155    4   48  205    4   76  215
              4  252  169   20
    datetime (unknown)

    body (0)

#### RECORD 60 BolusWizard 2013-09-10T12:23:35 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 36,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 128}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T12:23:35)
    0000   0xa3 0x57 0x0c 0x6a 0x0d                   .W.j.
    body (15)
    hex
    0000   0x24 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    $..n.6..
    0008   0x80 0x00 0x00 0x00 0x00 0x80 0x36         ......6
    decimal
             36  144    0  110   23   54    0    0
            128    0    0    0    0  128   54
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 61 UnabsorbedInsulinBolus unknown head[20], body[0] op[0x5c]
###### DECODED
```python
[{'age': 115, 'amount': 0.5, 'curve': 4},
 {'age': 125, 'amount': 1.8, 'curve': 4},
 {'age': 155, 'amount': 1.0, 'curve': 4},
 {'age': 205, 'amount': 1.2, 'curve': 4},
 {'age': 215, 'amount': 1.9, 'curve': 4},
 {'age': 169, 'amount': 6.3, 'curve': 20}]
```
    op hex (20)
    0000   0x5c 0x14 0x14 0x73 0x04 0x48 0x7d 0x04    \..s.H}.
    0008   0x28 0x9b 0x04 0x30 0xcd 0x04 0x4c 0xd7    (..0..L.
    0010   0x04 0xfc 0xa9 0x14                        ....
    decimal
             92   20   20  115    4   72  125    4
             40  155    4   48  205    4   76  215
              4  252  169   20
    datetime (unknown)

    body (0)

#### RECORD 62 Ian69 2013-09-10T12:23:36 head[2], body[2] op[0x69]

    op hex (2)
    0000   0x69 0x0b                                  i.
    decimal
            105   11
    datetime (2013-09-10T12:23:36)
    0000   0xa4 0x57 0x0c 0x0a 0x0d                   .W...
    body (2)
    hex
    0000   0x0e 0x1e                                  ..
    decimal
             14   30
    HOUR BITS: [0, 1, 0]
#### RECORD 63 Bolus 2013-09-10T12:23:36 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 12.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x80 0x00 0x80 0x00 0x40 0x00    ......@.
    decimal
              1    0  128    0  128    0   64    0
    datetime (2013-09-10T12:23:36)
    0000   0xa4 0x57 0x4c 0x6a 0x0d                   .WLj.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 64 BolusWizard 2013-09-10T12:41:19 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 54,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 23,
 'bolus_estimate': 0.0,
 'carb_input': 7,
 'carb_ratio': 0,
 'correction_estimate': 0.6,
 'food_estimate': 0.0,
 'sensitivity': 110,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 24}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-09-10T12:41:19)
    0000   0x93 0x69 0x0c 0x6a 0x0d                   .i.j.
    body (15)
    hex
    0000   0x07 0x90 0x00 0x6e 0x17 0x36 0x00 0x00    ...n.6..
    0008   0x18 0x00 0x00 0x00 0x00 0x18 0x36         ......6
    decimal
              7  144    0  110   23   54    0    0
             24    0    0    0    0   24   54
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 65 UnabsorbedInsulinBolus unknown head[23], body[0] op[0x5c]
###### DECODED
```python
[{'age': 23, 'amount': 3.2, 'curve': 4},
 {'age': 133, 'amount': 0.5, 'curve': 4},
 {'age': 143, 'amount': 1.8, 'curve': 4},
 {'age': 173, 'amount': 1.0, 'curve': 4},
 {'age': 223, 'amount': 1.2, 'curve': 4},
 {'age': 233, 'amount': 1.9, 'curve': 4},
 {'age': 187, 'amount': 6.3, 'curve': 20}]
```
    op hex (23)
    0000   0x5c 0x17 0x80 0x17 0x04 0x14 0x85 0x04    \.......
    0008   0x48 0x8f 0x04 0x28 0xad 0x04 0x30 0xdf    H..(..0.
    0010   0x04 0x4c 0xe9 0x04 0xfc 0xbb 0x14         .L.....
    decimal
             92   23  128   23    4   20  133    4
             72  143    4   40  173    4   48  223
              4   76  233    4  252  187   20
    datetime (unknown)

    body (0)

#### RECORD 66 Bolus 2013-09-10T12:41:19 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 3.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x20 0x00 0x20 0x00 0xac 0x00    .. . ...
    decimal
              1    0   32    0   32    0  172    0
    datetime (2013-09-10T12:41:19)
    0000   0x93 0x69 0x4c 0x6a 0x0d                   .iLj.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 67 Base unknown head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xc8                                  ..
    decimal
              0  200
    datetime (unknown)

    body (0)

`end analysis/ianj/raw/ReadHistoryData-page-1.data: 68 records`
