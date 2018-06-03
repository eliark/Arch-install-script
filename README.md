# Arch-install-script
A set of install scripts for Arch Linux. To make installing fast and fun.

Run all three as root or sudo in this order.

# run 
sudo ./strap-in        

##(this is full auto. just make sure that the partition that you want Arch installed to is mounted at /mnt)

# then
sudo arch-chroot /mnt

##(Make sure to do this before running install-me it will fail if you don't)

# then
sudo ./install-me     

##(but first open this script, search for and change all entries of "eli" to your username. then save & run it.)
##(when this is finnished vanilla arch is installed.

# then run
sudo ./arch1        

##(this gives you the ability to customize your arch the way you want it. explore, and enjoy.)


# if they will not run try this

sudo chmod +x ./strap-in && sudo chmod +x ./strap-in && sudo chmod +x ./arch1
