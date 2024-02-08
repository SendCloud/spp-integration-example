# Repository not maintained here anymore

You can find the plugin directly [here](https://gitlab.com/sendcloud-public/spp-integration-example) 


# Service point picker

This repository demonstrates how to integrate Sendcloud’s service point picker into a custom application.

## How to set up

1. Enable service points in your Sendcloud’s [API integration][docs-api-integration].
2. [Play around with the live example][live-example]. When selecting a service point, you’ll receive a service point object and a post number, if entered, as a result. You’ll need that data later when creating a new parcel through our parcels API (see **Create a parcel** in [our shipping API documentation][docs-parcel-api]).
3. Make sure to fill in the `to_service_point` and `to_post_number` parameters when sending the data over.

## Further reading

Please refer to the [service points API documentation][docs-api-service-points]. There you can determine the list of possible values to be used to [filter service points to certain carriers][live-example-carriers], for example.

## Officially supported browsers

- Edge (Blink, and Chromium)
- Firefox
- Chrome
- Safari

[docs-api-integration]: https://support.sendcloud.com/hc/en-us/articles/360024967612-Service-points-for-API-Integrations
[docs-api-service-points]: https://docs.sendcloud.sc/api/v2/service-points/
[docs-parcel-api]: https://docs.sendcloud.sc/api/v2/shipping/#create-a-parcel
[live-example]: https://sendcloud.github.io/spp-integration-example/
[live-example-carriers]: https://sendcloud.github.io/spp-integration-example#filter-carriers/
