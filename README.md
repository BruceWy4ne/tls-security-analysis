# tls-security-analysis

Deep analysis of a TLS 1.2 handshake, certificate validation, cipher suite negotiation, ECDHE key exchange, and TLS traffic decryption using Wireshark and SSLKEYLOGFILE.

## Overview

This project analyzes the complete TLS 1.2 connection establishment process between a client and a remote web server. Using Wireshark packet captures, the TLS handshake was inspected step-by-step to understand certificate validation, cipher suite negotiation, ephemeral key exchange, and encrypted application-layer communication.

By exporting TLS session keys through `SSLKEYLOGFILE`, encrypted HTTPS traffic was decrypted and examined to observe HTTP requests, HTTP responses, HTTP/2 traffic, and DNS-over-HTTPS communications.

## Key Skills Demonstrated

* TLS 1.2 Protocol Analysis
* Wireshark Packet Analysis
* Certificate Chain Validation
* Public Key Infrastructure (PKI)
* ECDHE Key Exchange
* Forward Secrecy
* HTTPS Traffic Inspection
* HTTP/2 Analysis
* DNS-over-HTTPS (DoH)
* Network Security Fundamentals

## Tools Used

* Wireshark
* Firefox
* Ubuntu Linux
* TLS 1.2
* SSLKEYLOGFILE
* badssl.com

## Project Highlights

* Captured and analyzed a complete TLS 1.2 handshake
* Examined Client Hello and Server Hello negotiation
* Validated server certificate chains issued by Let's Encrypt
* Identified negotiated cipher suites and cryptographic parameters
* Analyzed ECDHE key exchange used for forward secrecy
* Configured Wireshark to decrypt TLS traffic using exported session keys
* Inspected decrypted HTTP requests and responses
* Investigated DNS-over-HTTPS traffic carried within encrypted TLS sessions

## Screenshots

* Client Hello Analysis
* Server Hello Analysis
* Certificate Chain Inspection
* Client Key Exchange
* TLS Traffic Decryption
* HTTP Request Analysis
* HTTP Response Analysis

## Author

**Rishi Solanki**
M.Eng Cybersecurity Engineering
University of Maryland
