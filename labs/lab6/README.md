# Lab 6
## EE 322 A

### Outline
In this lab, we will be using Node.js to create a simple server and a client. In addition, we will be using Pystache to create a simple template engine. and run the say_hello.py file usign the say_hello.mustasche template.

#### Run the [hello.js](hello.js) file:
```sh
PS C:\Users\jxwel\OneDrive\Documents\Stevens\CPE_322_A\iot\lesson6> node hello.js
Server running at http://127.0.0.1:8080/
response end call done
request end event fired
```

In the above snippet from the terminal, we can see that the server is running at http://127.0.0.1:8080/ and the request end event is fired. This means that the server is running and the request has been processed.

#### Next, run the [hello-world.js](hello-world.js) file:
```sh
PS C:\Users\jxwel\OneDrive\Documents\Stevens\CPE_322_A\iot\lesson6> node hello-world.js
Server running at http://127.0.0.1:3000/
```

In the above snippet from the terminal, we can see that the server is running at http://127.0.0.1:3000/. When the page is visited, the website will display the text "Hello World!".

#### Next, run the [http.js](http.js) file:
```sh
PS C:\Users\jxwel\OneDrive\Documents\Stevens\CPE_322_A\iot\lesson6> node http.js
0

1
2
3
4
5
6
```

In the above snippet from the terminal, we can see that the server is running at http://127.0.0.1:3000/. When the page is visited, the website will display the text "This page was refreshed X times!". where X is the number of times the page has been refreshed. provided by the server.

#### Now, install pystache:
```sh
pip install pystache
```

#### Finally, run the [say_hello.py](say_hello.py) file:
```sh
(venv) PS C:\Users\jxwel\OneDrive\Documents\Stevens\CPE_322_A\iot\lesson6> python say_hello.py
Hi Alexa!
Hello, World!

['Hey ', _SectionNode(key='who', index_begin=12, index_end=18, parsed=[_EscapeNode(key='.'), '!'])]
Hey Google!
Hey Siri!
```

In the above snippet from the terminal, we can see the result of the [say_hello.mustache](say_hello.mustache) template populated with the data from the [say_hello.py](say_hello.py) file.
