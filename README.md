# ![LOGO](logo.png) Reisezentren-API **flow**ground Connector

## Description

A generated **flow**ground connector for the Reisezentren-API API (version v1).

Generated from: https://api.apis.guru/v2/specs/deutschebahn.com/reisezentren/v1/swagger.json<br/>
Generated at: 2019-05-07T17:40:13+03:00

## API Description

This REST-API enables you to query information about travel centers in Germany.

## Authorization

This API does not require authorization.

## Actions

### Get all station infos

#### Input Parameters
* `name` - _optional_ - A station name or part of it

### Get information about a station near a location

#### Input Parameters
* `lat` - _required_ - Latitude
* `lon` - _required_ - Longitude

### Get stations in a given radius

#### Input Parameters
* `lat` - _required_ - Latitude
* `lon` - _required_ - Longitude
* `dist` - _required_ - Radius

### Get information about a specific station

#### Input Parameters
* `id` - _required_ - Station id

## License

**flow**ground :- Telekom iPaaS / deutschebahn-com-reisezentren-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
