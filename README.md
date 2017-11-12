# Redis
Redis Database code

# Download  

Redis is an open source FREE NOSQL Database that one can download from:  
http://www.redis.io  

Redis can be downloaded to work on multiple different computing platforms, including: Mac/Linux/Windows.  
Currently, I'm using Windows 10; so, the following instructions will describe this particular kind of set up.  

1. Go to the main Redis web page site:   
   http://www.redis.io  
   ...click topmost navigation bar link which says, 'Download'...  
   ...scroll down the page to where it says: Windows port targeting Win64; click the link saying: Learn more...  
   ...scroll down the page to where it says: Redis on Windows; and, click the link: Release page  
   ...where it says at the top: 3.2.100; Downloads:...click on: Redis-x64-3.2.100.msi  

2. Wait for the program to download; and, then, click it to install the program.    
*NOTE*: During the installation process it may ask if you wish to include Redis onto your Windows pathname? Say, yes.   

3. If you did accept the default location in which to save the program; then, the program should have installed in:  
C:\Program Files\Redis  
...go into that same folder directory, and, run a Windows command prompt...type:  
C:\Program Files\Redis> redis-cli  
...and, this should load the Redis command line interface...so that you are now ready to issue commands to the Redis Database.  

4. Just to test that everything is up and working try running the following commands after the Windows command prompt symbol: >  

> 127.0.0.1:6379>Set x 1  
> 127.0.0.1:6379>OK  
> 127.0.0.1:6379>Get x  
> 127.0.0.1:6379>"1"  

...warmest congratulations. You've just gone and successfully added data to be stored inside of your Redis database/which you've also gone and successfully retreved back, again! ;-)  
