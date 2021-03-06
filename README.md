# Getting Started

The SVRF API allows you to supercharge your project or app with the first and largest search engine for immersive experiences. We make it simple for any developer to incorporate highly immersive experiences with all kinds of applications: virtual reality, augmented reality, mixed reality, mobile, and web.

The SVRF API is based on REST principles, allowing it to integrate cross-platform. Our endpoints return responses in [JSON][]. We support [CORS][], allowing you to access immersive experiences indexed by SVRF on your own web domains. We provide a variety of resolutions, projections, and file formats to support most modern clients.

SVRF API Documentation is available at [https://developers.svrf.com][SVRF Dev].

## Access and API Keys

To  generate a SVRF API Key, create an account on [www.svrf.com][SVRF] and go to the *Apps* section of the [User Settings][SVRF User Settings] page.

See our [terms of service][TOS] for restrictions on using the SVRF API, libraries, and SDKs.

If you have questions or need support, please [create a ticket][Support].

## API Highlights

## Search Endpoint

[The SVRF Search Endpoint][Docs Search] brings the power of immersive search found on [SVRF.com][SVRF] to your app or project. Our search engine enables your users to instantly find the immersive experience they're seeking. Content is sorted by the SVRF rating system, ensuring that the highest quality content and most relevant search results are returned first.

### Trending Endpoint

[The SVRF Trending Endpoint][Docs Trending] provides your app or project with the hottest immersive content - curated by real humans. The experiences returned mirror the [SVRF homepage][SVRF], from timely cultural content to trending pop-culture references. The trending experiences are updated regularly to ensure users always get fresh updates of immersive content.

## API Libraries

You can use SVRF API libraries to encapsulate endpoint requests:

* [C#][CSharp]
* [Java][]
* [Javascript][]
* [Swift][]

## SDKs

You can use the SVRF SDKs to encapsulate endpoint requests and render 3D face filters in your application.

* [iOS SDK][]

## Attribution

### Authors and Site Credit

At SVRF, we believe in giving credit where credit is due. Do your best to provide attribution to the `authors` and `site` where the content originated. We suggest using the format: __by {authors} via {site}__

If possible, please provide a way for users to discover and visit the page the content originally came from (`url`).

### Powered By SVRF

As per section 5 A of the [terms of service][TOS], __we require all apps that use the SVRF API to conspicuously display "Powered By SVRF" attribution marks where the API is utilized.__

## Rate Limits

The SVRF API has a generous rate limit to ensure the best experience for your users. We rate limit by IP address with a maximum of 100 requests per 10 seconds. If you exceed the rate limit, requests from the requesting IP address will be blocked for 60 seconds.

[API Email]: mailto:api@svrf.com
[CORS]: https://en.wikipedia.org/wiki/Cross-origin_resource_sharing
[CSharp]: https://github.com/SVRF/svrf-csharp-client
[Docs Search]: https://developers.svrf.com/#tag/Media/paths/~1vr~1search?q={q}/get
[Docs Trending]: https://developers.svrf.com/#tag/Media/paths/~1vr~1trending/get
[iOS SDK]: https://github.com/SVRF/svrf-ios-sdk
[Java]: https://github.com/SVRF/svrf-java-client
[Javascript]: https://github.com/SVRF/svrf-javascript-client
[JSON]: http://www.json.org/
[Support]: https://github.com/SVRF/svrf-api/issues/new/choose
[SVRF]: https://www.svrf.com
[SVRF Dev]: https://developers.svrf.com
[SVRF User Settings]: https://www.svrf.com/user/settings
[Swift]: https://github.com/SVRF/svrf-swift4-client
[TOS]: https://www.svrf.com/terms
