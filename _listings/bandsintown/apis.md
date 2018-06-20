---
name: Bandsintown
x-slug: bandsintown
description: Concert discovery has changed. Previously, fans would seek out concert
  dates, but with the rise of social media, fans now expect that information to come
  to them. Bandsintown simplifies concert discovery by allowing music fans to Track
  their favorite artists, see which shows they have RSVP&rsquo;d to &amp; share these
  shows with their friends. The concerts are then synced with their calendar, so fans
  are sure not to miss the show.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bands_in_town_logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Bandsintown
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/apis.md
specificationVersion: "0.14"
apis:
- name: Bands in Town Get artist information
  x-api-slug: bands-in-town
  description: Get artist information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bands_in_town_logo.png
  humanURL: http://news.bandsintown.com/home
  baseURL: https://rest.bandsintown.com////artists/{artistname}
  tags: Bands, Music, Concerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/artistsartistname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/artistsartistname-get-openapi.md
- name: Bands in Town Get all upcoming artist events or all past and upcoming events
    within a date range
  x-api-slug: bands-in-town
  description: artist events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bands_in_town_logo.png
  humanURL: http://news.bandsintown.com/home
  baseURL: https://rest.bandsintown.com////artists/{artistname}/events
  tags: Bands, Music, Concerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/artistsartistnameevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/artistsartistnameevents-get-openapi.md
- name: Bands in Town
  x-api-slug: bands-in-town
  description: Concert discovery has changed. Previously, fans would seek out concert
    dates, but with the rise of social media, fans now expect that information to
    come to them. Bandsintown simplifies concert discovery by allowing music fans
    to Track their favorite artists, see which shows they have RSVP&rsquo;d to &amp;
    share these shows with their friends. The concerts are then synced with their
    calendar, so fans are sure not to miss the show.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bands_in_town_logo.png
  humanURL: http://news.bandsintown.com/home
  baseURL: https://rest.bandsintown.com//
  tags: Bandsintown
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bandsintown/master/_listings/bandsintown/openapi.md
x-common:
- type: x-blog
  url: http://blog.bandsintown.com/
- type: x-blog-rss
  url: http://blog.bandsintown.com/rss
- type: x-developer
  url: http://www.bandsintown.com/api/overview
- type: x-github
  url: https://github.com/bandsintown
- type: x-twitter
  url: https://twitter.com/Bandsintown
- type: x-website
  url: http://news.bandsintown.com/home
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---