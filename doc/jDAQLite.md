# Procedure of ```int main()```
1. set base address.
2. check firmware at given baseaddress.(0x24:{moduleid[7:0],version[7:0]});
3. define and get all possible parameters
4. check dependencies
5. check exlusivnes
6. evaluate parameters

# Procedure of ```jTDC()```
1. set baseaddress, eventfifo(0xbase8888) and datafifo address(0xbase4444)
2. set jTDC config(0xbase0020)
3. enable all channels
4. read out jTDC properties
5. read out TDC with ```ofstream datfile```
