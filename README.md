# alias_linux
create a permanent alias
add alias dektop to lunch xfce4-session
alias desktop=xfce4-session

1)  gedit ~/.bashrc
2)  at the end of the file add the line  desktop='xfce4-session'
3)  execute . ~/.bashrc in your terminal (there should be a space between the . and ~/.bashrc
4)  check your alias  : in your terminal  :
$ alias
alias alert='notify-send --urgency=low -i "$([ $? = 0 ] && echo terminal || echo error)" "$(history|tail -n1|sed -e '\''s/^\s*[0-9]\+\s*//;s/[;&|]\s*alert$//'\'')"'
<e>alias desktop='xfce4-session'</e>


