# Alias

Aqui estan algunos alias para poder ver mejor los cambios realizados en el repositorios de trabajo actual.

## Muestra un gráfico con ramas, commits y decoraciones
`git config --global alias.graph "log --oneline --all --graph --decorate"`

## Log visual con colores, autor, tiempo relativo y grafo
`git config --global alias.lg "log --color --graph --pretty=format:'%C(yellow)%h%Creset %C(cyan)%d%Creset %s %C(green)(%cr) %C(bold blue)<%an>%Creset' --all"`

## Log compacto con commit ID, autor, mensaje, grafo y ramas (alias: tree)
`git config --global alias.tree "log --graph --pretty=format:'%C(yellow)%h%Creset %C(bold blue)%an%Creset - %s %C(green)%d%Creset' --abbrev-commit --all"`
