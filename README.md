# packages

add key.gpg

    curl -s --compressed "https://linuxcutefish.github.io/packages/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/KEY.gpg >/dev/null

add list

    sudo curl -s --compressed -o /etc/apt/sources.list.d/cutefishos.list "https://linuxcutefish.github.io/packages/cutefishos.list"

update packages

    sudo apt update

