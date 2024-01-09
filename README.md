# elucidate

A neat Bash script to build/install/update the Enlightenment ecosystem on Ubuntu 24.04 LTS.

Please take a look at the comments in the script before running it.

> [!NOTE]
> It can be useful to keep a record of the pre-existing system status, before proceeding with the installation.
>
> Check out our [backup script](https://gist.github.com/batden/993b5ee997b3df2c3b075907a1dff116).

## Get started

First, you will need to install git on your system.

Open a terminal window and type in the following:

```bash
sudo apt install git
```

Next, clone the repository with:

```bash
git clone https://github.com/batden/elucidate.git .elucidate
```

This creates a new hidden folder named .elucidate in your home directory.

Copy the elucidate.sh file from the new .elucidate folder to your download folder.

Navigate to the download folder and make the script executable:

```bash
chmod +x elucidate.sh
```

Then execute the script:

```bash
./elucidate.sh
```

To run it again later, open a terminal and simply type:

```bash
elucidate.sh
```

> [!TIP]
> Use auto-completion: Type *eluc* and press the Tab key.

## Update local repo

To update the local repository, change to ~/.elucidate/ and run:

```bash
git pull
```

## Uninstalling

You can uninstall Enlightenment and related applications from your computer at any time.

See [eloge.sh](https://github.com/batden/eloge).
