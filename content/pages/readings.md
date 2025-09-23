---
content_type: page
description: This section contains the background readings, the assigned readings,
  and the optional readings.
draft: false
learning_resource_types:
- Readings
ocw_type: CourseSection
title: Readings
uid: 065ed03c-b61c-e97b-68cc-671caa24bb9a
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
The readings listed on this page are in three parts. First come the background readings. You will find them useful to get up to speed. Then come the assigned readings. Finally, we list several papers as optional readings, for you to learn more about specific topics. The schedule provides hints on when any given optional reading might be useful. All papers are named by shorthand names such as CK74.

## Background (will not be explicitly discussed in class)

**\[SRC84\]** Saltzer, J., D. Reed, and D. Clark. "End-to-end Arguments in System Design." {{% resource_link "feeaf3d9-44ee-4cf1-a7f7-80a7b2010513" "*ACM Transactions on Computer Systems (TOCS)*" %}} 2, no. 4 (1984): 195-206. (This paper is covered in 6.033.)

Ethernet paper.

**\[L0\]** Balakrishnan, H. "Single-link Communication." 6.829 Computer Networks Lecture Notes, Fall 2002. (Read this before or soon after first lecture.) ({{% resource_link "f3e7d4d9-bee7-f8d9-9ad0-d4b3cbae3e55" "PDF" %}})

## Assigned Readings (by Topic Area)

### Part I. Internetworking and Routing

**Internet Architecture**

**\[CK74\]** Cerf, V., and {{% resource_link "846233e1-09d2-438c-887d-55c374cf0da3" "R. Kahn" %}}. "A Protocol for Packet Network Interconnection." {{% resource_link "e30ac617-8065-4d4c-8d0b-492d1ade54c2" "*IEEE Transactions on Communications*" %}} COM-22 (1974): 637-648.

**\[Cla88\]** Clark, D. "Design Philosophy of the DARPA Internet Protocol." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (August 1988): 106-114. Stanford, CA.

**\[Hin96\]** Hinden, R. "IP Next Generation Overview." *Comm of the ACM* 39, no. 6 (June 1996): 61-71.

**Unicast IP Forwarding and Routing**

**\[BCDP97\]** Brodnik, A., S. Carlsson, M. Degermark, and S. Pink. "{{% resource_link "b0acb404-74c3-443a-ba68-69b6685a3b2e" "Small Forwarding Tables for Fast Routing Lookups" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (September {{% resource_link "1c889d57-9000-4914-a405-ef3b20054518" "1997" %}}). Cannes, France.

**\[L4\]** Balakrishnan, H. "Wide-area Unicast Routing." 6.829 Computer Networks Lecture Notes, Fall 2002. ({{% resource_link "479e67f0-3ae6-82ec-5886-7664687a926e" "PDF" %}})

**Internet Routing in-the-Wild (Measurement)**

**\[Pax97\]** Paxson, V. "End-to-End Routing Behavior in the Internet." *IEEE/ACM Transactions on Networking* 5, no. 5 (October 1997): 601-615.

**Big Fast Routers**

**\[P+98\]** Partridge, C., et al. "A 50 Gb/s IP Router." *IEEE/ACM Transactions on Networking* 6, no. 3 (June 1998): 237-248.

**\[McK96\]** McKeown, N., M. Izzard, A. Mekkittikul, W. Ellersick, and M. Horowitz. "The Tiny Tera: A Packet Switch Core." *Proc Hot Interconnects* V (August 1996). Stanford University.

**Security Issues in the Internet Architecture**

**\[Bel89\]** Bellovin, Steven M. "Security Problems in the TCP/IP Protocol Suite ({{% resource_link "f6722fad-5f9e-4d56-bdd4-c000a2952f94" "PDF" %}})." *Computer Communications Review* 2, no. 19 (April 1989): 32-48.

**\[Sno+01\]** Snoeren, A., C. Partridge, L. Sanchez, C. Jones, F. Tchakountio, S. Kent, and T. Strayer. "{{% resource_link "14416888-a445-46e0-9ae9-b6d078c33aca" "Hash-based IP Traceback" %}}." *Proc ACM SIGCOMM* (August {{% resource_link "124c8864-1430-4e4a-8d96-f2dc2d146238" "2001" %}}). San Diego, CA.

