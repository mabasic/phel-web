# Phel - Web

Getting started Web template for [Phel](https://phel-lang.org/) lang.

This template creates a namespace called `app` for storing your application logic in `src/` directory, a public directory with `index.php` file for serving, and `app\tests` in `tests/` directory for storing your application tests.

**Requirement: PHP 7.4 or 8.0**

## Installation Via Composer

If your computer already has PHP and Composer installed, you may create a new Phel project by using Composer directly. After the application has been created, you may start the Phel application using the Phel CLI's `run` command:

```bash
composer create-project mabasic/phel-web example-app dev-main

cd example-app

php -S localhost:8000 -t ./public/
```

When you open the website on `http://localhost:8000` the output will be:

```
Hello, Phel!
```

## Shortcuts

- `composer dev` - Starts the PHP development server.
- `composer repl` - Starts the Phel REPL.
- `composer test` - Runs the test suite.
- `composer format {directory}` - Formats the given directory.
- `composer start {script}` - Executes the given script.


## Next Steps

From here you can learn more about using Phel from the [official website](https://phel-lang.org/), or view the [source code repository](https://github.com/phel-lang/phel-lang) and contribute to the development of the language and its ecosystem.
