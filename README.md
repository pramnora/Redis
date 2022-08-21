# Redis
Redis Database code

-----

# What is Redis?  

The acronym Redis, actually, means: (Re)mote (di)ctionary (s)erver. 

Redis, is an open source FREE NOSQL Database...meaning it doesn't use 'tables/columns' to store data; but, instead, it's data is stored in 'key/value' pairs; furthermore, it works 'in memory'...and, therefore, its performance is always exceptionally 'fast'! 

Providing the computer has enough memory capicity; then, Redis, can store up to 4 billion items...! 

-----

# How to both download Redis/and, set it up to work on Windows 10
   
Redis can be downloaded to work on multiple different computing platforms, including: Mac/Linux/Windows.  

Currently, I'm using Windows 10; so, the following instructions will describe this particular kind of set up.  

1. Go to the main Redis web page site:   
   http://www.redis.io  
   ...click topmost navigation bar link which says, 'Download'...  
   ...scroll down the page to where it says: Windows port targeting Win64; click the link saying: Learn more...  
   ...scroll down the page to where it says: Redis on Windows; and, click the link: Release page  
   ...where it says at the top: 3.2.100; Downloads:...click on: Redis-x64-3.2.100.msi  
   https://github.com/MicrosoftArchive/redis/releases  

2. Wait for the program to download; and, then, click it to install the program.    
*NOTE*: During the installation process it may ask if you wish to include Redis onto your Windows pathname? Say, yes.   

3. If you did accept the default location in which to save the program; then, the program should have installed in:  
> C:\Program Files\Redis>   
...go into that same folder directory, and, run a Windows command prompt...type:  
> C:\Program Files\Redis>redis-cli  
The Windows command prompt should now change to say the following...  
> 127.0.0.1:6379>  
...where: 127.0.0.1 means you are running a Redis local server on the 'default' Redis port nos: 6379.   


4. Just to test that everything is up and working try running the following commands after the Windows command prompt symbol: >  
> C:\Program Files\Redis>redis-cli    
> 127.0.0.1:6379>Set x 1   
> OK  
> 127.0.0.1:6379>Get x  
> "1"  
> 127.0.0.1:6379>quit  
> C:\Program Files\Redis>    

...warmest congratulations. You've just gone and successfully added data to be stored inside of your Redis database/which you've also gone and successfully retreved back, again! ;-)  

-----

# Setting up Redis to work on Linux Ubuntu...

> apt-get install redis  
> redis-server  
> redis-cli  
> 127.0.0.1:6379>ping
> PONG
> 127.0.0.1:637>quit  

> redis-cli  
> 127.0.0.1:6379>SET a 1  
> OK  
> 127.0.0.1:6379>GET a  
> 1  
> 127.0.0.1:6379>  

-----

# Downloads

http://www.redis.io   

Redis Desktop Manager  
https://redisdesktop.com/download  

-----

# Tutorials

Official 'interactive' online tutorial/plus, other links...    
http://try.redis.io  
https://redis.io/commands  
https://redis.io/topics/data-types-intro  
https://redis.io/documentation  

# YouTube videos...

Redis Beginner Tutorial 1 - What is REDIS    
https://www.youtube.com/watch?v=HNDtcXVo5ow    

Redis Beginner Tutorial 2 – Why to use REDIS  
https://www.youtube.com/watch?v=kUmrYQO51uA  

Redis Beginner Tutorial 3 – How to install REDIS on windows (step-by-step)  
https://www.youtube.com/watch?v=ncFhlv-gBXQ  

Redis Beginner Tutorial 6 – How to use Redis Desktop Manager  
https://www.youtube.com/watch?v=csifoYtJ7pM  

Redis Beginner Tutorial 7 – Redis GUI Clients  
https://www.youtube.com/watch?v=h2OlLxe5x8M  

-----

Redis Crash Course Tutorial/(Travis Media)  
https://www.youtube.com/watch?v=Hbt56gFj998  

Build A Node.js & Redis App From Scratch  
https://www.youtube.com/watch?v=9S-mphgE5fA&amp...    

Redis Crash Course/(Web Dev Simplified)  
https://www.youtube.com/watch?v=jgpVdJB2sKQ    

Intro to Redis in C# - Caching Made Easy/(IAmTimCorey)    
https://www.youtube.com/watch?v=UrQWii_kfIE    

What is Redis Cache? (Redis)  
https://www.youtube.com/watch?v=Tqaqdfxi-J4    

Redis tutorial for beginners/(.NET Interview Preparation videos)  
https://www.youtube.com/watch?v=z9OPBVe6tgc  

What is Redis and What Does It Do?/(CBT Nuggets)    
https://www.youtube.com/watch?v=8A_iNFRP0F4  

-----

Can Redis be used as a Primary database?/(Hussein Nasser)  
https://www.youtube.com/watch?v=VLTPqImLapM  

Crazy Like a Fox: Redis as Your Primary Database/(Request Metrics)    
https://www.youtube.com/watch?v=29WlzWth6-s  

-----

Redis Labs and SQL Server  
https://www.youtube.com/watch?v=XQ9QEgLZAcQ  



