# How_To_Install_Ubuntu20.04LTS_on_VirtualBox_in_Windows10

Check out this video on the entire guide from downloading VirtualBox and installing Ubuntu on it, to adjusting some features that can come in handy.

## NOTE: Run this line of code before installing Guest Additions:

```sudo apt install build-essential dkms linux-headers-$(umane -r)```

## Error: Incase you encounter an error while trying to run the Guest Audittions from the top menu bar on Devices

Navigate to /media/ubuntu/VBox_GAs_6.1.38/ folder

```cd ~/media/ubuntu/VBox_GAs_6.1.38/ ```

Locate the autorun.sh file and run it

```./autorun.sh```

Make sure to include the './' before the script name to specify that the script is located in the current directory.

If the script has executable permissions,  it will start running, and you will see the output or actions performed by the script in the terminal.


### If you encounter any issues while running the script, ensure that the script file has the necessary permissions. You can use the chmod command to add executable permissions if needed:

```chmod +x autorun.sh```

Check out the video below to learn more.

https://youtu.be/x5MhydijWmc
