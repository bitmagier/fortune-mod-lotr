# "Lord of the Rings" fortune cookies

This is the beginning of a collection of quotes from "Lord of the Rings".

Pull requests are welcome.

Setup (for GNU/Linux):
-
To use it, just copy the (pre-)generated *fortune* mod files from folder "/mod" into your *fortune* mod folder (or more elegant: create two links to the generated files from there).
The last step is to configure *fortune* to actually use the LOTR fortune mod.

- If not already done, you need to install "Fortune" app (called "Fortune-mod" sometimes) via your "Software Manager"<br/>
  `sudo apt install fortune-mod`
- Copy the generated mod files "lotr" and "lotr.dat" to the fortunes mod folder (e.g. "/usr/share/games/fortunes")<br/>
  `sudo cp mod/lotr mod/lotr.dat /usr/share/games/fortunes/`
- Configure your fortunes by adding the following line to the profile script of your favorite shell (e.g. ~/.bashrc for bash).<br/>
  `fortune lotr`<br/>
  An of course it is possible to use it together with other fortune mods with a line like this one:<br/>
  `fortune 75% lotr 18% de/zitate 7% pratchett`

