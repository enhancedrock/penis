> [!NOTE]
> Forked from [penis](https://github.com/enhancedrock/penis/)
> 
> This is penis but upgraded
# peen
it's a bash script which prints an ascii penis to your terminal with a random length from 10-25 dashes

i stole it from ruby, upgraded and rebranded everything because peen is better than penis

# flags
-c/--curved: makes the penis curved
-h/--hairy: makes the penis hairy

# demo
![demo](https://github.com/user-attachments/assets/7838a1d8-e1b3-4666-8efb-31aacc87c7a2)

# how 2 penis (or peen idk)
you can just download the `penis` file from the repo, give exec perms and run it but here are some installation commands anyways

for you (requires cURL and assumes you have ~/.local/bin on your $PATH):
```bash
mkdir -p "$HOME/.local/bin" && curl -fsSL https://raw.githubusercontent.com/comedymoon/peen/HEAD/penis -o "$HOME/.local/bin/penis" && chmod +x "$HOME/.local/bin/penis"
```
for everyone (requires cURL and sudo rights):
```bash
sudo curl -fsSL https://raw.githubusercontent.com/comedymoon/peen/refs/heads/main/penis -o /usr/local/bin/penis && sudo chmod +x /usr/local/bin/penis
```

# license
licensed under the penis license v2
