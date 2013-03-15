country-timezone
================

Python library for mapping ISO 3166-1 alpha-2 country codes to Olson timezone names.

When country-level is too coarse, you may choose from a list of timezones by
coordinates: latitude and longitude of the zone's principal location in ISO
6709 sign-degrees-minutes-seconds format, either +-DDMM+-DDDMM or
+-DDMMSS+-DDDMMSS, first latitude (+ is north), then longitude (+ is east).

Usage example:
```python
all_us_timezones = timezones['US']                       # Returns a dict by coordinates
honalulu_timezone = timezone['US']['+211825-1575130']    # Returns 'Pacific/Honolulu'
```

Country names are compatible with GeoIP database (for example, there's `EU` "country").
