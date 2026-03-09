Code was Tested and successfully run on pdp11/70 emulator at https://skn.noip.me/pdp11/pdp11.html

follow these instructions to get BASIC PLUS up and running :
at >boot prompt type :
BOOT RP2
strictly enter THIS DATE at request :
1-JAN-90 (this emulator only accepts dates from 01-JAN-86 to 31-DEC-99 )
time 12:00
At User prompt enter exactly 1,2
User 1,2
Password SYSTEM
enter command to run BASIC :
SWITCH BASIC 
System will reply with :
$Ready

Open .bas and Copy the text code from notepad or other editor.
Then paste into browser emulator using right button (ctrl-v win't work)   
type :
RUN
and... HAVE FUN !

FOLLOWING A SAMPLE OUTPUT AND TERMINAL INTERACTION FROM THE BEGINNING
-------
Paul Nankervis - paulnank@hotmail.com

Boot> boot rp2

Warning - main memory cache disabled at startup.
RSTS/E will not use cache.
System may run slowly.
RU0: controller type is UNSUPPORTED by RSTS/E - device disabled.


Enter today's date as DAY-MONTH-YEAR (e.g., 7-SEP-85)
Today's date? 1-JAN-90

Current time? 12:00


Start timesharing? <Yes> 

Default memory allocation table shows LESS
memory than INIT detects on this machine.

Adjusting memory table.

  Memory allocation table:

     0K: 00000000 - 00427777 (  70K) : EXEC
    70K: 00430000 - 15163777 (1623K) : USER
  1693K: 15164000 - 16737777 ( 219K) : XBUF

Memory available to RSTS/E is 1912K words.

01-Jan-90 12:00 PM

1 device disabled

Proceed with system startup? <YES> 

 Beginning RSTS/E system startup...
01-Jan-90 12:00 PM   Installing monitor overlays
01-Jan-90 12:00 PM   Mounting disks
01-Jan-90 12:00 PM   Assigning logical names
01-Jan-90 12:00 PM   Starting error logging
01-Jan-90 12:00 PM   Setting system characteristics
01-Jan-90 12:00 PM   Installing run-time systems and libraries
01-Jan-90 12:00 PM   Setting terminal characteristics
01-Jan-90 12:00 PM   Defining system commands
01-Jan-90 12:00 PM   Setting printer characteristics
01-Jan-90 12:00 PM   Starting spoolers

*** From [1,2] on KB0: at 12:00 PM 01-Jan-90     
** RSTS/E is on the air...     

RSTS V9.6-11 RSTS   (DB2) INIT V9.6-11

V9.6-11 01-Jan-90 12:00 PM
User: 1,2
Password: SYSTEM

Jobs detached under this account:
   Job  What  Size  State   Run-time   RTS
    1  ERRCPY 5K    SR           0.4  ...RSX
    3  PBS... 19K   SL           0.0  ...RSX
Job number to attach to? 
Last logged in on 01-Jan-90, 12:00 PM detached.
2 other users are logged in under this account

Your password has not been changed in over 365 days.
Please change it.

Welcome to RSTS/E V9.6 time sharing

This is a minimal system with a user account of 11,70

Hopefully it demonstrates how things were in the good old days

Paul Nankervis
paulnank@hotmail.com
http://skn.noip.me/pdp11/pdp11.html

$ SWITCH BASIC 

Ready
RUN
NONAME  12:23 PM        01-Jan-90

DO YOU WANT TO TRACE? N



               SATELLITE OBSERVABILITY REPORT

FOR OBSERVER # 1 AT  88 W 0 

PERIOD OF OBSERVATION FROM: 0700  12 / 26 / 1972 
                            TO:0700  12 / 27 / 1972 



          SATELLITE # 1  OF 3 FOR OBSERVER # 1 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0         0.00      19.27        GOOD    236337.    18775.    75098.
18:15         0.00      15.70        GOOD    241029.    18769.      -21.
18:30         0.00      12.13        GOOD    245721.    18764.      -20.
18:45         0.00       8.55        GOOD    250411.    18759.      -20.
19: 0         0.00       5.52        GOOD    255100.    18755.      -19.
19:15         0.00       1.38        GOOD    259788.    18750.      -18.



          SATELLITE # 2  OF 3 FOR OBSERVER # 1 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0   1549620.00      79.84        GOOD     23013.     5890.    23560.
18:15   % .887865E 8       79.79        GOOD     22005.     6185.     1180.
18:30   % .508709E 10       79.00        GOOD     20932.     6509.     1294.
18:45   % .291469E 12       77.62        GOOD     19791.     6865.     1427.
19: 0       267.51      76.39        GOOD     18579.     7262.     1586.
19:15       257.40      73.70        GOOD     17291.     7706.     1777.
19:30       248.20      71.35        GOOD     15923.     8209.     2011.
19:45       239.40      68.78        GOOD     14471.     8785.     2305.
20: 0       230.46      65.93        GOOD     12930.     9455.     2681.
20:15       220.84      62.65        GOOD     11299.    10248.     3173.
20:30       210.02      58.67        GOOD      9579.    11206.     3829.
20:45       197.42      53.38        GOOD      7786.    12384.     4715.
21: 0       182.41      45.65        POOR      5963.    13853.     5874.
21:15       164.32      33.42        POOR      4238.    15624.     7086.



          SATELLITE # 3  OF 3 FOR OBSERVER # 1 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

19:45       120.97      11.42        GOOD     20685.     7164.    28656.
20: 0       125.64      13.95        GOOD     20730.     7151.      -51.
20:15       130.46      16.08        GOOD     20775.     7138.      -52.
20:30       135.39      17.75        GOOD     20822.     7125.      -52.
20:45       140.39      18.91        GOOD     20869.     7112.      -53.
21: 0       145.40      19.53        POOR     20916.     7099.      -53.
21:15       150.35      19.61        POOR     20963.     7086.      -53.
21:30       155.13      19.12        POOR     21010.     7072.      -53.
21:45       159.68      18.09        POOR     21057.     7059.      -53.
22: 0       163.91      16.55        POOR     21104.     7046.      -52.
22:15       167.77      14.54        POOR     21150.     7033.      -51.
22:30       171.21      12.10        POOR     21195.     7021.      -51.
22:45       174.20       9.28        POOR     21240.     7008.      -50.



               ATELLITE OBSERVABILITY REPORT

FOR OBSERVER # 2 AT  95 W 0 

PERIOD OF OBSERVATION FROM: 0700  0 / 26 / 1972 
                            TO:0700  12 / 27 / 1972 



          SATELLITE # 1  OF 3 FOR OBSERVER # 2 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0   % .142662E 31       25.92        GOOD    237523.    18883.      532.
18:15         0.00      22.36        GOOD    242243.    18878.      -21.
18:30         0.00      18.80        GOOD    246962.    18873.      -20.
18:45         0.00      15.23        GOOD    251679.    18868.      -19.
19: 0         0.00      11.65        GOOD    256395.    18863.      -19.
19:15         0.00       8.07        GOOD    261110.    18859.      -18.
19:30         0.00       5.51        GOOD    265824.    18854.      -17.
19:45         0.00       0.89        GOOD    270537.    18850.      -17.



          SATELLITE # 2  OF 3 FOR OBSERVER # 2 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0     23181.80      77.94        GOOD     27064.     4974.   -42600.
18:15   1328220.00      78.17        GOOD     26257.     5184.      839.
18:30   % .761014E 8       77.71        GOOD     25399.     5410.      905.
18:45   % .436029E 10       76.64        GOOD     24485.     5655.      978.
19: 0   % .249826E 12       75.09        GOOD     23516.     5920.     1061.
19:15   % .14314E 14       73.22        GOOD     22487.     6209.     1156.
19:30   % .82013E 15       72.21        GOOD     21395.     6525.     1265.
19:45       265.78      68.91        GOOD     20239.     6873.     1392.
20: 0       259.69      66.60        GOOD     19013.     7259.     1543.
20:15       253.90      64.24        GOOD     17715.     7690.     1725.
20:30       248.10      61.85        GOOD     16339.     8177.     1948.
20:45       242.01      59.43        GOOD     14882.     8734.     2227.
21: 0       235.31      56.96        POOR     13340.     9379.     2581.
21:15       227.60      54.39        POOR     11709.    10140.     3043.
21:30       218.32      51.55        POOR      9993.    11054.     3656.
21:45       206.72      48.09        POOR      8203.    12174.     4480.
22: 0       191.76      43.25        POOR      6376.    13565.     5564.
22:15       172.28      35.36        POOR      4621.    15256.     6765.



          SATELLITE # 3  OF 3 FOR OBSERVER # 2 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

20:15       128.92      10.78        GOOD     20738.     7149.      563.
20:30       133.59      12.86        GOOD     20781.     7137.      -49.
20:45       138.36      14.49        GOOD     20825.     7124.      -50.
21: 0       143.19      15.61        POOR     20870.     7112.      -50.
21:15       148.02      16.20        POOR     20914.     7099.      -51.
21:30       152.77      16.25        POOR     20959.     7086.      -51.
21:45       157.38      15.75        POOR     21004.     7074.      -51.
22: 0       161.76      14.72        POOR     21049.     7061.      -50.
22:15       165.84      13.18        POOR     21094.     7049.      -50.
22:30       169.57      11.17        POOR     21138.     7036.      -50.



               ATELLITE OBSERVABILITY REPORT

FOR OBSERVER # 3 AT  80 W 0 

PERIOD OF OBSERVATION FROM: 0800  0 / 26 / 1972 
                            TO:0800  12 / 27 / 1972 



          SATELLITE # 1  OF 3 FOR OBSERVER # 3 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0   % .109562E 31       25.87        GOOD    218631.    18906.      223.
18:15         0.00      22.32        GOOD    223356.    18900.      -25.
18:30         0.00      18.75        GOOD    228080.    18894.      -24.
18:45         0.00      15.18        GOOD    232802.    18888.      -23.
19: 0         0.00      11.61        GOOD    237523.    18883.      -22.
19:15         0.00       8.02        GOOD    242243.    18878.      -21.
19:30         0.00       5.47        GOOD    246962.    18873.      -20.



          SATELLITE # 2  OF 3 FOR OBSERVER # 3 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0    502485.00      71.60        GOOD     29796.     4276.   -43923.
18:15   % .287903E 8       71.35        GOOD     29180.     4432.      626.
18:30   % .164956E 10       70.67        GOOD     28519.     4601.      673.
18:45   % .945129E 11       69.59        GOOD     27811.     4782.      724.
19: 0   % .541519E 13       68.19        GOOD     27054.     4976.      779.
19:15   % .310267E 15       66.52        GOOD     26247.     5186.      839.
19:30   % .17777E 17       65.67        GOOD     25387.     5413.      905.
19:45   % .101855E 19       62.66        GOOD     24474.     5657.      979.
20: 0   % .583585E 20       60.55        GOOD     23503.     5923.     1062.
20:15   % .33437E 22       58.37        GOOD     22474.     6212.     1157.
20:30   % .19158E 24       56.17        GOOD     21382.     6529.     1266.
20:45       267.39      53.96        GOOD     20225.     6877.     1394.
21: 0       263.37      51.78        POOR     18998.     7263.     1545.
21:15       259.23      49.65        POOR     17699.     7695.     1728.
21:30       254.82      47.62        POOR     16322.     8183.     1951.
21:45       249.96      45.70        POOR     14864.     8741.     2231.
22: 0       244.41      43.95        POOR     13321.     9387.     2586.
22:15       237.79      42.40        POOR     11690.    10150.     3049.
22:30       229.57      41.07        POOR      9973.    11066.     3664.
22:45       218.81      39.90        POOR      8182.    12188.     4491.
23: 0       204.00      38.57        POOR      6355.    13583.     5578.
23:15       182.80      35.93        POOR      4602.    15277.     6777.



          SATELLITE # 3  OF 3 FOR OBSERVER # 3 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

20: 0       107.49       9.55        GOOD     20542.     7205.      674.
20:15       112.01      12.78        GOOD     20577.     7195.      -40.
20:30       116.70      15.73        GOOD     20615.     7184.      -43.
20:45       121.57      18.33        GOOD     20654.     7173.      -45.
21: 0       126.62      20.52        POOR     20695.     7161.      -47.
21:15       131.81      22.24        POOR     20738.     7149.      -48.
21:30       137.11      23.44        POOR     20781.     7137.      -49.
21:45       142.43      24.09        POOR     20825.     7124.      -50.
22: 0       147.69      24.16        POOR     20870.     7112.      -50.
22:15       152.78      23.65        POOR     20914.     7099.      -51.
22:30       157.60      22.58        POOR     20959.     7086.      -51.
22:45       162.08      20.98        POOR     21004.     7074.      -50.
23: 0       166.14      18.89        POOR     21049.     7061.      -50.
23:15       169.73      16.37        POOR     21094.     7049.      -50.
23:30       172.83      13.48        POOR     21138.     7036.      -50.
23:45       175.43      10.28        POOR     21182.     7024.      -49.



               ATELLITE OBSERVABILITY REPORT

FOR OBSERVER # 4 AT  118 W 0 

PERIOD OF OBSERVATION FROM: 0500  0 / 26 / 1972 
                            TO:0500  12 / 27 / 1972 



          SATELLITE # 1  OF 3 FOR OBSERVER # 4 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0         0.00      19.33        GOOD    275249.    18846.     -106.
18:15         0.00      15.76        GOOD    279959.    18842.      -16.
18:30         0.00      12.18        GOOD    284669.    18839.      -15.
18:45         0.00       8.60        GOOD    289378.    18835.      -15.
19: 0         0.00       5.57        GOOD    294086.    18831.      -14.
19:15         0.00       1.42        GOOD    298793.    18828.      -14.



          SATELLITE # 2  OF 3 FOR OBSERVER # 4 

TIME  COMPASS ELEV   VISIBILITY ALTITUDE  VELOCITY ACCELERATION

18: 0       180.50      85.90        GOOD     18998.     7263.   -32055.
18:15       194.81      82.81        GOOD     17699.     7695.     1728.
18:30       198.17      79.30        GOOD     16323.     8183.     1951.
18:45       197.70      75.45        GOOD     14865.     8741.     2230.
19: 0       193.52      71.35        GOOD     13321.     9387.     2586.
19:15       191.10      66.35        GOOD     11690.    10150.     3049.
19:30       185.58      60.57        GOOD      9973.    11066.     3664.
19:45       178.47      53.27        GOOD      8182.    12188.     4491.
20: 0       169.43      43.40        GOOD      6356.    13583.     5578.
20:15       157.80      29.13        GOOD      4602.    15277.     6777.

Ready



--------
