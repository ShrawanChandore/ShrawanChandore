print("Hello, World")
import request 
resp = request.get("http://olympus.realpython.org")
html = resp.text
print(html[86:132])