**Robustness**

**\[ASSW02\]** Anderson, T., S. Shenker, I. Stoica, and D. Wetherall. "Towards More Robust Internet Protocols." (July 2002).

## Part II. Resource Management

**End-to-End Congestion Control**

**\[JK88\]** Jacobson, V., and M. Karels. "Congestion Avoidance and Control." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (August 1988). Stanford, CA.

**\[CJ89\]** Chiu, and D. M., and R. Jain. "Analysis of the Increase and Decrease Algorithms for Congestion Avoidance in Computer Networks." *Computer Networks and ISDN Systems* 17 (1989): 1-14.

**Router-Assisted Congestion Control, Active Queue Management, and Scheduling**

**\[FJ93\]** {{% resource_link "ef8b42da-b99a-4e08-ac82-61b2e61273ea" "Floyd, S." %}}, and V. Jacobson. "Random Early Detection Gateways for Congestion Avoidance." *IEEE/ACM Transactions on Networking* 1, no. 4 (August 1993): 397-413.

**\[KHR02\]** Katabi, D., M. Handley, and C. Rohrs. "{{% resource_link "d032ed62-0b21-44fe-a151-2ac1f68fe6c5" "Congestion control for high bandwidth-delay product networks" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**\[DKS90\]** Demers, A., S. Keshav, and {{% resource_link "3f1583bf-333c-4206-87c5-63747bda88ad" "S. Shenker" %}}. "Analysis and Simulation of a Fair Queueing Algorithm." *Internetworking: Research and Experience* 1, no. 1 (1990): 3-26. (If you like, you may also read the slightly older SIGCOMM '89 version.)

**\[SSZ98\]** {{% resource_link "bbf5c173-deb1-4d13-9395-f626f5f5fc65" "Stoica, I." %}}, {{% resource_link "3f1583bf-333c-4206-87c5-63747bda88ad" "S. Shenker" %}}, and {{% resource_link "52c64165-aa9d-4d4a-af2c-73a4810e0609" "H. Zhang" %}}. "Core - Stateless Fair Queueing: Achieving Approximately Fair Allocations in High Speed Networks." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (September {{% resource_link "6b9e59f5-9783-4a1b-adab-71f879bcc718" "1998" %}}). Vancouver, Canada. ASIN: B0006R9W38.

**Modeling and Measurement**

**\[JD02\]** Jain, M., and C. Dovrolis. "{{% resource_link "f3527a49-b207-4b90-95ec-11feb82d2a24" "End-to-end Available Bandwidth: Measurement Methodology, Dynamics, and Relation with TCP Throughput" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**\[WGJPS02\]** Willinger, W., R. Govindan, S. Jamin, V. Paxson, and S. Shenker. "{{% resource_link "ebc2a784-6fda-4550-a266-aa084c3664eb" "Scaling phenomena in the Internet: Critically examining criticality" %}}." *Proc Natl Acad Sci USA* 99, supplement 1 (February 19, 2002): 2573-2580.

**\[SPW02\]** Staniford, S., V. Paxson, and N. Weaver. "{{% resource_link "96080be8-24d3-4d61-baff-7b2a388a6022" "How to 0wn the Internet in Your Spare Time" %}}." *Proc USENIX Security Symp* (August 2002). San Francisco, CA.

**Adaptive Applications and Internet QoS**

**\[CT90\]** Clark, D., and D. Tennenhouse. "Architectural Consideration for a New Generation of Protocols." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (September 1990). Philadelphia, PA.

**\[BSR99\]** Balakrishnan, H., S. Seshan, and H. Rahul. "An Integrated Congestion Management Architecture for Internet Hosts." *Proc ACM SIGCOMM* (September {{% resource_link "7c859d6e-0ad0-4ffd-9699-86e358bc7eb0" "1999" %}}). Cambridge, MA.

**\[She95\]** Shenker, S. "Fundamental Design Issues for the Future Internet." *IEEE Journal on Selected Areas in Communications* 13, no. 7 (September 1995): 1176-1188.

