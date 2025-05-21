# NetNip

![Go](https://img.shields.io/badge/Go-1.18%2B-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/status-early%20stage-lightgrey)

**NetNip** is a lightweight and easy-to-understand **TCP port scanner** written in Go. Perfect for learning networking, concurrency, and systems programming basics.

---

## Features

- Scan a hostname or IP address for **open TCP ports**
- Default port range: `1-1024`
- Simple and fast
- Easy to customize or extend
- Great for learning and basic network audits

---

## Use Cases

- Learn how TCP port scanning works  
- Identify which services are running on a local or remote host  
- System administration and port auditing  
- Security testing  
- Penetration testing basics and ethical hacking  
- Build your understanding of networking and Go's `net` package  

---

## How It Works

A port is like a “door” on a computer that services use to talk to the outside world.

This scanner:

1. Takes a domain or IP (like `scanme.nmap.org`)
2. Loops through a range of ports
3. Tries to connect to each port using TCP
4. If a connection is successful, the port is marked **open**

---

## Ethical Usage Only

> **Warning:** Only scan hosts that you own or have **explicit permission** to scan. Unauthorized scanning may violate laws, ISP rules, or terms of service.

This tool is strictly for:

- Education  
- Ethical testing  
- Authorized auditing  

---

## Getting Started

### Requirements

- Go 1.18 or later  
- Internet connection (if scanning remote hosts)  

### Run It

````bash
go run port_scanner.go
````

## Planned Features / Ideas

- Concurrency (faster scanning using goroutines)  
- CLI flags for host, port range, and timeout  
- Output formatting (JSON, CSV)  
- Service detection on common ports  
- Optional UDP scanning (advanced)  

---

## License

This project is licensed under the **MIT License**. Feel free to use, share, and modify it.

---

## Disclaimer

This is a simple educational project and **should not be used maliciously**. The developer is **not responsible** for any misuse.

---

## Contributing

Pull requests are welcome! If you have ideas to improve this tool or want to practice contributing to open-source Go projects, feel free to **fork** and submit a **PR**.

---

## ChatGPT

This `README.md` was created using ChatGPT. It has been reviewed for accuracy, but if you find any issues or have improvements, feel free to contribute.
