# First-things-you-may-wanna-change-in-kali-liunx
I have created a list of things that i like to change after os installation.

A)GRUB Background image:
  
  1.Open file manager and go to the location /usr/share/images/desktop-base/desktop-grub.png
  2.Move the image file(actually it is a link file) to a known location(like pictures).
  3.Using browser download a .png image with 1920x1080(or download a 1920x1080px and convert it to png format).
  4.Rename the new image as desktop-grub.png and paste it in the location /usr/share/images/desktop-base/
  
B)GRUB Timeout:
  
  1.Enter the following command in terminal.
      leafpad /etc/default/grub 
   
  2.Change the TIMEOUT 3 to TIMEOUT 1 (or whatever the number you want Eg. 2,3,0,...).
  