**\[CSZ92\]** Clark, D., {{% resource_link "efd127cd-b4c5-473f-a640-9ecf02817805" "S. Shenker" %}}, and L. Zhang. "Supporting Real-Time Applications in an Integrated Services Packet Network: Architecture and Mechanisms." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*SIGCOMM*" %}} *'92 (* August 1992). Baltimore, MD.

**\[CF98\]** Clark, D., and W. Feng. "Explicit Allocation of Best-Effort Packet Delivery Service." *IEEE/ACM Transactions on Networking* 6, no.4 (August 1998): 362-373.

## Part III. Network Services

**Wireless/Mobile Networking**

**\[BMJ+98\]** Broch, J., D. Maltz, {{% resource_link "6d213387-7340-4b55-9906-fa5627efb69e" "D. Johnson" %}}, Y. C. Hu, and J. Jetcheva. "A Performance Comparison of Multi-Hop Wireless Ad Hoc Routing Protocols." *Proc ACM MOBICOM* (August 1998). Dallas, TX.

**\[IGE00\]** Intanagonwiwat, C., {{% resource_link "8ab26baa-5ebf-4d0b-bcc2-e1756c8f6698" "R. Govindan" %}}, and {{% resource_link "03ba2a3c-e745-4987-9863-2eaa6f762d06" "D. Estrin" %}}. "{{% resource_link "a1f48ba9-30b5-40ca-ad96-3dc0cae8b8b8" "Directed diffusion: A scalable and robust communication paradigm for sensor networks" %}}." *Proc ACM MOBICOM* (August 2000). Boston, MA.

**\[BDSZ94\]** Bharghavan, V., A. Demers, {{% resource_link "3f1583bf-333c-4206-87c5-63747bda88ad" "S. Shenker" %}}, and L. Zhang. "MACAW: A Media Access Protocol for Wireless LANs." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (September 1994): 212-225. London, UK.

**\[BSK95\]** Balakrishnan, H., {{% resource_link "e49759fa-254a-4591-b3e7-3254d6dd90b3" "S. Seshan" %}}, and {{% resource_link "a38255c6-48c6-41fb-9185-17fb1779d8a1" "R. Katz" %}}. "Improving Reliable Transport and Handoff Performance in Cellular Wireless Networks." *ACM Wireless Networks* 1, no. 4 (December 1995).

**Naming: DNS**

**\[JSBM01\]** Jung, J., E. Sit, H. Balakrishnan, and R. Morris. "DNS Performance and the Effectiveness of Caching." *Proc ACM SIGCOMM Internet Measurement Workshop* (November 2001). San Francisco, CA. ({{% resource_link "8389509f-d721-4949-a62c-f6f3657539eb" "PDF" %}})

**Peer-to-Peer Networking, Distributed Hash Tables**

**\[SMKKB01\]** {{% resource_link "413c2fa2-63b2-4a9a-872a-dfda4a36e96f" "Stoica, I." %}}, R. Morris, D. Karger, M. Kaashoek, and H. Balakrishnan. "Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August {{% resource_link "124c8864-1430-4e4a-8d96-f2dc2d146238" "2001" %}}). San Diego, CA.

**\[BKKMS03\]** ———. Looking Up Data in P2P Systems, *Comm. of the ACM* (February 2003).

**\[CSWH00\]** Clarke, I., O. Sandberg, B. Wiley, and T. Hong. "Freenet: A Distributed Anonymous Information Storage and Retrieval System." *Proc ICSI Workshop on Design Issues in Anonymity and Unobservability* (July 2000). Berkeley, CA.

**Overlay Routing**

**\[ABKM01\]** {{% resource_link "fe036e24-a9ce-44af-b1e6-26c70a8be512" "Andersen, D." %}}, H. Balakrishnan, M. Kaashoek, and R. Morris. "Resilient Overlay Networks." *Proc 18th ACM SOSP* (October 2001). Banff, Canada.

**\[Sto+02\]** {{% resource_link "413c2fa2-63b2-4a9a-872a-dfda4a36e96f" "Stoica, I." %}}, D. Adkins, S. Zhuang, S. Shenker, and S. Surana. "{{% resource_link "c2516ab0-2c91-45a1-9d77-9aab93a2e42e" "Internet Indirection Infrastructure" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**Multicast**

