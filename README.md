# neon-color-scheme-atom-syntax theme

### or, just "Neon" is fine

This is a port of the popular [Neon Color Scheme](https://packagecontrol.io/packages/Neon%20Color%20Scheme) for [Sublime Text](https://sublimetext.com/3) to the Atom editor. I've removed all the grossly Sublime-specific stuff like SublimeLinter and AAAPackageDev scopes, just because they aren't necessary, but I haven't done too much fiddling at this point, other than to tweak how selections look. I'm fairly new to Atom, so bear with me as I learn how to do things better. This is also my first real foray into LESS, so I'm learning all sorts of things as I go here.

## Peeves/Bugs (so far)

* I don't know if this is Atom's fault or mine, but when a scope has `background-color` set, the various `@selection` selectors just don't work - for example, open this file in Atom, and try to select a regular word. See how pretty that looks? Now, try to select part of or the whole URL for one of the links in the first section - you don't see a thing. Is there any way to fix that?
* There seem to be some colors defined somewhere like `@red`, `@yellow`, etc., but I don't know *where* they're defined or how to change them. Any guesses?

## Issues

If you haven't figured out so far, I'm learning as I go here, as Sublime is (and will probably remain) my primary editor. If you catch any bugs or have suggestions for improvements or anything, please [open an issue](https://github.com/MattDMo/neon-color-scheme-atom-syntax/issues). Have awesome changes you'd like to contribute? A [pull request](https://github.com/MattDMo/neon-color-scheme-atom-syntax/pull/new/master) is the way to go. Want to shower me in praise and/or money? You can support me (and any of your favorite open-source Github developers) at [Gratipay](https://www.gratipay.com/on/github/MattDMo/). Feel free to email me at <mattdmo@pigimal.com>, or tweet at me [@MattDMo](https://twitter.com/MattDMo). Find my blog on Sublime Text and other stuff at [MattDMo.com](http://mattdmo.com).

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=R97MGGYES6GAJ&lc=US&item_name=Matthew%20D%2e%20Morrison&item_number=neon%2datom%2dtheme&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted">
    <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" border="0" name="Donate" alt="PayPal - The safer, easier way to pay online!">
</a>_

## License

&copy; 2015 Matt Morrison <mattdmo@pigimal.com>.

This is free software. It is licensed under the [MIT License](http://opensource.org/licenses/MIT). Feel free to use this in your own work. However, if you modify and/or redistribute it, please attribute me in some way, and it would be great if you distribute your work under this or a similar license, but it's not required. A shout-out or a beer would be appreciated.
