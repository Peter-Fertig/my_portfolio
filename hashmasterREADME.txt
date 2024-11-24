

##     ##    ###     ######  ##     ## ##     ##    ###     ######  ######## ######## ######## 
##     ##   ## ##   ##    ## ##     ## ###   ###   ## ##   ##    ##    ##    ##       ##     ##
##     ##  ##   ##  ##       ##     ## #### ####  ##   ##  ##          ##    ##       ##     ##
######### ##     ##  ######  ######### ## ### ## ##     ##  ######     ##    ######   ######## 
##     ## #########       ## ##     ## ##     ## #########       ##    ##    ##       ##   ##  
##     ## ##     ## ##    ## ##     ## ##     ## ##     ## ##    ##    ##    ##       ##    ## 
##     ## ##     ##  ######  ##     ## ##     ## ##     ##  ######     ##    ######## ##     ##

hashmaster.sh is a Bash file that will determaine if a file you downloaded has kept its integrity by compairing two SHA 256 hashes to determine if they are the same. 
![image]https://private-user-images.githubusercontent.com/132501189/389287280-d9deca29-751d-4204-a1e2-c904c324401d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzI0NjQ1MTEsIm5iZiI6MTczMjQ2NDIxMSwicGF0aCI6Ii8xMzI1MDExODkvMzg5Mjg3MjgwLWQ5ZGVjYTI5LTc1MWQtNDIwNC1hMWUyLWM5MDRjMzI0NDAxZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyNFQxNjAzMzFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yMDZjMDkzYWI5YWEwZDA3NzViYjgxNTJkZjFkZWI0OGRhYzdmNmY4ZTU3Y2JkMDBkYzc4ZmJmNDI3NzkxMjJiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.54uuHVe1NMHgnKFw1nvXDRq_gOIGhYR9uVsNqbR6j2c
One being copied from the website and the other from the downlaoded file.
When you run this script it will ask you to paste the first checksum( you will need to copy a chechsum from the website you are downloading the file from)
This Program assumes a few things:
1. You are using a common linux Distro with bash installed.
2. You saved the file you want to check in your "Downloads" folder(as in /home/user_name/Downloads/foo.bar)
3. you know how to make a program bash file executable in linux.
