# OUTDATED!
now this wont work idk why but something sh*t happend i think.
i hope someone fix it lmafo
i got error on require('mime') and it says change to import() but i got error "getType() is not function" error, so sucks.
i hate nodejs. its so f**king bad. 

i stop updating this. ill never update this.
dont use this. bye



# Moe Counter Lite
Moe Counter Lite is recoded version of Moe-Counter with Improvments.<br>
It can handle averge 12,550 requests per seconds under 10-90ms response time(depends machine spec)<br>
I run Performance-Test for 30seconds and count reached 376,000, averge responce time is 20ms.<br>
It is 10x Faster than original Moe-Counter *This result is based on running the load test tool with the same specifications and settings.<br>
# How To Install
Download from github:<br>
```git clone https://github.com/d1hydr0gen/moe-counter-lite.git```<br>
Install Dependencies:<br>
```npm i```<br>
Edit Configuration (if you want):<br>
```nano moe.js```<br>
Run:<br>
```node moe.js```<br>
WE ONLY TESTED THIS IN Node VERSIONS from v18.13.0 up to 21.7.3<br>
# How to fix "Mixed Content" error?
It's browser side error occurred for load HTTP content from HTTPS page.
To Fix this, you can use proxy server (nginx for example) and apply SSL Ceritification or Use Cloudflare's Proxy to get SSL Ceritification.<br>
If someone knows way to support SSL in node.js's http server let me know :D

# Only ２ theme?
Sadly Yes. but You can add theme easly.
open themes.json and add this
```
{
            "name": "your-theme-title",
            "letters":{
                "0":"assets/your-theme-dir/0.gif",
                "1":"assets/your-theme-dir/1.gif",
                "2":"assets/your-theme-dir/2.gif",
                "3":"assets/your-theme-dir/3.gif",
                "4":"assets/your-theme-dir/4.gif",
                "5":"assets/your-theme-dir/5.gif",
                "6":"assets/your-theme-dir/6.gif",
                "7":"assets/your-theme-dir/7.gif",
                "8":"assets/your-theme-dir/8.gif",
                "9":"assets/your-theme-dir/9.gif"
}
```
Done. Make it sure you added theme to assets folder.<br>
Please use 45x100(9:20) Images.<br>


* I recommend to host it your self when you use it!
