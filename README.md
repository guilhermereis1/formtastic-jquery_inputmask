# Formtastic jQuery Inputmask
Easily add jquery inputmask to your Formtastic (or ActiveAdmin).

## Installation
**1. Include to your Gemfile**
```ruby
gem 'formtastic-jquery_inputmask'
```

**2. Require javascript dependency**
```javascript
//= require formtastic/inputmask
```

**3. Load locale or other [inputmask](https://github.com/guilhermereis1/formtastic-jquery_inputmask/tree/master/vendor/inputmask/dist) file as you want**
```javascript
//= require formtastic/inputmask/locales/pt-BR
//= require inputmask/phone-codes/phone-us
```

*p.s. it auto adds jquery as a dependency in your project*

## Usage
```ruby
f.input :created_at, mask: 'datetime'
f.input :date, mask: { alias: 'datetime', inputformat: 'dd/mm/yyyy' }
```

Guilherme Reis

* https://www.worldcode.com.br

![alt text](https://res.cloudinary.com/dgxdamqhe/image/upload/v1545168182/logo_wc_png_irc4l2.png)