**\[MS97\]** Maufer, T., and C. Semeria. "Introduction to IP Multicast Routing." Internet-Draft, July 1997.

**\[F+97\]** {{% resource_link "1d6bef83-85b3-42f9-b848-7ffcda9e9100" "Floyd, S." %}}, V. Jacobson, C. Liu, S. McCanne, and L. Zhang. "A Reliable Multicast Framework for Light-Weight Sessions and Application Level Framing." *IEEE/ACM Transactions on Networking* (1997).

**Optional Additional Readings and References**

**\[LABJ00\]** Labovitz, C., A. Ahuja, A. Bose, and F. Jahanian. "Delayed Internet Routing Convergence." *Proc* {{% resource_link "b0fbbd76-726c-4da6-a3fe-0b7edcbc88b2" "*ACM SIGCOMM*" %}} (September {{% resource_link "d50ff54b-e376-4837-befe-42bdf9c07638" "2000" %}}): 175-187. Stockholm, Sweden.

**\[Nor00\]** Norton, W. "Internet Service Providers and Peering." 2000.

**\[BV01\]** Baboescu, F., and G. Varghese. "Scalable Packet Classification." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August {{% resource_link "124c8864-1430-4e4a-8d96-f2dc2d146238" "2001" %}}). San Diego, CA.

**Network Protection**

**\[SWKA00\]** {{% resource_link "522cd564-77ef-4f37-aa32-ad80c89a8c97" "Savage, S." %}}, {{% resource_link "cbd1e627-f073-4f0d-a9e0-74528eefde2d" "D. Wetherall" %}}, {{% resource_link "38480b55-67d4-4544-9fa2-f40e6dfa1218" "A. Karlin" %}}, and {{% resource_link "66efbdaa-2c93-4a20-ab41-eed8623b51f3" "T. Anderson" %}}. "Practical Network Support for IP Traceback." *Proc ACM SIGCOMM* September {{% resource_link "a67dfdb4-2eb0-4e5b-a579-ed742f629145" "2000" %}}. Stockholm, Sweden. ({{% resource_link "a67dfdb4-2eb0-4e5b-a579-ed742f629145" "PDF" %}})

**Reliable Transport and Congestion Control**

**\[FF96\]** Floyd, S., and K. Fall. "A Simulation Comparison of Tahoe, Reno, and SACK TCP." *ACM SIGCOMM CCR* (1996).

**\[FF99\]** {{% resource_link "c3a84e59-408d-4911-8230-af98b059308e" "Floyd, S." %}}, and K. Fall. "{{% resource_link "5bca3751-ae4d-4cf6-b1b7-47c136cdc87f" "Promoting the Use of End-to-End Congestion Control in the Internet" %}}." *IEEE/ACM Transactions on Networking* 7, no. 4 (August 1999): 458-472.

**\[RJ90\]** Ramakrishnan, K. K., and R. Jain. "A Binary Feedback Scheme for Congestion Avoidance in Computer Networks." {{% resource_link "feeaf3d9-44ee-4cf1-a7f7-80a7b2010513" "*ACM Transactions on Computer Systems (TOCS)*" %}} 8, no. 2 (May 1990): 158-181.

**\[FHPW01\]** Floyd, S., M. Handley, J. Padhye, and J. Widmer. "Equation-Based Congestion Control for Unicast Applications." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August {{% resource_link "d50ff54b-e376-4837-befe-42bdf9c07638" "2000" %}}). Stockholm, Sweden. ({{% resource_link "b4e011b4-73ec-42a6-b8b4-7dd62f49870d" "PDF" %}})

**\[BB01\]** Bansal, D., and H. Balakrishnan. "Binomial Congestion Control Algorithm." *Proc IEEE INFOCOM* (April 2001). Anchorage, AK.

**\[SEW01\]** Spring, N., D. Ely, D. Wetherall, S. Savage, and T. Anderson. "Robust ECN Signaling." *Proc International Conf on Network Protocols* (November 2001). Riverside, CA.

