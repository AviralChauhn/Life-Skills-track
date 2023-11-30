# Firewall Overview

A **firewall** is a network security device, either hardware or software. It serves as a protective barrier, monitoring all incoming and outgoing traffic to safeguard user devices from malicious activities and ensure privacy.

## Firewall Functions

The firewall functions by:

- Checking if incoming traffic is desired by the user.
- Blocking incoming traffic or files from unexpected sources.
- Verifying the source of traffic through an access list.

## Access List

An **access list** is a text-based document containing names of allowed sources that can share data with the user. The firewall checks if the source of incoming or outgoing data is present in the access list. If not, it immediately blocks the connection request, preventing unauthorized access to the user's system.

## Types of Firewalls

### 1. Packet Filtering Firewall

- Filters data based on sender's and receiver's IP addresses.
- Fast and reliable, but not the safest as it only filters based on IP addresses, not content.

### 2. Application/Proxy Firewall

- Provides better protection than packet filtering.
- Requests are passed to a proxy device, which fetches the desired data from the internet.
- Slower than packet filtering due to multiple steps involved.

### 3. Hybrid Firewall

- The most secure type, combining features of application/proxy and packet filtering firewalls.
- Both types are connected in series to offer hybrid firewall features.

## Conclusion

In conclusion, a firewall is a crucial component for internet access, ensuring the protection of user and data from unauthorized access and malicious activities.

## Rerferences
- https://www.youtube.com/playlist?list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6
- https://www.geeksforgeeks.org/introduction-of-firewall-in-computer-network/
- https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/
