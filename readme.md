# MYPROJECT

Diving into Laravel.

        Cada usuário pode criar sua conta - ok 
        Esse usuário poderá escolher entre cadastrar produtos ou serviços que ele presta para outras pessoas.
        O usuário tem a possibilidade de cadastrar termos e condições para acrescentar no orçamento depois. 
        Após esse cadastro é disponibilizado para ele a opção de gerar um orçamento para o cliente dele, baseado nos produtos e páginas de termos criados

## Features

* Bootstrap 3.x
* Custom Error Pages
    * 403 for forbidden page accesses
    * 404 for not found pages
    * 500 for internal server errors
* Confide for Authentication and Authorization
* Back-end
    * User and Role management
    * Manage blog posts and comments
    * WYSIWYG editor for post creation and editing.
    * DataTables dynamic table sorting and filtering.
    * Colorbox Lightbox jQuery modal popup.
* Front-end
    * User login, registration, forgot password
    * User account area
    * Simple Blog functionality
* Packages included:
    * [Confide](https://github.com/zizaco/confide)
    * [Entrust](https://github.com/zizaco/entrust)
    * [Ardent](https://github.com/laravelbook/ardent)
    * [Generators](https://github.com/JeffreyWay/Laravel-4-Generators/blob/master/readme.md)

##Requirements

    PHP >= 5.4.0
    MCrypt PHP Extension

### Production Launch

By default debugging is enabled. Before you go to production you should disable debugging in `app/config/app.php`

```
    /*
    |--------------------------------------------------------------------------
    | Application Debug Mode
    |--------------------------------------------------------------------------
    |
    | When your application is in debug mode, detailed error messages with
    | stack traces will be shown on every error that occurs within your
    | application. If disabled, a simple generic error page is shown.
    |
    */

    'debug' => false,
```