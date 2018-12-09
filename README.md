# BotBomb

Blow them away

# Alias

`sql.tar.gz`, `main.js`, `main.css`, etc. -> `10GB.tar.gz` (gzip bomb) 

## Why?

Web crawlers are clever and they won't follow 30x response.

But, web crawlers are expected to parse html file, so I return an html with malformed `<a>` tag, targeting to our malformed files. 

You can check that repo out in the [submodule](https://github.com/NeverBehave/docker-nginx-https-redirect/)'s `index.html` 

## Reference

https://blog.haschek.at/post/f2fda

https://github.com/Xumeiquer/nobots/blob/master/README.md

https://dl.yecdn.com/speedtest/ (Mainland China mirror: plz, be kind.)

https://repos.dfw.lax-noc.com
