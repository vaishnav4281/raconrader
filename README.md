# ReconRadar

<p align="center">
  <h3 align="center">Enterprise Domain Intelligence & OSINT Platform</h3>
  <p align="center">
    Analyze • Investigate • Discover • Secure
  </p>
</p>

---

## 🚀 Overview

**ReconRadar** is a modern **Domain Intelligence, OSINT, and Security Analysis Platform** built to provide deep visibility into the infrastructure, reputation, security posture, and technology stack of internet-facing domains.

Instead of manually using multiple security tools, Raccoon Radar aggregates intelligence from numerous sources into a **single unified dashboard**, allowing security researchers, penetration testers, SOC analysts, bug bounty hunters, developers, and IT teams to perform comprehensive reconnaissance with one scan.

Every scan generates a detailed security report, calculates an overall security score, stores scan history for authenticated users, and supports bulk domain analysis for enterprise-scale investigations.

---

# ✨ Key Features

### 🔐 Authentication & User Management

* JWT Authentication
* Secure Login & Registration
* Password Hashing
* User Dashboard
* Persistent Scan History
* PostgreSQL Database
* Prisma ORM

---

### 🌍 Domain Intelligence

Analyze any public domain and retrieve:

* Domain Registration Information
* Domain Age
* Registrar Details
* Name Servers
* IP Address
* ISP / ASN
* Country & Geolocation

---

### 📊 Security Dashboard

Every scan generates an executive security summary containing:

* 🟢 Overall Security Score
* 🚨 Risk Level
* 📈 Health Breakdown
* ✅ Safe Checks
* ⚠️ Warnings
* ❌ Critical Findings
* 💡 Security Recommendations

---

# 🔍 Scan Modules

Users can enable individual modules or execute a complete scan.

---

# 📌 Summary

Provides an overall security overview by correlating all scan results into a single report.

### Information Provided

* Overall Score
* Security Rating
* Health Breakdown
* Safe / Warning / Critical Checks
* Key Findings
* Security Recommendations

---

# 🌐 Core Analysis

Collects essential domain information.

### Information Provided

* Domain Name
* IP Address
* Domain Age
* Registration Date
* Expiration Date
* Registrar
* ISP / ASN
* Country
* Geolocation

---

# 🛡️ Security Intelligence

Evaluates the trustworthiness of the infrastructure.

### Information Provided

### 🚦 Risk Score

Overall infrastructure reputation score.

### 🔒 VPN Detection

Detects whether the IP belongs to a VPN provider.

**Useful for**

* Infrastructure attribution
* Fraud detection
* Threat hunting

---

### 🕵️ Proxy Detection

Detects anonymous or public proxies.

**Useful for**

* Identifying anonymized infrastructure
* Detecting hidden origin servers

---

### 🧅 Tor Node Detection

Checks whether the IP belongs to the Tor Network.

**Useful for**

* Anonymous infrastructure detection
* Threat intelligence

---

### 🤖 Bot Traffic Probability

Estimates automated traffic likelihood.

**Useful for**

* Bot detection
* Scanner detection
* Automated abuse monitoring

---

### 🚨 Abuse Reports

Checks publicly reported abuse databases.

Includes

* Spam
* Malware
* Phishing
* Brute Force
* Abuse History

---

### 🚫 DNS Blacklist Status

Checks DNSBL reputation.

Useful for detecting:

* Spam Infrastructure
* Blacklisted Servers
* Poor Reputation

---

# 🌎 Subdomain Enumeration

Discovers publicly available subdomains.

### Includes

* Active Subdomains
* Hidden Services
* Additional Attack Surface
* Asset Discovery

---

# 🦠 VirusTotal Security Analysis

Aggregates security intelligence from VirusTotal.

### Includes

* Malicious Detections
* Suspicious Detections
* Harmless Detections
* Undetected Vendors
* Reputation Score
* Community Votes
* Categories
* Passive DNS Information

---

# 📝 Metadata Analysis

Extracts publicly available website metadata.

### Includes

* Website Title
* Meta Description
* Canonical URL
* Language
* OpenGraph Metadata
* Structured Data
* Social Metadata
* Content Completeness
* Technology Metadata

---

# 🌍 Extended DNS Records

Performs complete DNS enumeration.

### Includes

### A Records

IPv4 Addresses

### AAAA Records

IPv6 Addresses

### MX Records

Mail Servers

### NS Records

Authoritative Name Servers

### TXT Records

* SPF
* Verification Records
* Ownership Validation
* Third-party Integrations

### SOA Record

DNS Zone Administration

### CAA Records

Authorized Certificate Authorities

---

# 📧 Email Security

Analyzes email authentication.

### Includes

### SPF

Authorized Mail Servers

### DMARC

Email Authentication Policy

### DKIM

DomainKeys Identification

### BIMI

Brand Indicators for Message Identification

### Security Score

Overall Email Security Rating

### Recommendations

Security Improvements

---

# 🔒 SSL/TLS Analysis

Performs certificate inspection.

### Includes

### Certificate Status

Valid / Invalid

### Certificate Issuer

Certificate Authority

### Expiration Date

Remaining Certificate Lifetime

### TLS Version

Supported TLS Versions

### Cipher Suite

