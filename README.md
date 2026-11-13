# Georeminder optional timezone data

Public geographic data for the optional offline timezone lookup module. Application source code is not hosted here.

## Release tz-2020d-v1

- File: timezonemap-4.5-2020d.tar.zstd
- Size: 25,603,336 bytes
- SHA-256: f0a3e68af026fc13d9c50abcf0f3418c1114310f259a64de59e8d3fd7142736c
- Format: Zstandard-compressed TAR, TimeZoneMap 4.5 format
- Geographic dataset: 2020d (the same boundaries previously bundled with Georeminder). This is not a claim that the geographic dataset is current. UTC offsets and daylight-saving rules are supplied separately by Android's timezone database.

## Sources and attribution

The asset is copied without modification from the official Maven Central artifact us.dustinj.timezonemap:timezonemap-data:4.5.

- https://github.com/dustin-johnson/timezonemap (code: MIT; data: ODbL)
- https://github.com/evansiroky/timezone-boundary-builder
- © OpenStreetMap contributors, https://www.openstreetmap.org/copyright
- Data license: Open Database License 1.0. See DATA_LICENSE.

No user locations or task data are included. Clients download one common file, verify its pinned SHA-256 and perform coordinate lookups locally.
