```bash
~/studies/devopswithdocker/part1/1.8 master ?1 > docker build -t curler . 
~/studies/devopswithdocker/part1/1.8 master ?1 > docker run -it --rm curler   
Input website:
helsinki.fi
Searching..
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="https://www.helsinki.fi/">here</a>.</p>
</body></html>
```
