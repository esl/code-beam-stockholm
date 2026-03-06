---
audience:
- intermediate
- proficient
tags: geospatial, web
title: "From STAC APIs to Interactive Maps: Building a Sustainable Geospatial Stack with Elixir"
speakers:
- _participants/Alexander-Kmoch.md

---
In geoinformatics, the standard toolkit leans heavily on Python. But for building scalable and maintainable web apps and services for environmental data we desired a better mix of productivity and reliability. At our lab in Tartu, we have embraced Elixir and Phoenix to build the core infrastructure for our geospatial data cataloguing and mapping needs. Our current work centres on a datacube portal and a STAC API implementation designed to provide seamless access to many large spatial datasets. By leveraging Phoenix LiveView and MapLibre, we have built an interactive map visualisation platform that reduces the complexity of front-end and backend for our small dev team. As we started to feel more comfortable with Elixir, we also started with orchestration, managing hundreds of map layers through established software GeoServer via our open-source geoserver_config_ex library. We also elaborate on our choice and path towards Elixir for our generally Python-dominated domain.


**Talk objectives:**

* to hare the "Why Elixir?" from a university perspective and discuss why a geoinformatics lab chose Phoenix and LiveView over more traditional stacks to build a datacube portal and STAC API, including the technical and human reasons.

* to advertise geospatial orchestration on the BEAM and explain how we use Elixir to integrate established "heavyweight" geospatial software like GeoServer and satellite data for our stakeholders. We will discuss the development of our open-source geoserver_config_ex library and how we manage hundreds of map layers via REST.

* to showcase how we use LiveView and MapLibre to build map viewers and data-cataloguing and editing interfaces without getting lost in the complexities of state management of SPA setups, JavaScript dependencies, or brittle Python deployment challenges

* an optimistic reflection on the ecosystem: We will share our experience on building authentication with Keycloak and using Livebook for internal data workflows, and how we approach geo data with the available BEAM ecosystem to work for GIS

**Target audience:**

* This talk is for developers, architects, and product managers who are interested in a "niche" but real-world application of Elixir. It will be especially useful for those who need to orchestrate legacy third-party software via APIs or those looking for alternatives to the traditional Python/JavaScript stack for orchestrating heavy geo data in light-weight web applications. We don't expect the audience to know what a "SpatioTemporal Asset Catalog (STAC)", or "Cloud-optimised GeoTIFF", or a "Datacube" is, and we will give a gentle overview and introduction to the domain. But we want to focus on the technical patterns, the libraries we built, and the architectural decisions that make this stack work for us, and also how the human element was important, our small team of developers in a university lab of geographers, and the decisions about programming languages.
