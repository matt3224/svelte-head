# Svelte Head Test

Steps:
1. Fire this repo up
2. Check the head and you will see 2 `<meta name="description" content="One: A test of svelte head with @html">`
3. Change to the "about" page and you will see that one of them has changed.
4. Change to blog and again one has changed but one remains the same throughout

```
<head>
   ...
   <title>Sapper project template</title>
   <meta name="description" content="One: A test of svelte head with @html">
   <meta name="description" content="One: A test of svelte head with @html">
</head>
```
