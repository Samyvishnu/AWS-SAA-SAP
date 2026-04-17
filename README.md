# AWS-SAA-SAP

As a Technical Program Manager, I've always believed the best way to drive technical programs is to understand the systems deeply enough that you can spot the risk before the engineers flag it.

So I built a tool to force myself to go deeper on AWS.

It's a fully self-contained interactive learning platform — one HTML file, no internet required — that I've been iterating on for the past several weeks. Here's what it's become:


━━━━━━━━━━━━━━━━━━━━━━
📐 WHY I BUILT IT
━━━━━━━━━━━━━━━━━━━━━━

Passing a certification exam and actually understanding a distributed system are two different things. I wanted the latter — the kind of understanding that lets you look at an architecture diagram and immediately see where the single points of failure are, where the cost surprises live, and which design decisions will create operational debt.

━━━━━━━━━━━━━━━━━━━━━━
🔧 WHAT'S INSIDE
━━━━━━━━━━━━━━━━━━━━━━

→ 24-week certification roadmap (CLF → SAA → SAP → Security Specialty) mapped to Bloom's Taxonomy
→ 11 deep-learning modules across every SAP-C02 domain
→ Architecture Simulator — swap services, see tradeoffs in real time
→ 120 real-world incident scenarios rendered in an interactive 4D Three.js engine
→ 3D Network Visualizer with 25 AWS services, live particle flows, and an Explode View
→ Audio Tutor with narrated topics, flashcards, and an exam simulator
→ 140 practice exam questions across CLF-C02, SAA-C03, SAP-C02
→ Reverse Learn mode — hardest scenarios first, drill to root cause

━━━━━━━━━━━━━━━━━━━━━━
💡 THE THING THAT CHANGED HOW I THINK
━━━━━━━━━━━━━━━━━━━━━━

Building the 120 incident scenarios was the most valuable part. I had to research and write things like:

— Why a Redis cluster splits brain when two AZs partition (and why odd-number quorums matter)
— How NAT port exhaustion silently kills Lambda at scale (SNAT port reuse)
— Why CloudTrail tampering is harder than it looks to detect (and how Config catches what CloudTrail misses)
— How DynamoDB hot partitions form under seemingly reasonable access patterns
— Why S3 Cross-Region Replication with DeleteMarkerReplication enabled can wipe your DR bucket

Each scenario forces you through Problem → Root Cause → Fix → Resolution. In the 4D engine, the affected components highlight in real time, inactive nodes fade, and animated flow arrows show exactly which connections are healthy or broken — including bidirectional flows.

For a TPM working on cloud infrastructure programs, this is the mental model you need when a team tells you "we had an incident." You need to already know the failure topology before they explain it.

━━━━━━━━━━━━━━━━━━━━━━
📬 OPEN TO CONNECT
━━━━━━━━━━━━━━━━━━━━━━

If you're working toward AWS certification or building cloud infrastructure programs and want to talk architecture, incident patterns, or how TPMs can develop deeper technical context — I'd love to connect.

#TechnicalProgramManagement #AWS #CloudArchitecture #AWSCertification #SolutionsArchitect #NetworkInfrastructure #LeadershipInTech #LearningInPublic #CloudComputing
