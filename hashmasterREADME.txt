

##     ##    ###     ######  ##     ## ##     ##    ###     ######  ######## ######## ######## 
##     ##   ## ##   ##    ## ##     ## ###   ###   ## ##   ##    ##    ##    ##       ##     ##
##     ##  ##   ##  ##       ##     ## #### ####  ##   ##  ##          ##    ##       ##     ##
######### ##     ##  ######  ######### ## ### ## ##     ##  ######     ##    ######   ######## 
##     ## #########       ## ##     ## ##     ## #########       ##    ##    ##       ##   ##  
##     ## ##     ## ##    ## ##     ## ##     ## ##     ## ##    ##    ##    ##       ##    ## 
##     ## ##     ##  ######  ##     ## ##     ## ##     ##  ######     ##    ######## ##     ##

hashmaster.sh is a Bash file that will determaine if a file you downloaded has kept its integrity by compairing two SHA 256 hashes to determine if they are the same. 
![hashmaster01](https://private-user-images.githubusercontent.com/132501189/389286982-e7d39bef-6282-45f3-90ec-ab56984b4c25.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzI0NjQyODEsIm5iZiI6MTczMjQ2Mzk4MSwicGF0aCI6Ii8xMzI1MDExODkvMzg5Mjg2OTgyLWU3ZDM5YmVmLTYyODItNDVmMy05MGVjLWFiNTY5ODRiNGMyNS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyNFQxNTU5NDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yYWRlZWE5N2RhM2I0NGFkMmVhYzQ1ZWQ3MWE1NDdhMGM0Mzk4NmJjNzY5ZmI1OGY5MDRmYjVlODA5MjM4NzJhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.PRUdMXtI60GYdJDfNfboa6nJuQjyNKs61hx9y9uRoKs)
One being copied from the website and the other from the downlaoded file.
When you run this script it will ask you to paste the first checksum( you will need to copy a chechsum from the website you are downloading the file from)
This Program assumes a few things:
1. You are using a common linux Distro with bash installed.
2. You saved the file you want to check in your "Downloads" folder(as in /home/user_name/Downloads/foo.bar)
3. you know how to make a program bash file executable in linux.
