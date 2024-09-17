создать ssh ключЖ ssh-keygen -t ed25519 -C "почта"
добавить ключ ssh-add .ssh/имя файла с ключом
ssh-add -l
ssh -T git@github.com
