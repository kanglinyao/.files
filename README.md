# .files
My dot files for arch linux i3

Turn contex menu key to right Mod key: 
xmodmap -e "keysym Menu = Super_R"
Showing the keycode: 
xev | gawk '/keycode/{if($0!=l)print;l=$0;}'

