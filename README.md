# Change timezone laravel

app\Providers\AppServiceProvider.php on boot method

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

config/app.php (optional if you can use faker)

```bash
'faker_locale' => 'id_ID',
```