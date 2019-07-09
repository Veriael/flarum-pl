# Polish Language Extension

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Veriael/flarum-pl/blob/master/LICENSE) [![Latest Stable Version](https://img.shields.io/packagist/v/Veriael/flarum-polish.svg)](https://github.com/Veriael/flarum-polish)

**PL** Polska paczka językowa Flarum. Zawiera:

- Wszystkie tłumaczenia forum,
- Tłumaczenia panelu administratora (ACP),
- Tłumaczenia wszystkich domyślnych rozszerzeń dostarczanych wraz z instalacją Flarum.

**EN** Polish language pack for Flarum. Contains:

- All forum translations,
- Admin control panel (ACP) translations,
- Translations of all default extensions provided with Flarum installation.


### Instalacja

```bash
composer require veriael/flarum-polish
```

### Aktualizowanie

```bash
composer update veriael/flarum-polish
php flarum migrate
php flarum cache:clear
```

### Włączenie

Aby włączyć, wystarczy udać się do panelu administratora, po lewej kliknąć zakładkę "Extensions" i odnaleźć wśród innych rozszerzeń "Język Polski", po czym go zaznaczyć.

Możemy wybrać język polski z listy w prawym górnym rogu forum...

...albo ustawiamy język polski jako domyślny dla naszego forum:
Wchodzimy w "Podstawy", później znajdujemy "Domyślny język", wybieramy z listy "Język polski" i zatwierdzamy.


### Przydatne linki

- [on packagist](https://packagist.org/packages/veriael/flarum-polish)

