This project demonstrates a complete modernization of GlobalTech Corporation’s network infrastructure. The redesign replaces a failing, flat network with a robust, scalable architecture based on the Cisco Hierarchical Model to ensure high availability and enterprise-grade security.

The Problem (Legacy Environment)

The original network was outdated and hindered organizational growth due to:

Single Points of Failure: No redundancy meant any hardware failure caused total downtime.

Performance Bottlenecks: A flat topology without VLANs led to excessive broadcast traffic and poor performance.

Security Risks: All departments (HR, Sales, IT) shared the same network, and the lack of a firewall or VPN exposed private data.

Scalability Issues: The infrastructure could not easily expand to accommodate new employees or offices.

The Solution (Modernized Architecture)

The new design implements a tiered approach to solve these challenges:

Hierarchical Topology: Using Core, Distribution, and Access layers to separate high-speed switching from policy-based routing and user connectivity.

VLAN Segmentation: Departments are isolated into their own VLANs to enhance security. Critical services—including DNS, Mail, Web, and Database—are protected in a dedicated Server VLAN.

Redundancy: Integrated redundant links ensure that the company remains operational even if a primary router or switch fails.

Network Edge Security: Deployment of a hardware firewall and VPN allows for secure perimeter defense and safe remote access for employees.

Layer 3 Intelligence: Utilization of Layer 3 devices for Inter-VLAN routing, creating a smoother and more manageable data flow.

Key Benefits

Reliability: High availability through redundant paths.

Security: Multi-layer protection and logical isolation of sensitive data.

Flexibility: A modular design that supports future expansion without requiring a network overhaul.

Technologies Used

Cisco Hierarchical Model (Core, Distribution, Access)

VLANs & Inter-VLAN Routing

Redundant Link Implementation

Firewall & VPN Configuration

Network Services (DNS, Web, Database) Management
