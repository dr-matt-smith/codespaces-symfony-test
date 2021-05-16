using MS Devcontaine for PHP 
https://github.com/microsoft/vscode-remote-try-php

added 2 lines to .devcontainer install symfony CLI
```bash
  # Install Symfony CLI
    && curl -sS https://get.symfony.com/cli/installer | bash \
    && mv /root/.symfony/bin/symfony /usr/local/bin/symfony \
    && rmdir /root/.symfony/bin /root/.symfony \
    && /usr/local/bin/symfony self-update --no-interaction \
```

