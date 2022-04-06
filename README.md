# cloudflare-rules
[AntiDDoS] My Rules of Cloudflare Firewall for Block Bad Bot and Exploiting

# Block Bad Bot - Action Block
> Blocks popular bad User Agent
> 
> Blocks connections by port (usually only bots do this)
> 
> Blocks outdated versions HTTP (1.0)
> 
> Blocks Bad Threats Flagged By Cloudflare
> 
> Blocks bad method requests
> 
> Blocks suspicious X-Forwarded-For
> 
> Blocks requests from the Tor network
> 
> Blocks ASN list of most known proxy scraping sites

# Block Exploiting (Beta) - Action Block
> Blocking queries with SQL vulnerabilities
> Blocking queries with XSS vulnerabilities
> Block popular PHP vulnerabilities
...

# Threat Check - Action Challenge
> Checking for outdated versions HTTP (1.1, 1.2)
> Checking countries that allow a lot of malicious traffic
> Checking Bad Threats Flagged By Cloudflare
> Checking for insecure requests (Not SSL requests)
> Checking requests of unknown origin (Not have referer)
