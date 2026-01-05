# homelab-infra-docs
Infrastructure documentation for a private R&amp;D lab: 20-node GPU cluster protected and powered by a 2.5kW solar array and 4kWh Lithium-Ion storage.
Aurora R&D Lab: Infrastructure Specifications
Physical Layer: Energy & Power Resilience
Solar Array: 2.5kW series-wired array designed for maximum high-voltage efficiency.

Storage: 4kWh Lithium-Ion battery stack.

Redundancy: Hybrid UPS configured for 0ms failover, stress-tested via total grid isolation to ensure zero downtime for critical trading logic.

Compute Layer: Distributed GPU Cluster
Master Node: Dell PowerEdge R740 (Dual Xeon, Headless Linux).

GPU Estate: 20x NVIDIA GTX 1060 6GB (Total VRAM: 120GB).

Orchestration: Custom SSH-based job scheduling and thermal-aware load balancing.

Storage & Virtualization
Hypervisor: Oracle VirtualBox.

NAS: TrueNAS Scale running in a hardened VM with bridged networking.
