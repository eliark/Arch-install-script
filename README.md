# Arch-install-script
A set of instll scrips for arch linux. to make installing fast and fun.

run all three as root or sudo in this order

# run 
sudo ./strap-in        ## (this is full auto. just make sure that the partition that you want arch installed to is mounted at /mnt)

# then
sudo ./install-me      ## (but first open this script, search for and change all entries of "eli" to your username. then save & run it.)

# then run
sudo ./arch1           ## (this gives you the ability to customize your arch the way you want it. explore, and enjoy.)


# if they will not run try this

sudo chmod +x ./strap-in && sudo chmod +x ./strap-in && sudo chmod +x ./arch1
