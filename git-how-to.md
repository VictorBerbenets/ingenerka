1) ssh-keygen -t ed25519 -C "имя.фамилия@phystech.edu"
2)eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_ed25519
3)git clone "rep name"