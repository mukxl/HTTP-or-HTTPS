# HTTP-or-HTTPS

This tool checks whether a given URL is active and determines if it's using HTTP or HTTPS. It processes a list of domains from a text file. The approach is as follows: we first try accessing the domain via HTTP. If we receive a 301 or 302 response code, it indicates that the site has been redirected to HTTPS. If the response is a 200, it means the site is accessible and operating over HTTP.



