# Create a Shell Alias for Artisan
If you frequently switch between PHP versions, you can create a shell alias to streamline the process:

1. Edit your shell configuration (.bashrc, .zshrc): Add an alias that runs php artisan serve with the desired PHP version:

```bash
alias artisan74='/usr/local/bin/php@7.4 artisan serve'
```

```bash
source ~/.bashrc  # or ~/.zshrc
```

```bash
artisan74
```
