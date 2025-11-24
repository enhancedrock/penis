> [!NOTE]
> Forked from [penis](https://github.com/enhancedrock/penis/)
# peen
it's a bash script which prints an ascii penis to your terminal with a random length from 10-25 dashes

i stole it from ruby and rebranded everything because peen is better than penis

# demo
![demo](https://github.com/user-attachments/assets/d161b162-3049-4e6d-9169-e26a7452ed4e)

# how 2 penis
you can just download the `penis` file from the repo, give exec perms and run it but here are some installation commands anyways

for you (requires cURL and assumes you have ~/.local/bin on your $PATH):
```bash
mkdir -p "$HOME/.local/bin" && curl -fsSL https://raw.githubusercontent.com/enhancedrock/penis/HEAD/penis -o "$HOME/.local/bin/penis" && chmod +x "$HOME/.local/bin/penis"
```
for everyone (requires cURL and sudo rights):
```bash
sudo curl -fsSL https://raw.githubusercontent.com/enhancedrock/penis/refs/heads/main/penis -o /usr/local/bin/penis && sudo chmod +x /usr/local/bin/penis
```

# license
licensed under the penis license v2
