# Document Simsimi

### Url
~~~
https://api.simsimi.net/v1/?lang=[Language]&cf=[Chatfuel]&text=hi
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
