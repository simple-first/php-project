# Simple-First/PHP-Project

## Introduction

Welcome to `simple-first/php-project`. This repository aims to be the simplest and fastest way to set up a PHP project. It comes with the bare minimum code to get you started. This is a part of the Simple-First initiative, which is fully open-source.

## Prerequisites

- Docker
- Docker-Compose
- Composer

## Setup

```shell
# 1. Create the project
composer create-project simple-first/php-project my-project --ignore-platform-reqs

# 2. Navigate to the project folder.
cd my-project

# 3. Start the Docker services.
sail up -d

# 4. Open your browser and go to `localhost`.
```

You should see the Welcome message.

## Folder Structure

- `public/`: Web entry
- `src/`: Your PHP source files

## Tech Stack

- PHP 8.2
- Docker
- Laravel Sail

## Configuration

### Docker-Compose

The `docker-compose.yml` file contains the Docker services configurations.

### Composer

The `composer.json` file has project's autoload and dev dependencies.

## Contributing

Feel free to contribute and make this even simpler. Open a pull request or an issue.

## License
This project is licensed under the MIT License. This means you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software.

For the full license text, please see the LICENSE file in the repository.