# Redis
Redis Database code

-----

# What is Redis?  

Redis, is an open source FREE NOSQL Database; it's used to store data in 'key/value' pairs; it works 'in memory'...and, therefore, its performance is exceptionally 'fast'.  

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

# Downloads

http://www.redis.io   

-----

# Tutorials

Official 'interactive' online tutorial  
http://try.redis.io  




