Frustrated.js
=============
Find out if your customer is frustrated with your application. It works by detecting rapid-fire clicks on your application and firing a custom event ".." that you can listen on. 


Installing
----------

Include [the javascript](frustrated.js) in your HTML template and create the event listener to listen on your customerFrustrated event[example]:

```javascript

<script type="text/javascript">

  document.addEventListener("customerFrustrated", function(e){ 
    alert("Looks like something is frustrating you :(. Email us at support@company.com and we'll help you!");
    }, false);

</script>
```

Companies Using Frustrated.js
-----------------------------
Telly

LegalReach




=^.^=
-----
