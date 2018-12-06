# bypass nginx proxy_cache settings. 
proxy_cache_bypass $http_pragma;
proxy_cache_bypass $http_cache_control;
