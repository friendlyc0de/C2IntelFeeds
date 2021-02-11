# C2IntelFeeds
Automatically created C2 Feeds


* Feeds ( Source/Raw Data courtesy of Censys - https://censys.io/ )

  By default C2s seen active in the last 7 days are added to the main feed files.

  * `C2 IPs` - Live C2 IP (no frontend or CDN IPs - All bad)
  * `C2 Domains` - All domain names extracted from implants, including domain fronting values and fake Host headers (High abuse of MS, Apple and Google).
  * `C2 Domains Filtered` - Excludes several domains abused in domain fronting, along with fake headers for popular sites. Current filter list:  `(^microsoft\.com|\.microsoft\.com|\.windowsupdate\.com|^apple\.com|^amazon\.com|\.apple\.com|\.amazon\.com|\.mzstatic\.com|^gmail\.com|^jquery\.com|^github\.com|\.live\.com|\.bing\.com|^google\.com|\.bloomberg\.com|\.oracle\.com|\.lenovo\.com|^a0\.awsstatic\.com|^ajax\.aspnetcd\.com|^baidu\.com|^cnn\.com)`

  Additionally a new 30 day set of feed files was added for any C2 seen live in the last 30 days.
  
* VPN 
  * Nord VPN Exit Nodes
