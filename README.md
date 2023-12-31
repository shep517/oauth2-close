# Close Provider for OAuth 2.0 Client

## Installation

To install, use composer:

```
composer require shep517/oauth2-close
```

## Usage

Usage is the same as The League's OAuth client, using `\Shep517\OAuth2\Client\Provider\Close` as the provider.

### Authorization Code Flow

```php
$provider = new \Shep517\OAuth2\Client\Provider\Close([
    'clientId'          => '{close-client-id}',
    'clientSecret'      => '{close-client-secret}',
    'redirectUri'       => 'https://example.com/callback-url',
]);
```
For further usage of this package please refer to the [core package documentation on "Authorization Code Grant"](https://github.com/thephpleague/oauth2-client#usage).

## Credits

- [Jon Sheppard](https://github.com/shep517)
- [Chad Hutchins](https://github.com/chadhutchins) - piggybacked
- [All Contributors](https://github.com/shep517/oauth2-close/contributors)


## License

The MIT License (MIT). Please see [License File](https://github.com/shep517/oauth2-close/blob/master/LICENSE) for more information.
