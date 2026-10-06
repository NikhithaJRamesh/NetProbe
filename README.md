# NetProbe
Network Port Analysis &amp; Server Discovery Suite Team: Logic Link | Domain: Computer Networks &amp; Cybersecurity  NetProbe is a single-file Python tool that combines a multi-threaded TCP port scanner, a LAN host discovery sweep, and a security risk analyzer. It uses only the Python standard library, so there is nothing to install.


Features
    Multi-threaded TCP connect scan with open / closed / filtered detection
    Banner grabbing for open ports (including HTTP Server: headers)
    LAN discovery: sweeps the local /24 subnet and lets you pick a host to scan
    Service identification for 60+ well-known ports
    Risk analysis: each open port is rated HIGH / MEDIUM / LOW / INFO with a remediation tip
    Overall risk score (0-100) per scan
    Auto-saved reports as timestamped .txt files
    Safety prompt that asks for confirmation before scanning public IPs
    Zero dependencies: standard library only

Requirements
    Python 3.6+
    Works on Windows, Linux and macOS
