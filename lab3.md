# 1. ChatServer
![Image](lab3ss6) \
This is my code for ChatServer. Note that the code assumes that any URL input will follow the specified format outlined in the lab writeup.\
![Image](lab3ss1) \
For this image, the method `handleRequest` was called.\
This method takes a `URI` parameter, which is the URL which we type into the browser window. In this case, it was `http://localhost:4000/add-message?s=Hi&user=Tyler`\
Based on this method call, the `handleRequest` method takes the URL and identifies the User and the Message portion of the URL.\
It then arranges them in the format `User: Message`, and then adds this to the end of the `messages` field, which in this case was `"jpolitz: Hello\n"` at the time the method was called. A line break is added as well.\
The `messages` field is then printed out. (note: I already called the method once before I took the screenshots, which is why the `messages` field was not just `""`)\
![Image](lab3ss2) \
For this image, the method `handleRequest` was called again, since another URL is passed into the browser.\
This method takes a `URI` parameter, which is the URL which we typed into the browser window. In this case, it was `http://localhost:4000/add-message?s=Bye&user=jpolitz`\
Based on this method call, the `handleRequest` method takes the URL and identifies the User and the Message portion of the URL.\
It then arranges them in the format `User: Message`, and then adds this to the end of the `messages` field, which in this case was `"jpolitz: Hello\nTyler: Hi\n"` at the time the method was called. A line break is added as well.\
The `messages` field is then printed out.\
\
# 2. SSH keys
![Image](lab3ss3)\
location of key on my computer\
![Image](lab3ss5)\
location of key on the remote computer\
![Image](lab3ss4)\
logging into my account without the password\
# 3. Something I learned
Something I learned during this lab was the process of creating an SSH key, as well as the `scp` command to copy files. I also learned how to make a directory using `mkdir`. I also learned that `cd ..` will let you cd into the directory above the current one.\
Another thing that this lab helped me with was familiarizing myself with making a Server in java. Although this was a very basic server, writing the code helped me understand what we have been doing the past two labs.\

