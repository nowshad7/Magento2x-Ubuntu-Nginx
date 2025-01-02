#Kali Linux version

    cat /etc/os-release
    lsb_release -a
    hostnamectl
    cat /etc/issue


# Add an Alias in Kali Linux    

    nano ~/.zshrc    
    #alias hs="history"
    alias cl="clear"
    alias hs="history"
    alias u2="sudo apt update -y"
    alias u3="sudo apt update && sudo apt upgrade -y"
    alias ar="sudo apt autoremove -y"
    alias u4="apt list --upgradable -y"
    source ~/.zshrc