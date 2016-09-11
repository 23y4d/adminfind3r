# adminfind3r
adminfind3r is PHP script ,find any  Administrator Login Page of various websites  is helpful for penetration testing..

##Installation
```
git clone https://github.com/23y4d/adminfind3r.git
```


##Screenshots

![adminfind3r](http://down.secureland.ps/Screenshot.png)



##Recommended PHP Version:

The recommended PHP version =>5.5.x

##Dependencies:

####curl library 

- Install for Ubuntu/Debian:
```
sudo apt-get install php5-curl
```

- Install for Centos/Redhat:
```
sudo yum install php5-curl
```

- Install using pip on Linux:
```
sudo pip install php5-curl
```

##Usage
php find [target] [type] [output]

 target : domin / url			            
 type   : -php OR -js OR -asp OR -cgi OR -cfm OR -brf  	    
 output : output will be saved to (optional)     

- exmple
 ```
php find exmple.com -php output.txt
```
- exmple2
 ```
php find exmple.com -php 
```

##License

adminfind3r is licensed under the GNU GPL license. take a look at the [LICENSE](https://github.com/23y4d/adminfind3r/blob/master/LICENSE) for more information.

##Version
**Current version is 1.0**
