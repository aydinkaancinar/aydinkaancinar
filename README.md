<h1 align="center">Kaan Cinar</h1>
<p align="center"><strong>Software &amp; Platform Engineer</strong> · Toronto, Canada</p>

I build developer tools and cloud services. At IBM, I designed and operated infrastructure for a production SaaS platform and worked directly with enterprise customers.

## Engineering at IBM

### Cloud architecture

- **Multi-region failover.** Rolled out global load balancing, health checks, and automated failover across two regions to keep critical customer operations running through maintenance and outages.
- **Cloud migration.** Used canary tests, error rates, and latency to guide a staged migration to IBM Cloud. Adjusted Kubernetes replicas, node capacity, and resource limits as traffic shifted.

### Customer ownership and incident response

- **Enterprise customer ownership.** Served as the primary SRE contact for a customer handling **~85 million API calls per week**. Led weekly architecture discussions and built proofs of concept to validate proposed changes.
- **Sev 1 on-call.** Handled Sev 1 incidents roughly every two weeks and covered weekends every three weeks. Led engineers during critical incidents and coordinated escalations with Support and Development.

### Engineering tools

- **API performance testing.** Built a multithreaded Python tool with configurable concurrency, request rates, and payload sizes. Its reports verified critical API operations during maintenance.
- **Developer tooling.** Built Python tools used by **5+ engineers** to switch Kubernetes clusters across cloud accounts. Automated log collection, cutting a **30+ minute workflow to 2–3 minutes**.

## Featured project · Art Gallery

A live gallery for my ceramics and printmaking. I built a Django REST API and an admin workflow for publishing artwork, and designed the deployment around free-tier limits on Vercel, Render, Neon PostgreSQL, and Cloudflare R2.

**[Live gallery](https://arts.kaancinar.com) · [Source code and architecture](https://github.com/aydinkaancinar/kaan-gallery)**

**Core tools:** Python, Kubernetes, OpenShift, Linux, Ansible, Bash, Django, and REST APIs.