**Unicast Routing**

**\[Huitema96\]** Huitema, C. *Routing in the Internet*. Upper Saddle River, NJ: Prentice Hall, January 15, 2000. ISBN: 0130226475. (Search for Huitema on the Prentice Hall site.)

**\[LMJ97\]** Labovitz, C., R. Malan, and F. Jahanian. "{{% resource_link "7b132b84-f819-4890-bd84-c1a31918f544" "Internet Routing Instability" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (September {{% resource_link "1c889d57-9000-4914-a405-ef3b20054518" "1997" %}}). Cannes, France.

**\[Stewart99\]** Stewart, J. *BGP4 Inter-Domain Routing in the Internet*. Reading, MA: Addison-Wesley, January 1999. ISBN: 0201379511.

**\[Tsu88\]** Tsuchiya, P. "The Landmark Hierarchy: A New Hierarchy for Routing in Very Large Networks." *Proc ACM SIGCOMM* (August 1988): 35-42. Stanford, CA.

**Adaptive and Network-Aware Applications**

**\[PM95\]** {{% resource_link "5756eef2-2f2d-442c-adbc-9f7799c0b243" "Padmanabhan, V." %}}, and J. Mogul. "Improving HTTP Latency." *Computer Networks and ISDN Systems* 28 (December 1995): 25-35.

**\[RHE99\]** Rejaie, R., {{% resource_link "9a5bf85b-e8b5-495a-a952-5837983565ec" "M. Handley" %}}, and {{% resource_link "03ba2a3c-e745-4987-9863-2eaa6f762d06" "D. Estrin" %}}. "{{% resource_link "2de067b5-7a51-4a42-a5fc-3b205be0cab8" "Quality Adaptation for Congestion Controlled Video Playback over the Internet" %}}." {{% resource_link "7c859d6e-0ad0-4ffd-9699-86e358bc7eb0" "*Proc ACM SIGCOMM*" %}} (September 1999).

**Traffic Engineering, Flow Modeling**

**\[Elw01\]** Elwalid, A., C. Jin, S. Low, and I. Widjaja. "MATE: MPLS Adaptive Traffic Engineering." *Proc IEEE INFOCOM* (2001). Anchorage, AK.

**\[EV02\]** Estan, C., and G. Varghese. "{{% resource_link "0e481bfa-c54f-4c80-9550-41c8ca4b858c" "New directions in traffic measurement and accounting" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**Multicast Routing/Transport**

**\[DC90\]** Deering, S., and {{% resource_link "9c5e11c2-716a-4a0a-882b-37be74ee34ee" "D. Cheriton" %}}. "Multicast Routing in Datagram Internetworks and Extended LANs." {{% resource_link "feeaf3d9-44ee-4cf1-a7f7-80a7b2010513" "*ACM Transactions on Computer Systems (TOCS)*" %}} 8, no. 2 (May 1990): 85-110.

**\[DE+94\]** Deering, S., {{% resource_link "03ba2a3c-e745-4987-9863-2eaa6f762d06" "D. Estrin" %}}, D. Farinacci, V. Jacobson, C. G. Liu, and L. Wei. "An Architecture for Wide-Area Multicast Routing." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (September 1994). London, UK.

**\[HC99\]** Holbrook, H., and D. Cheriton. "IP Multicast Channels: EXPRESS Support for Large-scale Single-source Applications." *Proc* {{% resource_link "717e6cd9-d1ea-4025-9a81-dd24505ef49a" "*ACM SIGCOMM*" %}} (September {{% resource_link "7c859d6e-0ad0-4ffd-9699-86e358bc7eb0" "1999" %}}). Cambridge, MA.

**\[MJV96\]** McCanne, S., V. Jacobson, and {{% resource_link "799efc6b-7c0c-4246-8055-038f15c06896" "M. Vetterli" %}}. "Receiver-driven Layered Multicast." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (August 1996). Stanford, CA.

**\[Pap98\]** Papadopoulos, C. "{{% resource_link "bd44d921-226f-4af8-b081-4e3f79cf6f7f" "An Error Control Scheme for Large-Scale Multicast Applications" %}}." *Proc IEEE INFOCOM '98* (March 1998). San Francisco, CA.

