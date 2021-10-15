# Biznes Elektroniczny

Projekt z przedmiotu Biznes Elektroniczny polega na odtworzeniu strony https://www.cinema-city.pl/#/.

## Wymagania systemu
* Oracle VM VirtualBox 
* System: Windows
* Web serwer: Apache Web Server 2.2 albo nowsze wersje
* PHP: PHP 7.2.5 albo następne
* MySQL: 5.6 minimalnie, najlepiej najnowsza wersja
* Server RAM: Tym więcej tym lepiej. Rekomendowane jest ustawienie alokacji pamięci na skrypt (memory_limit) na minimum 256 M

## Installation

Użyj git clone w celu zainstalowania projektu.

```git
git clone https://github.com/BognaGondek/project.git biznes_elektroniczny
```
Następnie doinstaluj niezbędne zależności.
```git
cd biznes_elektroniczny
build_project.sh
```
Powinien pojawić się dodatkowy folder third_party, a w nim ściągnięta shallow copy najnowszej wersji PrestaShop (https://github.com/PrestaShop/PrestaShop).
Aby zainstalować niezbędne elementy dla PrestaShop postępuj zgodnie z instrukcją: https://devdocs.prestashop.com/8/basics/installation/.

## Usage

```python
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
