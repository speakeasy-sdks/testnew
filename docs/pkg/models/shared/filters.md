# Filters

An array of filters are used to query requests.


## Fields

| Field                                                   | Type                                                    | Required                                                | Description                                             |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| `Filters`                                               | [][shared.Filter](../../../pkg/models/shared/filter.md) | :heavy_check_mark:                                      | A list of filters to apply to the query.                |
| `Limit`                                                 | *int64*                                                 | :heavy_check_mark:                                      | The maximum number of results to return.                |
| `Offset`                                                | *int64*                                                 | :heavy_check_mark:                                      | The offset to start the query from.                     |