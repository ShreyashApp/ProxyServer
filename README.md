# ProxyServer
This project implements a proxy server for a single connection. Not many functionalities. 
Tested with Ordinary fetch-Fetch a normal web page. 
Split request-Request in more than one ‘chunk’ (connection), 
Large request/resp-Requests of size 65535 bytes or response of size about 200MB, 
Bad Connect-URL to a bad port or bad host (e.g. blahblah.com:2222), 
Malformed request-HTTP request that is syntactically incorrect,
Huge request-Requests larger than 65535 bytes (of up to 1MB), 
Stress test- We will test your proxy with several high-speed requests
