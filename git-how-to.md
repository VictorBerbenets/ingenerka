- ssh-keygen -t ed25519 -C "имя.фамилия@phystech.edu"
- eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_ed25519
- git clone "rep name"