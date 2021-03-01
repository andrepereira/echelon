# echelon
To capture network traffic passing by a interface and analise with the Isolation Forest machine learning algorithm to detect outliers.

This can be used to detect suspicious activity in the network and show real time alerts in security applications.

Early stage under heavy development.
Using Go (Golang) and the libs:
- libpcap C Lib to intercept network packages
- Go Packet to intercept network packages using libpcap: github.com/google/gopacket
- Golearn ML Lib: (https://github.com/sjwhitworth/golearn)

With code from NanoDano
https://www.devdungeon.com/blogs/nanodano