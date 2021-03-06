## POS UI
POS UI is a demo POS UI based on [Core UI](https://coreui.io) free template.

For authentication this shop connects to the following service:

* [authentication](https://github.com/ricmoreira/authentication)

For other services this online shop connects to the following API gateway:

* [api_gateway_pos](https://github.com/ricmoreira/api_gateway_pos)

The gateway will expose the following services:

* [products](https://github.com/ricmoreira/products)
* [company_info](https://github.com/ricmoreira/company_info)
* [stocks](https://github.com/ricmoreira/stocks)


For full functionality, back end services must be up. So make sure to clone those repositories and put them up and running.

## Installation

### Clone repo

``` bash
# clone the repo
$ git clone https://github.com/ricmoreira/shop_ui my-project

# go into app's directory
$ cd my-project

# install app's dependencies
$ npm install
```

## Usage

``` bash
# serve with hot reload at localhost:4201.
$ ng serve

# build for production with minification
$ ng build
```
