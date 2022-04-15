[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/rezaamini-ir/laravel-easypanel/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/rezaamini-ir/laravel-easypanel/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/rezaamini-ir/laravel-easypanel/badges/build.png?b=master)](https://scrutinizer-ci.com/g/rezaamini-ir/laravel-easypanel/build-status/master)

# EasyPanel
EasyPanel is a beautiful, customizable and flexible admin panel based on Livewire for Laravel.

![EasyPanel screenshots](https://user-images.githubusercontent.com/15362786/163543631-a6c24010-242f-4136-8083-041355e7b97f.jpg)


## Installation and Usage Guide:
#### Install with composer 
**1- Install the package and its dependencies using Composer:**

`composer require rezaamini-ir/laravel-easypanel`


**2- Publish package files and create tables using the Artisan command:**

`php artisan panel:install`


**3- Create laravel Auth UI with any ways you want**

for example simple Laravel default auth method :

`composer require laravel/ui`

and then step up Auth Scaffolding (this is an example)

`php artisan ui bootstrap --auth`


**4-Edit .env file add database config on it then Migrate and serve project**

`php artisan migrate`

`php artisan serve`


**5- Register new user in `http://localhost:8000/register`**


**6- Convert user type to `admin`**

`php artisan panel:add [user_id]`

> change [user_id] by registerd user id

**7-**
<pre>
composer update
composer dump-autoload
php artisan serve
</pre>

**8- Go to `localhost:8000/admin`. you are in easypanel. for more info visit [EasyPanel Document](https://easypanel.netlify.app)**

----

#### Install as a local repository
**1- After installing laravel go to your `laravel` project and make `components` dir**

**2- Clone this repository on `laravel\components`**

**3- Add this to `composer.json`**
<pre>
"repositories": [
    {
        "type": "path",
        "url": "components/laravel-easypanel"
    }
],
"require": {
    ...
    "rezaamini-ir/laravel-easypanel": "@dev"
}
</pre>

**4- Go to **Install with composer** step `2` and do next steps**

----

[EasyPanel Document](https://easypanel.netlify.app)

### Features:
- Easy to install 🚀
- Multi Language
- A tons of features for Fields & Inputs
- RTL and LTR style
- Support CKEditor and Persian Font for RTL mode
- CRUD Maker GUI! 💡
- Everything is customizable
- A beautiful UI/UX with AdminMart template
- UserProviders and Authentication classes are customizable and you can change them
- Real time validation with Livewire 🚦


## What do we use in this package?
- [AdminMart Template](https://adminmart.com/)
- [Livewire](https://github.com/livewire/livewire)
- [Laravel EasyBlade](https://github.com/rezaamini-ir/laravel-easyblade)
- [CKEditor 5](https://github.com/ckeditor/ckeditor5)
- [Vazir Font](https://github.com/rastikerdar/vazir-font)

## Contribution: 
If you feel you can improve our package You are free to send a pull request or submit an issue :)

## V2 Path 
- [ ] ACL System
- [ ] Logging System
- [x] CRUD Maker GUI
- [x] RTL Style
- [x] Translation
- [x] Relational inputs
- [x] More input types & editors
- [x] Customizable inputs and fields
- [ ] Multi languages support
