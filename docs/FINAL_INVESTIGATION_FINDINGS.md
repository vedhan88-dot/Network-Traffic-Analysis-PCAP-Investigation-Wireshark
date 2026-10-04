# Network Traffic Analysis & PCAP Investigation
# Final Investigation Findings

## PCAP

`2026-09-11-traffic-analysis-exercise.pcap`

## Primary Internal Host

`10.9.11.135`

## Capture Statistics

- Total packets: 73,779
- Capture duration: approximately 21 minutes 9 seconds

---

# 1. Executive Summary

The PCAP investigation identified suspicious outbound network activity originating from the internal host `10.9.11.135`.

The host generated DNS queries for multiple external domains and subsequently communicated with external IP addresses using HTTP and QUIC.

The investigation identified repeated HTTP GET and POST requests to multiple external destinations. Several HTTP POST requests contained `application/octet-stream` content and substantial File Data.

The observed activity is suspicious and consistent with possible command-and-control or automated malicious network communication.

However, the PCAP evidence reviewed does not independently prove the identity of the malware or confirm that the transmitted data was sensitive information.

---

# 2. Primary Internal Host

The primary internal host identified during the investigation was:

```text
10.9.11.135
