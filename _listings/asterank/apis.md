---
name: Asterank
x-slug: asterank
description: Asterank is a scientific and economic database of over 600,000 asteroids.
  Weve collected, computed, or inferred important data such as asteroid mass and composition
  from multiple scientific sources. With this information, we estimate the costs and
  rewards of mining asteroids. Details on orbits and basic physical parameters are
  sourced from the Minor Planet Center and NASA JPL. Composition data is based on
  spectral classification and size. Our calculations incorporate conclusions from
  multiple scientific publications in addition to cross-referencing known meteorite
  data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/asterank.png
x-kinRank: "8"
x-alexaRank: "0"
tags: API Provider
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/asterank/apis.md
specificationVersion: "0.14"
apis:
- name: Asterank Kepler Project
  x-api-slug: asterank-kepler-project
  description: Asterank provides a queryable database containing information on over
    2,000 exoplanets and unconfirmed &quot;objects of interest&quot; collected through
    NASA&#039;s Kepler Project. The Kepler spacecraft detects planets outside our
    solar system (a.k.a. exoplanets) by observing the decrease in light caused when
    a planet passes in front of a star. The Asterank Kepler Project database is updated
    nightly from the Kepler Data Explorer. Because Asterank&#039;s database runs on
    MongoDB, queries must adhere to Mongo&#039;s JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/asterank.png
  humanURL: http://www.asterank.com/
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/asterank/openapi.md
- name: Asterank Minor Planet Center
  x-api-slug: asterank-minor-planet-center
  description: The International Astronomical Union&#039;s Minor Planet Center (MPC)
    is responsible for the designation of minor bodies found within our solar system.
    This includes minor planets, comets, and natural satellites. The MPC is also responsible
    for collecting, computing, checking, and disseminating astrometric observations
    and orbital information for those minor bodies.The Asterank MPC API enables users
    to apply constraints to the more than 600,000 asteroids documented in the MPC&#039;s
    MPCORB.DAT files. Because the Asterank database runs on MongoDB, queries must
    use Mongo&#039;s JSON format. Information in the Asterank MPC database is updated
    nightly.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/asterank.png
  humanURL: http://www.asterank.com/
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/asterank/openapi.md
- name: Asterank SkyMorph / NEAT
  x-api-slug: asterank-skymorph--neat
  description: The Asterank SkyMorph / NEAT API provides a RESTful JSON interface
    to NASA&#039;s SkyMorph archive. SkyMorph helps researchers to find variable,
    moving, or transient celestial objects by providing access to images and catalogs
    generated by the Near Earth Asteroid Tracking (NEAT) program. These include hundreds
    of thousands of images that, taken together, cover a large portion of the sky.
    Each region of the sky is usually observed several times per night and is subsequently
    revisited on a monthly or yearly basis.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/asterank.png
  humanURL: http://www.asterank.com/
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/asterank/openapi.md
x-common:
- type: x-website
  url: http://www.asterank.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---