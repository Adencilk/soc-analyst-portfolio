Title
WordPress Conditional Redirect Investigation

Short Description
Investigation of a WordPress site experiencing conditional redirection when accessed over HTTP.

Environment
- VirtualBox lab
- Ubuntu Server 24.04
- WordPress test instance

Objective
Identify the possible cause and indicators of a conditional redirect affecting only HTTP traffic.

Tools Used
- nmap
- ping
- traceroute
- VirusTotal

Process
- Performed basic connectivity checks to the server.
- Scanned exposed services and ports.
- Reviewed WordPress directories and plugin files.
- Checked for suspicious redirect behavior.

Findings
- Redirect occurred when accessing the site over HTTP but not HTTPS.
- Behavior suggested a possible injected redirect script or conditional rule.

Challenges
- Could not immediately locate the exact injected file.

What I Learned
- Redirect malware can be condition-based.
- Initial network and file inspection helps narrow down the investigation.

Next Improvement
- Inspect database and web server configuration for injected redirect rules.
