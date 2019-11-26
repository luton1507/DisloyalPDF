# DisloyalPDF
  Adobe Reader is infamous for many of the exploits found within it. Well here is a example of one of the more famous exploits. It takes both an exe and a PDF and binds the files together so when the target runs the file it will run the exe.
  [https://github.com/Xerox00/DisloyalPDF/blob/master/PDF.png|alt=MalicousPDF]]
  
 ## Setup
 ```
 git clone https://github.com/Xerox00/DisloyalPDF
 ```
 ```
 cd DisloyalPDF
 ```
 ```
 pip3 install colorama
```
 ```
 pip3 install zlib
```
```
python3 DisloyalPDF.py
```
Thats about it, then you just need to give it the files to bind.

## Note 
If you are having issues and it says "Unable to locate file" try to give the full file path, I have noticed that it can have some issues with feeding it the files to bind.
Also another thing to note, this exploit targets the very vunerable adobe acrobat reader 2010. That being said it will work on older versions and the 2010 versions but it only sometimes works with the more modern version.

## Disclaimer
Use this software is provided for educational puposes only. Do not use this in any malicous way. Creater is not liable for your actions. That being said don't abuse this.
