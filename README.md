# scan_ports

this is a scanner ports tools
-delay int
        Delay between scans in milliseconds (default 100)
  -endPort int
        End port number (default 1024)
  -startPort int
        Start port number (default 1)
  -target string
        Target host (IP or domain)

【for example】
scan_ports.exe -target=192.168.2.131
scan_ports.exe -target=192.168.2.131 -startPort=1 -endPort=10000
scan_ports.exe -target=192.168.2.131 -startPort=1 -endPort=10000 -delay=200
