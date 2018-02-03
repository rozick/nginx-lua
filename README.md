# nginx-lua
Sample config file for nginx with our lua-nginx-module. 

This project allows the user to send an HTTP request with a site in the header and then receive the body in response. 

Send a request using the RedirectURL header. For example: `curl -XPOST test.localhost --header "RedirectURL: https://google.com"`

For more information on the lua-nginx-module check out https://github.com/openresty/lua-nginx-module.
