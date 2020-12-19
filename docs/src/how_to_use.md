# How to use

- Clone theme

```shell
mdbook init 

mkdir themee && cd theme 
 
git clone https://github.com/francis-du/mdbook-grogu-theme
 
rm -rf .gitignore README.md LICENSE docs/* .github/*
```

- modify `book.toml`

```shell
[output.html]
default-theme = "grogu"

mdbook serve
```

- Live demo

```shell
https://grogu-theme.francis.run
```