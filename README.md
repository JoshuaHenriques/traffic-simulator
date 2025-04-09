# **Traffic Simulator**

Generating multi-protocol packets (TCP/UDP/HTTP/HTTPS) to stress-test server configurations under diverse and variable loads, simulating real-world network conditions to measure response times, error rates, and resource utilization while validating reliability, scalability, and robustness across distributed environments.

_(Work in Progress)_

## **Core Features**

### **Raw Packet Generation**

- **TCP/UDP**:
  - **Randomized Payloads**: Inject unpredictable data (e.g., random strings, binary blobs)
  - **Custom Headers**: Define source/destination IPs, ports, and protocol-specific flags (e.g., TCP SYN/ACK, UDP checksum).
  - **Speed Control**: Adjust transmission rates.
  - **Variable-Sized Packets**

### **HTTP/HTTPS Traffic**

- **Variable-Sized Requests**: Generate HTTP/HTTPS messages with dynamic payloads (e.g., 100B–5MB JSON/XML).
  - Simulate API calls with randomized query parameters or POST bodies.
- **SSL/TLS Support**: Encrypt HTTPS traffic.
- **Rate Limiting**: Throttle requests (e.g., 100 RPS to 10,000 RPS) for load testing.

---
