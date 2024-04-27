AstroNvim is the most powerful vim configuration I've met. I like it. 

## Usage
If AstroNvim is not installed, installed it first. 
```
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak

git clone --depth 1 https://github.com/AstroNvim/template ~/.config/nvim
```

And then install the user configuration
```
git clone https://github.com/JerryMouseZ/AstroUser.git ~/.config/nvim/lua/user
```
