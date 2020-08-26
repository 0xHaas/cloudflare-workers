# cloudflare-workers
This repository contains [CloudFlare workers](https://workers.cloudflare.com/) I use on a regular basis. 

# Why workers?
CloudFlare workers can be written in a variety of languages (JS, Rust, C, and C++) and are highly performant. Rather than having to handle configuration at the edge, CloudFlare handles this for us. In sec-headers above, we use CloudFlare workers to affix [security headers](https://securityheaders.io) to all traffic. 

The impact on my loading speeds is practically negligible, but the added security from being able to set these headers is incredible.  
