

##     ##    ###     ######  ##     ## ##     ##    ###     ######  ######## ######## ######## 
##     ##   ## ##   ##    ## ##     ## ###   ###   ## ##   ##    ##    ##    ##       ##     ##
##     ##  ##   ##  ##       ##     ## #### ####  ##   ##  ##          ##    ##       ##     ##
######### ##     ##  ######  ######### ## ### ## ##     ##  ######     ##    ######   ######## 
##     ## #########       ## ##     ## ##     ## #########       ##    ##    ##       ##   ##  
##     ## ##     ## ##    ## ##     ## ##     ## ##     ## ##    ##    ##    ##       ##    ## 
##     ## ##     ##  ######  ##     ## ##     ## ##     ##  ######     ##    ######## ##     ##

hashmaster.sh is a Bash file that will determaine if a file you downloaded has kept its integrity by compairing two SHA 256 hashes to determine if they are the same. 
One being copied from the website and the other from the downlaoded file.
When you run this script it will ask you to paste the first checksum( you will need to copy a chechsum from the website you are downloading the file from)
This Program assumes a few things:
1. You are using a common linux Distro with bash installed.
2. You saved the file you want to check in your "Downloads" folder(as in /home/user_name/Downloads/foo.bar)
3. you know how to make a program bash file executable in linux.
Note: Kali Linux is wierd, so I made a seperate hashmaster_Kali file for that.
