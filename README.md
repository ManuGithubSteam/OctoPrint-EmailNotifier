# OctoPrint-EmailNotifier with postfix.

Recieve email notifications when OctoPrint jobs are complete.

![Settings tab and email screenshot](extras/emailnotifier.png)

## Help needed!

- Basic function is working and it does the sending and snapshot etc.

__Todo:__
- rename the Plugin internally so they and anoved's version can coesist peacefully.
 - Unfortunatelly i dont know much about Octoprint Plugin makeup structure to make it work if i change the name
- Some mail parameter seems wrong, user definded FROM line is not used. 
- Testing Testing Testing (only tested "test" function for now.)

## Installation

Install via the OctoPrint [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager) or manually using the master Zip.

## Configuration

Configure postfix that postfix can send emails with the mail command!

## Acknowledgements

Clone from anoved

Uses [yagmail](https://github.com/kootenpv/yagmail) to send email.

## License

Licensed under the terms of the [AGPLv3](http://opensource.org/licenses/AGPL-3.0).
