# Control Yourself
A Software to reduce your distraction caused by several non-productive websites

## Steps to run the blocker.js

Running the blocker is very simple. Just download the blocker.js file (inside JavaScript folder) and type in the following command through your terminal,

```sh
sudo node blocker.js
```

It will block the websites in the `websites` array in `blocker.js` file from 2pm to 6pm.

**Note** If you want to block some other websites, just place those websites in the websites array at line number 21 of blocker.js file. And, if you want to change the time at which the program blocks the website, just change the time interval inside the if statement at line number 33. By default the script blocks `www.someRandomWebsite.com` (I dont know what that is, as the name suggests it is SOME RANDOM WEBSITE xD), and it blocks it from 1400 hours (2pm) to 1600 hours (4pm).

## Important Notice

Please take a backup of your hosts file (`/etc/hosts`) before running the script. I am not responsible for any damages.