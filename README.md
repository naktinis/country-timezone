country-timezone
================

Python library for mapping ISO 3166-1 alpha-2 country codes to Olson timezone names.

Usage example:
```python
all_us_timezones = timezones['US']                       # Returns a dict by coordinates
honalulu_timezone = timezone['US']['+211825-1575130']    # Returns 'Pacific/Honolulu'
```

Country names are compatible with GeoIP database (for example, there's `EU` "country").
