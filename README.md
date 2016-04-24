# notify.sh

Little script to be notified when a command finishes.

You will be able to use [notifiers](https://github.com/jcgay/send-notification#available-notifiers) from [send-notification](https://github.com/jcgay/send-notification):

 - Growl,
 - Snarl,
 - notify-send
 - terminal-notifier
 and more...

# Installation

Download `notify` and add it to your path.

# Usage

When you are about to run a time consuming command, just wrap it with `notify`:

    notify make install
    
It will display a desktop notification when the task ends reflecting the task status (success or failure).