# Pushover for HTTP

A simple HTTP api for the [Pushover](https://pushover.net) sercvice.
This is to make the service accessible for smaller devices that does not support https.

### Install via composer

Use the [Composer](https://getcomposer.org/) to install.

Add pushover-http to composer.json configuration file.
```
$ composer require nuccleon/pushover-http
```

And update the composer
```
$ composer update
```

## Usage

### Basic Example using wget and GET
```
wget "localhost/pushover-http/pushover-http.php/?user=foo&token=bar&priority=&message=baz&title=&url=&urlTitle=&sound=&html=&device=&date="
```