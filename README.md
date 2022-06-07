<p align="center"><img src="https://raw.githubusercontent.com/dcblogdev/laravel-admintw/main/images/edit-user.png"></p>
<p align="center"><img src="https://raw.githubusercontent.com/dcblogdev/laravel-admintw/main/images/login.png"></p>

## Laravel AdminTW

Laravel AdminTW is a free theme built on top of Laravel Breeze, main reason for this theme is a sidebar layout rather than top navigation.

AdminTW is minimal theme presenting a clean sidebar and top bar and open areas for content to be displayed.

AdminTW supports both light and dark mode based on the users OS.

Provided are blade and Laravel Livewire components for common layout / UI elements and a complete test suite (Pest PHP) in addition to Laravel's default tests.

## Install

Install a fresh copy of Laravel then use require this package with composer:

```bash
composer require dcblogdev/laravel-admintw
```
Then install using the command:

```bash
php artisan admintw:install
```

Migrate the database

```
php artisan migrate
```

To compile your assets:

```bash
npm install && npm run dev
```

Run the tests by running PestPHP

```bash
vendor/bin/pest
```

## Styles

Default styling is applied to these elements: H1,H2,H3, p, table, thead tr, tbody tr, th, td, hr.

Custom classes

Input elements should use .input

Alerts should use .alert for base style then alert-colour for the colour:
```css
<div class="alert alert-blue"></div>
```


## Contributing

Contributions are welcome and will be fully credited.

## Pull Requests

- **Document any change in behaviour** - Make sure the `readme.md` and any other relevant documentation are kept up-to-date.

- **One pull request per feature** - If you want to do more than one thing, send multiple pull requests.

## Security

If you discover any security related issues, please email dave@dcblog.dev email instead of using the issue tracker.

## License

Laravel AdminTW is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
