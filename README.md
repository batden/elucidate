# elucidate

A neat Bash script to build/install/update the Enlightenment ecosystem on Ubuntu Noble Numbat.

Please take a look at the comments in the script before running it.

*See also [eloge.sh](https://github.com/batden/eloge) (companion script).*

## Get started

Before using elucidate, you'll need to install git on your system.

Open a terminal window and type in the following:

```bash
sudo apt install git
```

Next, clone the repository:

```bash
git clone https://github.com/batden/elucidate.git .elucidate
```

This creates a new hidden folder named .elucidate in your home directory.

Copy the elucidate.sh file from the new .elucidate folder to your download folder.

Navigate to the download folder and make the script executable:

```bash
chmod +x elucidate.sh
```

Then execute the script with:

```bash
./elucidate.sh
```

To run it again later, open a terminal and simply type:

```bash
elucidate.sh
```

(Use auto-completion: Just type *eluc* and press Tab.)

## Update local repo

Check for updates at least once a week.
To update the local repository, change to ~/.elucidate/ and run:

```bash
git pull
```