Negotiated Encryption Algorithms

### Subject Alternative Names

All Protected Domains

### Security Grade

Overall SSL Rating

### Recommendations

SSL Hardening Suggestions

---

# 🛡️ HTTP Security Headers

Audits browser security headers.

### Includes

### CSP

Protects against XSS attacks

### HSTS

Forces HTTPS connections

### X-Frame-Options

Protects against Clickjacking

### X-Content-Type-Options

Prevents MIME Sniffing

### Referrer Policy

Controls referrer information

### Permissions Policy

Restricts browser APIs

### Security Grade

Overall Header Rating

---

# 🚨 Advanced Threat Intelligence

Collects external intelligence.

### Includes

* URLScan Reports
* Infrastructure Reputation
* Public Intelligence
* Suspicious URLs
* Threat Indicators

---

# 🕰️ Wayback Machine

Analyzes historical snapshots.

### Includes

* Historical Pages
* Archived Versions
* Website Timeline
* OSINT Evidence

---

# 🤝 TLS Handshake Analysis

Inspects the secure connection negotiation.

### TLS Protocol Version

Negotiated TLS Version.

### Cipher Suite

Encryption algorithms protecting the connection.

### Cipher Version

Supported encryption version.

### ALPN Negotiation

Negotiated application protocol (HTTP/2, HTTP/1.1).

### Server Name Indication (SNI)

Indicates SNI support for virtual hosting.

### Session Ticket Support

Detects TLS Session Tickets.

### Session Resumption

Checks whether TLS sessions can be resumed.

---

# ⚡ Connection Diagnostics

Measures network performance.

### Includes

* DNS Lookup Time
* TCP Connection Time
* TLS Handshake Duration
* Time To First Byte (TTFB)
* Total Response Time
* Performance Summary

---

# 🔀 HTTP Redirect Analysis

Analyzes redirect chains.

### Includes

* Redirect Count
* Redirect Path
* HTTPS Upgrade
* Final Destination
* Redirect Status Codes
* Secure Redirect Validation

---

# 📄 HTML Structure Profiling

Profiles webpage structure.

### Includes

* HTML Size
* DOM Nodes
* Script Tags
* Stylesheets
* Images
* Forms
* Iframes
* Node Density

---

# 🌐 External Dependencies Inventory

Discovers external resources.

### Includes

* External Domains
* Analytics Providers
* Trackers
* CDNs
* Fonts
* Video Embeds
* JavaScript Libraries

---

# ⚙️ Technology Ecosystem

Detects technologies powering the website.

### Includes

* Framework Detection
* CMS Detection
* Web Server Detection
* Security Technologies
* Structured Data
* Frontend Libraries
* CSP Detection
* Security Policies

---

# 📦 Bulk Domain Scanner

Perform enterprise-scale scanning by uploading a `.txt` file.

### Features

* Upload Hundreds of Domains
* Automatic Queue Processing
* Concurrent Scanning
* Progress Tracking
* CSV Report Generation
* Bulk Security Reports
* Export Results

Perfect for:

* Attack Surface Discovery
* Enterprise Audits
* Bug Bounty Recon
* Threat Hunting
* Asset Inventory

---

# 🏗️ Engineering Highlights

* 🔐 JWT Authentication
* 🔑 Secure Password Hashing
* 🗄️ PostgreSQL Database
* ⚡ Prisma ORM
* 🌐 REST API
* 🔄 API Key Rotation
* 🚦 Intelligent Rate Limiting
* 🛡️ Request Validation
* ⚡ Response Caching
* 📂 User Scan History
* 📈 Modular Scan Engine
* 📊 Security Score Generation
* 📤 CSV Export Pipeline
* 📁 Bulk Processing Engine
* ⚙️ Environment-based Configuration
* 🚨 Graceful Error Handling
* 🔒 Secure Secret Management
* 📈 Scalable Backend Architecture

---

# 🛠️ Technology Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* shadcn/ui

### Backend

* Node.js
* Express.js
* TypeScript

### Database

* PostgreSQL
* Prisma ORM

### Authentication

* JWT
* bcrypt

### External Integrations

* VirusTotal
* WHOIS
* URLScan
* DNS APIs
* TLS Analysis
* Metadata Extraction
* Threat Intelligence APIs

---

# 🎯 Use Cases

* 🛡️ Security Operations Center (SOC)
* 🔍 OSINT Investigations
* 🎯 Penetration Testing
* 🐞 Bug Bounty Reconnaissance
* 🚨 Threat Hunting
* 🌍 Domain Intelligence
* 📡 Infrastructure Auditing
* 🏢 Enterprise Security Assessments
* 🔎 Attack Surface Discovery
* 📈 Security Compliance

---

## ⭐ Why Raccoon Radar?

Raccoon Radar combines **Domain Intelligence**, **OSINT**, **Threat Intelligence**, **DNS Analysis**, **SSL Inspection**, **Metadata Extraction**, **Email Security**, **Technology Fingerprinting**, **Infrastructure Analysis**, **Network Diagnostics**, and **Bulk Reconnaissance** into a single, enterprise-ready platform—eliminating the need to switch between multiple security tools.

> 🦝 **Raccoon Radar — See Beyond the Domain.**
