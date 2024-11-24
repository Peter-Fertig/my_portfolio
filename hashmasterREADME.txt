

##     ##    ###     ######  ##     ## ##     ##    ###     ######  ######## ######## ######## 
##     ##   ## ##   ##    ## ##     ## ###   ###   ## ##   ##    ##    ##    ##       ##     ##
##     ##  ##   ##  ##       ##     ## #### ####  ##   ##  ##          ##    ##       ##     ##
######### ##     ##  ######  ######### ## ### ## ##     ##  ######     ##    ######   ######## 
##     ## #########       ## ##     ## ##     ## #########       ##    ##    ##       ##   ##  
##     ## ##     ## ##    ## ##     ## ##     ## ##     ## ##    ##    ##    ##       ##    ## 
##     ## ##     ##  ######  ##     ## ##     ## ##     ##  ######     ##    ######## ##     ##

hashmaster.sh is a Bash file that will determaine if a file you downloaded has kept its integrity by compairing two SHA 256 hashes to determine if they are the same. 
![hashmaster01](https://github.com/user-attachments/assets/335ea680-3e09-4fb1-9377-ff86e1feacbf)
![hashmaster2](https://github.com/user-attachments/assets/37af8fd9-09b3-4fdf-8644-c8b2f6d918d7)
One being copied from the website and the other from the downlaoded file.
When you run this script it will ask you to paste the first checksum( you will need to copy a chechsum from the website you are downloading the file from)
This Program assumes a few things:
1. You are using a common linux Distro with bash installed.
2. You saved the file you want to check in your "Downloads" folder(as in /home/user_name/Downloads/foo.bar)
3. you know how to make a program bash file executable in linux.
