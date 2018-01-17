# net2doc
grep net package and generate prety document, especially for http-api,restful-api, based on python3,mitmproxy jinja2

pip3 install mitmproxy jinja2

mitmdump grep.py

than set you explorer's proxy use  mitmproxy-ip:8080

for example:

curl -x 127.0.0.1:8080   'http://httpbin.org/ip'
