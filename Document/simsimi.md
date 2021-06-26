# Document Simsimi

### Url
~~~
GET https://api.simsimi.net/v1/?lang=[Language]&cf=[Chatfuel]&text=hi
~~~
### Language
```
en (English)
ph (Filipino)
zh (中文[简体])
ch (中文[繁體])
ru (Русский<)
id (Bahasa Indonesia)
ko (한국어)
ar (العربية)
fr (Français)
ja (日本語)
es (Español)
de (Deutsch)
pt (Português)

Contact me if you want to update more languages.
```


### Chatfuel
~~~
//cf = true
{
    "methods": "GET",
    "messages": [{
        "ask": "hi",
        "response": "Hello",
        "result": 100
    }],
    "error": "Contact fb.com\/copcute.xyz",
    "donate": "Momo: 0974991632 - Bitcoin: 153uvWrtsaWFDtzDdf2efwWajnGR3GUScx - Eth: 0x1Fb9e08A5662fbC06756d3A1F19EEcD8b4bBD855"
}

//cf = false
{
    "methods": "GET",
    "success": "Hello",
    "donate": "Momo: 0974991632 - Bitcoin: 153uvWrtsaWFDtzDdf2efwWajnGR3GUScx - Eth: 0x1Fb9e08A5662fbC06756d3A1F19EEcD8b4bBD855"
}
~~~

### Images Keyword (ChatFuel)
~~~
    'bj','pussy','lesbian','hentai',
    'lewd','kiss','lick','hug','baka',
    'cry','poke','smug','slap','tickle',
    'pat','laugh','feed','cuddle'
    
//cf = true & text=baka
{
    "methods": "POST",
    "messages": [{
        "ask": "baka",
        "attachment": {
            "type": "image",
            "payload": {
                "url": "https:\/\/domain.com\/storage\/baka\/baka_020.gif"
            }
        },
        "response": "t\u00f4i l\u00e0 sim ngu ng\u00f3c nh\u1ea5t th\u1ebf gian. ",
        "result": 100
    }],
    "error": "Contact fb.com\/mewcop",
    "donate": "hoanggiap.name.vn\/donate\/"
}

~~~
