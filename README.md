# NETWORKWALKS-CHINENYEPRECIOUS-B084-WK1-Extra-WIRESHARK-NETWORK-TRAFFIC-ANALYSIS

**Project Category:** Cybersecurity \| Network Analysis \| Wireshark \|
SOC Analysis\
**Difficulty:** Beginner\
**Training Platform:** Networkwalks\
**Lab:** Wireshark Lab 3\
**Status:** Completed

## Project Overview

As part of the Networkwalks Wireshark Lab 3 challenge, I completed
practical exercises designed to strengthen my understanding of network
traffic analysis, TCP communication, packet filtering, and the
investigation of potentially suspicious network activities.

This project provided hands-on experience using Wireshark to capture and
examine network packets, apply display filters, and interpret basic
network communication.

## Project Objectives

-   Capture network traffic using Wireshark.
-   Understand how to inspect captured packets.
-   Apply display filters to isolate specific network traffic.
-   Identify TCP connection initiation using SYN flags.
-   Analyze communication between source and destination IP addresses.
-   Investigate network traffic patterns.
-   Develop practical network security monitoring skills.

## Tools and Technologies

-   **Wireshark:** Network protocol analyzer used to capture and inspect
    network packets.
-   **Windows PC:** Host operating system.
-   **TCP/IP:** Network communication protocol suite.
-   **Wireshark Display Filters:** Used to isolate and examine specific
    packets.

## Practical Exercises and Findings

### Task 1: Capturing Network Traffic

**Objective:** Capture network traffic and determine the total number of
packets recorded by Wireshark.

**Procedure:**

1.  Opened Wireshark on the Windows PC.
2.  Selected the active Wi-Fi network interface.
3.  Started capturing network traffic.
4.  Allowed the capture to run.
5.  Checked the total packet count.

**Result:** Wireshark successfully captured **309 packets**.

**Screenshot:**

### Task 2: Filtering TCP SYN Packets

**Objective:** Filter the captured traffic to display packets with the
TCP SYN flag set.

**Display Filter Used:**

``` wireshark
tcp.flags.syn == 1
```

**Procedure:**

1.  Entered the TCP SYN display filter into Wireshark.
2.  Applied the filter to the captured traffic.
3.  Examined the filtered packets.
4.  Checked the number of packets displayed.

**Result:** The filter returned **73 packets** out of the original 309
captured packets.

This exercise helped me understand how TCP SYN flags are used during
connection establishment and how Wireshark display filters can isolate
specific network activities.

**Screenshot:*
## Additional Challenge Evidence

The following links provide additional screenshots documenting the
exercises and findings from the Wireshark challenge. They are listed in
the order shared.

1.  [View screenshot
    1](https://drive.google.com/file/d/1S7Oiqy67cMJC_3imZbeXsgC6mRH_bf3T/view?usp=sharing)
2.  [View screenshot
    2](https://drive.google.com/file/d/1aUrK32TnTcHLy7GnFFESAHP3ElKr-WIU/view?usp=sharing)
3.  [View screenshot
    3](https://drive.google.com/file/d/1aOdGLiCM2CzgrVTxc9tTFDhTVhhwjli8/view?usp=sharing)
4.  [View screenshot
    4](https://drive.google.com/file/d/173rvhwGzP-Nvi0BxrsP0B-UL7pb0LQbf/view?usp=sharing)
5.  [View screenshot
    5](https://drive.google.com/file/d/13janFb0Yi_GN49AHNGq_irhLyWvWpaWH/view?usp=sharing)
6.  [View screenshot
    6](https://drive.google.com/file/d/1swuYaLHCULiPf964Bkc8X5pH1Av0ByGc/view?usp=sharing)
7.  [View screenshot
    7](https://drive.google.com/file/d/1iKj2WBcg6v5PDMoS-kBm8umx2nu-gTc_/view?usp=sharing)
8.  [View screenshot
    8](https://drive.google.com/file/d/1VZ9D3jCrO_xd-1avDV-muG7oj6TfHPBG/view?usp=sharing

## Key Learning Outcomes

Through this practical challenge, I strengthened my understanding of:

-   Network traffic capture and monitoring.
-   Wireshark's packet analysis interface.
-   Source and destination IP addresses.
-   TCP communication and SYN flags.
-   Applying Wireshark display filters.
-   Inspecting and interpreting network packets.
-   Identifying and investigating network traffic patterns.
-   Practical cybersecurity investigation techniques.

## Conclusion

Completing this Wireshark challenge was an important step in
strengthening my practical cybersecurity and network analysis skills.

It provided hands-on experience with packet capture, traffic filtering,
and network protocol analysis using Wireshark. It also improved my
understanding of how network traffic analysis supports security
monitoring, troubleshooting, and incident investigation.

I look forward to building on these skills through additional hands-on
cybersecurity labs and SOC analyst projects.

**Project Status:** Completed\
**Training Platform:** Networkwalks
