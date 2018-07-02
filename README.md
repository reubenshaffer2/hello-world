# hello-world
Hello, GitHub...

I've been using git for years.  I have a lot of C code that I may put on here, and also some C++, C#, PHP, JavaScript, and maybe even some really old Pascal code.  I guess that this repository is used as a sort of news feed by people on here, and maybe I'll put a couple dozen versions of "Hello, world" here just for kicks but I guess I'll be using it primarily for the README that it seems will kind of act as a news feed or something.

I just wrote some code I couldn't find anywhere on the 'net for parsing serialized PHP session data in C.  I realize that may seem weird, but I'll put it on here after I test it a little bit and maybe I'll add interfaces for C# or something later.  It seems that there is nothing out there for parsing the data, and the only alternate serializer implementations I found appeared to be something for Node.js and something that appeared to be geared towards serializing foreign characters or something.  So, anyway, I decided the best plan was to let PHP serialize these things using its standard serializer and just deal with the data.  I looked at just incorporating the serialization functions from PHP itself, but it was pretty closely tied to their GC and who knows what else, so I decided for basic deserialization I would make an implementation myself.  It should be in another repository for me in the next day or two.

I'm not sure what else I'll put here.  I've been working on an HTTP/HTTPS server that's multithreaded and modular (uses libdl) for Linux.  After I clean up the code some, I may put some of that code on here, but it does have a few modules I'd rather not publish as they depend on other libraries that I will not be releasing.

So I guess I'll stop writing and finish this great intorductory tutorial thing...
