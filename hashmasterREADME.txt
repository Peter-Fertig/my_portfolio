

##     ##    ###     ######  ##     ## ##     ##    ###     ######  ######## ######## ######## 
##     ##   ## ##   ##    ## ##     ## ###   ###   ## ##   ##    ##    ##    ##       ##     ##
##     ##  ##   ##  ##       ##     ## #### ####  ##   ##  ##          ##    ##       ##     ##
######### ##     ##  ######  ######### ## ### ## ##     ##  ######     ##    ######   ######## 
##     ## #########       ## ##     ## ##     ## #########       ##    ##    ##       ##   ##  
##     ## ##     ## ##    ## ##     ## ##     ## ##     ## ##    ##    ##    ##       ##    ## 
##     ## ##     ##  ######  ##     ## ##     ## ##     ##  ######     ##    ######## ##     ##

hashmaster.sh is a Bash file that will determaine if a file you downloaded has kept its integrity by compairing two SHA 256 hashes to determine if they are the same. 
![image]https://gist.github.com/Peter-Fertig/b27b18cddb3f541f8ac55e1757535d09?permalink_comment_id=5298675#gistcomment-5298675
One being copied from the website and the other from the downlaoded file.
When you run this script it will ask you to paste the first checksum( you will need to copy a chechsum from the website you are downloading the file from)
This Program assumes a few things:
1. You are using a common linux Distro with bash installed.
2. You saved the file you want to check in your "Downloads" folder(as in /home/user_name/Downloads/foo.bar)
3. you know how to make a program bash file executable in linux.
