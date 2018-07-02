# Configs Gerais

1. Install Iterm2. 
2. Se der algum problema com monitores externos, profiles > text > check anti-aliased
3. Color Scheme - Gostei de SpaceGray Eighties.
4. Font - 13pt Meslo LG S regular for Powerline.
4.1. Instalar fonts for powerline 
5. Temas - Um interessante foi o avit. Checar também o robyrussell e o af-magic

## Z 
1. Brew Install Z  
2. Se não funcionar o alias "z", adicionar no .zshrc a seguinte linha
`source /usr/local/etc/profile.d/z.sh`

## AutoSuggestions 
- Install `https://github.com/zsh-users/zsh-autosuggestions`. 
- adicionar `zsh-autosuggestions` como pluginn.

## Trash
Comando melhor do que `rm` no terminal. 
[link](https://github.com/sindresorhus/trash)
`npm install --global trash-cli`


## Delete lines, words, etc. 

Preferences > Profiles > Keys

Click the plus.
move forward one word

```
option+right
send escape
f
```

move back one word
```
option+left
send escape
b
```

delete to beginning of word (credit)
```
option+delete
send hex code
0x1B 0x08
```
delete to end of word
```
fn+option+delete
send escape
d
```