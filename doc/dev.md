# Serial Commands



```bash
# request own MAC CMD_GET_REQ
02 10 01 00 04 17

-> 77 00 30 DA 18 00
-> 87 00 30 DA 18 00

# set module to "just works" CMD_SET_REQ
# see Proteus Maunual 5.6.1.1 
# Secured connection with LE Legacy security method "Just Works" without bonding
02 11 02 00 0C 02 1F

# restore default settings CMD_FACTORYRESET_REQ
02 1C 00 00 1E

# connect (adapt checksum, XOR) CMD_CONNECT_REQ
02 06 06 00 77 00 30 DA 18 00 87

# send 41 42 43 44 (ABCD) CMD_DATA_REQ
02 04 04 00 41 42 43 44 06

# disconnect CMD_DISCONNECT_REQ
02 07 00 00 05

# scan start CMD_SCANSTART_REQ
02 09 00 00 0B

# scan stop CMD_SCANSTOP_REQ
02 0A 00 00 08

# get devices CMD_GETDEVICES_REQ
02 0B 00 00 09


```

