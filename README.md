# Smile Store Locator

## Requirements

You need to have a modified version of the [Smile Store Locator](https://github.com/pimruiter/magento2-module-store-locator/tree/feature/stable) module installed and configured within your Magento 2 installation. This fork adds some extra's to the retailers:

- Description field
- Streetview field
- Facilities field
- Description and display from/to fields on special opening hours

It's also possible to use the original module but in that case you need to remove these extra's from the Blade views.

## Installation

```bash
yarn add gmap-vue -D
```

```bash
composer require rapidez/smile-store-locator
```

After that go to the configured url, default: `/stores`

## Views

If you need to change the views you can publish them with:
```bash
php artisan vendor:publish --provider="Rapidez\SmileStoreLocator\SmileStoreLocatorServiceProvider" --tag=views
```

## License

GNU General Public License v3. Please see [License File](LICENSE) for more information.
