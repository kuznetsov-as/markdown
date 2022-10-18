#### Simple text
 
docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest

#### Blockquotes
> docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest

#### Blockquote-in-a-blockquote
> docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest
>> docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest

#### Code block (tab or space)
  
    docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest
    
#### Code block highlighted (bash) - gitlab/idea only? For github use - console
``` bash
foo@bar:~$ docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest
```

#### Inline code
You'll want to run `docker run -p 5000:5000 -d --name back koshi8bit/back_automatic_build:latest`