**\[BTW94\]** Turletti, T., and I. Wakeman. "Scalable Feedback Control for Multicast Video Distribution in the Internet." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (September 1994). {{% resource_link "6754b276-738e-4f53-bad6-40260a21fbbc" "London" %}}, UK.

**Wireless Protocols**

**\[Joh96\]** {{% resource_link "6d213387-7340-4b55-9906-fa5627efb69e" "Johnson, D." %}} "Scalable Support for Transparent Mobile Host Internetworking." Chapter 3 in *Mobile Computing.* Edited by T. Imielinski and H. Korth. Kluwer Academic Publishers, 1996, pp. 103-128.

**\[SB00\]** Snoeren, A., and H. Balakrishnan. "An End-to-End Approach to Host Mobility." *Proc* {{% resource_link "b03b4f9b-3de4-4d06-b83e-2281da40fea3" "*ACM MOBICOM*" %}} (August 2000). Boston, MA.

**\[She96\]** Shepard, T. J. "A Channel Access Scheme for Large Dense Packet Radio Networks." *Proc ACM SIGCOMM* (August 1996). Stanford, CA.

**\[J+01\]** Li, J., C. Blake, D. De Couto, H. Lee, and R. Morris. "Capacity of Wireless Ad Hoc Networks." *Proc* {{% resource_link "5a7a74e2-e873-4306-b676-51fb3a31b468" "*ACM MOBICOM*" %}} (July 2001). Rome, Italy.

**\[CJBM01\]** Chen, B., K. Jamieson, H. Balakrishnan, and R. Morris. "Span: An Energy-Efficient Coordination Algorithm for Topology Maintenance in Ad Hoc Wireless Networks." *Proc* {{% resource_link "5a7a74e2-e873-4306-b676-51fb3a31b468" "*ACM MOBICOM*" %}} (July 2001). Rome, Italy.

## Naming

**\[MD88\]** Mockapetris, P., and K. Dunlap. "Development of the Domain Name System." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (August 1988). {{% resource_link "d8c0ba30-6c18-45f2-b2e1-6a0c96f85948" "Stanford" %}}, CA.

## Web Caching

**\[FCAB98\]** Fan, L., P. Cao, J. Almeida, and A. Broder. "{{% resource_link "98a5e50e-5091-4bca-8324-80ae6273fb99" "Summary Cache: A Scalable Wide-Area Cache Sharing Protocol" %}}." {{% resource_link "0d0034d6-6a94-4296-bf56-4737c88b28f0" "*Proc SIGCOMM '98*" %}} (September 1998): 254-265. Vancouver, Canada.

## Introducing New Services: Overlays v. Active Networks

**\[W99\]** {{% resource_link "cbd1e627-f073-4f0d-a9e0-74528eefde2d" "Wetherall, D." %}} "Active network vision and reality: Lessons from a capsule-based system." *Proc* {{% resource_link "ea0335de-da03-4086-b6e2-c8f000f0fae4" "*17th SOSP*" %}} December 1999. Kiawah Island, SC.

**Modeling and Measurement**

**\[Pax97\]** Paxson, V. "{{% resource_link "ac335600-c5fc-40d9-9d7d-ccf62eb74a14" "End-to-End Internet Packet Dynamics" %}}." *Proc* {{% resource_link "4c76f10e-b074-4377-801f-c6eb37f907f3" "*ACM SIGCOMM*" %}} (September 1997): 139-152. Cannes, France.

**\[Bol93\]** Bolot, J. C. "End-to-End Packet Delay and Loss Behavior in the Internet." *Proc* {{% resource_link "777deaad-8462-472d-b107-418369c86eb4" "*ACM SIGCOMM*" %}} (August 1993). San Francisco, CA.

**\[LTWW94\]** Leland, W. E., M. S. Taqqu, W. Willinger, and D. V. Wilson. "On the Self-Similar Nature of Ethernet Traffic." *IEEE/ACM Transactions on Networking* 2, no. 1 (February 1994): 1-15.

Paper on Topology Modeling.