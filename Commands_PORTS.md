### Mainframe TCP/IP PORTS Commands

| Name | Version | Description | Date |
| ----------- | ----------- | ----------- | ----------- |
| AC | 1.0 | Initial Version | 13th July 2025 |

## TCP/IP PORTS:

#### DISPLAY ALL PORTS (IMPORTANT: May be an extended result)
```
D TCPIP,,NETSTAT,PORTL,MAX=*
```
#### DISPLAY FIRST 50 PORTS
```
D TCPIP,,NETSTAT,PORTL,MAX=50
```
#### DISPLAY SPECIFIC PORT
```
D TCPIP,,NETSTAT,PORTL,PORT=21
```
#### DISPLAY ADDITIONAL INFO FOR AN APPLDATA
```
D TCPIP,TCPIP,NETSTAT,CONN,APPLDATA   
```


[IBM 3.1 Display TCPIP NETSTAT](https://www.ibm.com/docs/en/zos/3.1.0?topic=commands-display-tcpip-netstat)
