# elucidate

A premium bash script to build, install, or update the Enlightenment ecosystem on Ubuntu 24.04 LTS.

Please refer to the script comments for hints and additional information.

> [!NOTE]
> It may be useful to keep a record of the pre-existing system status before proceeding with the installation.
>
> Check out our [backup script](https://gist.github.com/batden/993b5ee997b3df2c3b075907a1dff116).

## Getting started

Before using elucidate, you may need to install the git package on your system if it isn't already there.

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

Then, execute the script:

```bash
./elucidate.sh
```

To run it again later, open a terminal and simply type:

```bash
elucidate.sh
```

> [!TIP]
> Use auto-completion: Type _eluc_ and press the Tab key.

That's it.

You can uninstall Enlightenment and related applications from your computer at any time.

See [eloge.sh](https://github.com/batden/eloge).

## In the picture

![GitHub Image](/images/enlightenment_french.jpg)

_Please help us continue to promote this fantastic desktop environment.
Over the years, writing bash scripts, translations, documentation, and bug reports has been a substantial endeavor._

[Donate with PayPal](https://www.paypal.com/donate/?hosted_button_id=QGXWYZWH5QP5E) :trophy:
