I don't expect to be able to encounter every bit of IRSSI's UI in my daily chatting, so if you find some sections that are unthemed, or where the themeing seems a bit off, please do open a ticket or raise a pull-request.

If you open a bug asking for the theme to be applied somewhere, please let me know how to reproduce the message.

If you want to raise a pull request, here are some notes to help:

 * I can't seem to theme the /HELP text properly. IRSSI prints the timestamp and then prints the help-text *unformatted*. If we want the expandable first segment, then we have to put up with this.
 * I am trying to bring the colouring close to the solarized standards so:
   * Most of the UI will be in shades of grey.
   * Channels are in GREEN
   * Nicks are in BLUE
   * "Own Nick" is in YELLOW
   * Modes are in PURPLE
   * Minimal use of bold (as some terminals conflate 'bold' and 'bright')
   * All colouring will be done using the basic 16-colour palette. My understanding is that correct use of solarized means that you should configure your _terminal_ to map the base-16 colours to the correct RGB shades; if that's not possible, then the 256-colour palette has some approximately-equivalent colours.


