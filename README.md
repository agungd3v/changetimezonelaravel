# Change timezone laravel

## Installation

app\Providers\AppServiceProvider.php boot method

```bash
config(['app.locale' => 'id']);
Carbon::setLocale('id');
```

config/app.php

```bash
'timezone' => 'Asia/Jakarta',
'locale' => 'id',
'faker_locale' => 'id_ID', // optional if you can use faker
```