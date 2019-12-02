## Code snippets. ##  
For more informatioon see ['Instructions.md'](Instructions.md)


Part to take out:
```
fbq('track', "PageView");  
```
Snippet 1:  
(the number is unique to your account):
```
<!-- Facebook Pixel Code --> <script>
!function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
document,'script','https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '45525584503xxx');
</script>  
<!-- End Facebook Pixel Code -->  
```

Snippet 2:  
```
<script>
fbq('track', "PageView");
 </script>  
 ```
(this time leave tag firing priority empty)  

Snippet 3:

```
<script>
 	 fbq('track', 'Lead', {
    value: 1,
    currency: ‘EUR’
  });
</script>  
```
