# Cloudflare Rules
My Rules of Cloudflare Firewall for Block Bad Bot and Exploiting

# Bad Bot - Action Block
> * Blocks popular bad User Agent
> * Blocks connections by port (usually only bots do this)
> * Blocks outdated versions HTTP (1.0)
> * Blocks bad threats flagged by cloudflare
> * Blocks bad method requests
> * Blocks suspicious X-Forwarded-For
> * Blocks requests from the Tor network
> * Blocks ASN list of most known proxy scraping sites

# Exploiting (Beta) - Action Block
> * Blocking queries with SQL vulnerabilities
> * Blocking queries with XSS vulnerabilities
> * Block popular PHP vulnerabilities
> 
> ...

# Threat Check - Action Challenge
> * Checking for outdated versions HTTP (1.1, 1.2)
> * Checking countries that allow a lot of malicious traffic
> * Checking bad threats flagged by cloudflare
> * Checking for insecure requests (Not SSL requests)
> * Checking requests of unknown origin (Not have referer)

# How to use?
*Copy the expression and paste it into your expression builder*
![image](https://user-images.githubusercontent.com/55624740/161973398-05e74f0c-f72c-4c71-afa4-46987801f3c8.png)

# Not enough Cloudflare?
Free WAF for websites:
https://safeness.su/web-firewall/
Free Firewall for servers:
https://safeness.su/firewall/
