# Changelog

## 1.2.0 (17-Oct-22)

* Properly handle flat params:

```ruby
client.tournaments 'type[]': [1, 2, 3] # requesting tournaments with IDs 1, 2, or 3
```

## 1.1.0 (29-Jul-22)

* Added requests for venues (thanks, @L-Eugene)

## 1.0.1 (28-Jul-22)

* Fixed endpoint reinitialization (thanks, @L-Eugene)
* Minor fixes

## 1.0.0 (12-Apr-22)

* Stable release

## 1.0.0.rc1 (11-Apr-22)

* Initial release