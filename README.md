CHANGED:

Toolbar.hh
Windows.cc
Windowmenu.cc



# Toolbar.hh
add...		 Toolbar Ctime include

# Window.cc
replace...	Titlebar doubleclick > Toggle Maximize
add...		Titlebar button2 > close
add...		Titlebar button 6, 7 habilitate
add... 		Titlebar button 6, 7> Next, Previous Window

# Windowmenu.cc
add...		Windowmenu 3 items + Separator...
	... Restart Client (SIGHUP)
	... DumpInfo (tmp/...txt
	... ToggleDecorations py external scrpt....

# Screen.cc
add... 		button1 > iconmenu
add... 		button6, 7 enable
add... 		button6, 7> Next, Previous Windows

# main.cc
add...		version notice

# Toolbar.cc - seg 27 abr 2026 03:35:54 -03
add...		Clock button 1, 2.... enable
replace...	window_label button 4,5 > nextfocus prevfocus 
replace...	window_label button 2 > close 
- seg 27 abr 2026 04:49:33 -03

version 0.8


make clean
./configure --prefix=$HOME/.local/blackbox-hacked
make
make install
