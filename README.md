# packages

    curl -s --compressed "https://linuxcutefish.github.io/packages/cutefishos.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/cutefishos.gpg >/dev/null &&
    sudo curl -s --compressed -o /etc/apt/sources.list.d/cutefishos.list "https://linuxcutefish.github.io/packages/cutefishos.list" &&
    sudo apt update

