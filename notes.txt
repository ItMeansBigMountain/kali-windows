FIXING APT UPDATE ISSUE ON WSL KALI LINUX 
    # download
    wget https://http.kali.org/kali/pool/main/k/kali-archive-keyring/kali-archive-keyring_2025.1_all.deb

    # install
    sudo dpkg -i kali-archive-keyring_2025.1_all.deb

    # remove downloaded file again
    rm kali-archive-keyring_2025.1_all.deb

    # try to update again
    sudo apt-get update -y

________________________________________________________________________________



