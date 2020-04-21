# polybar on Solus Budgie / Mate

## Instalação

Dependência;
mpd + ncmpcpp

# INSTALAÇÂO mpd + ncmpcp
#### sudo eopkg it mpd ncmpcpp && mkdir ~/.config/mpd && mkdir .config/mpd/playlists && wget https://raw.githubusercontent.com/nilsonlinux/ncmpcpp-mpd/master/mpd.conf && cp mpd.conf ~/.config/mpd/ && mpd && ncmpcpp && sleep 2 && exit


# INSTALAÇÂO POLYBAR
#### sudo eopkg it polybar && git clone https://github.com/nilsonlinux/polybar && cd polybar && cp -r fonts/* ~/.local/share/fonts && fc-cache -v && cp -r * ~/.config/polybar && ~/.config/polybar/polybar.sh
