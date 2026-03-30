---
title : "Workshops"
page_header_bg : "images/background/background-nn-1.jpeg"
date: 2025-02-01T14:13:24+02:00
description : "FOSS4G Europe 2026 workshops schedule (proposed)."
map_select_id: [1]
draft : false
layout: "single"
---

## Thursday, 2 July 2026

### 09:00 - 13:00

#### An Introduction to GeoServer3

Jody Garnett, Ian Turton

This workshop will cover the basics of setting up a GeoServer instance and
adding vector and raster data to it, and applying styles to the data to
produce a completed web map.

#### Doing Geospatial with Python

Tom Kralidis, Paul van Genuchten, Angelos Tzotsos, Just van den Broecke

This workshop will provide an introduction to performing common GIS/geospatial
tasks using Python geospatial tools such as OWSLib, Shapely, Fiona/Rasterio,
and common geospatial libraries like GDAL, PROJ, pycsw, as well as other tools
from the geopython toolchain.

#### eoAPI with STAC for Earth Data at scale

Felix Delattre

This interactive session will introduce you to eoAPI, a powerful cloud-native
framework that simplifies access to Earth Observation data. By the end of this
workshop, you will understand how to use eoAPI to catalog, discover,
visualize, and analyze geospatial data efficiently.

Workshop objectives:

- Explore how eoAPI can fit into your geospatial workflows
- Learn about STAC (SpatioTemporal Asset Catalog) and its role in Earth observation
- Explore the key components of eoAPI and how they work together
- Gain hands-on experience working with metadata, raster, and vector services

#### From Sensors to Services: Building Interoperable Environmental Data Platforms with istSOS4 and the OGC SensorThings API

Daniele Strigaro

Environmental monitoring infrastructures are increasingly required to support
high-frequency sensor data, heterogeneous observation types, and real-time
analytics, while ensuring interoperability, scalability, and long-term
sustainability. In this context, open standards and open-source technologies
play a central role in enabling data sharing across institutions, disciplines,
and national boundaries. This workshop introduces istSOS4, an open-source
implementation of the OGC SensorThings API, designed for the management,
publication, and analysis of spatio-temporal sensor observations.

The workshop targets practitioners and researchers involved in environmental
monitoring, smart cities, hydrology, climate studies, and geospatial data
infrastructures who wish to design interoperable sensor data platforms aligned
with FAIR data principles.

Participants will gain both conceptual and practical knowledge on how to
structure sensor metadata, ingest observations, and expose time-series data
through standardized web APIs. The workshop starts by framing the challenges of
modern sensor networks: increasing data volumes, diverse sensor typologies, the
need for near real-time access, and the integration of observations with
downstream analytics, dashboards, and decision-support systems.

A core focus will be the SensorThings API data model, including key entities
such as Things, Locations, Sensors, ObservedProperties, Datastreams, and
Observations. Particular attention will be given to modeling complex
environmental monitoring setups, including multi-parameter stations, mobile
sensors, and long-term monitoring networks. The workshop will demonstrate how
istSOS4 extends and operationalizes this model in real-world deployments,
supporting versioning, quality control, and efficient time-series handling.

Through hands-on sessions, participants will interact directly with an istSOS4
instance to:

- Register sensors and monitoring stations
- Ingest observations via RESTful endpoints
- Query time-series data using spatial, temporal, and attribute filters
- Visualize and export observations for further analysis

The workshop will also cover architectural aspects, including database
backends, performance considerations for high-frequency data, and integration
patterns with visualization tools, data analytics pipelines, and early-warning
systems. Real use cases from environmental monitoring projects such as
hydrometeorological networks, water quality monitoring, and climate adaptation
initiatives will be used to illustrate best practices and common pitfalls.

By the end of the workshop, participants will have a clear understanding of how
to design and deploy a SensorThings-based infrastructure using istSOS4,
enabling interoperable and standards-compliant access to sensor observations.

#### How to cloudify your QField project - from your phone

Berit Mohr

With the most recent upgrade to QField 4.0, it is suddenly possible to
cloudify any project from QField from any smart device. In this workshop the
participant will start in QField, not QGIS, collect data in the field and only
then synchronize it with the desktop.

Participants will learn how to:

- create and edit their own QGIS project
- optimally configure attribute forms
- cloudify their projects to QFieldCloud
- manage teams in QFieldCloud
- capture data using a mobile device and synchronize it back to the cloud

#### Building and Consuming Urban Digital Models with Open-Source Tools

Stefano Bovio

The workshop describes processes and tools used by the author and his team to
build and consume digital models for urban environments. Participants will gain
exclusive insights into the development of digital models in 3D Tiles format to
consume them within MapStore WebGIS framework.

### 11:00 - 13:00

#### MapStore, Development of an Extension

Stefano Bovio

This workshop will provide an introduction to building your own Extension, a
plugin component that allows adding custom functionality to the map viewer,
based on the MapStore Open Source framework. MapStore is a highly modular open
source WebGIS framework to create, manage, and securely share maps and
geospatial applications.

### 14:00 - 18:00

#### OGC APIs, an introduction with GeoServer

Andrea Aime

This workshop introduces OGC APIs, their story, objectives and structure, with
practical examples from the GeoServer. Join this workshop to get an update on
the APIs, to learn the current implementation progress as well as some
GeoServer unique features.

#### Getting Started with MapServer

Even Rouault, Seth Girvin

MapServer is an open source platform for publishing spatial data and
interactive mapping applications to the web. Learn how to set up and use one of
the fastest map engines in the world.

#### EOEPCA+ Exploitation Platform: Hands on Deployment and Usage

Richard Conway, James Hinton

EOEPCA+ provides an out-of-the-box solution for an EO Exploitation Platform
that integrates open source components interfacing through open standards.
Developed under an ESA project led by Telespazio, the EOEPCA Building Blocks
cover the full scope of an exploitation platform, from data discovery and
access, through processing and analytics to user workspace management.

This hands-on workshop introduces the core platform components comprising the
EOEPCA solution, providing an end-to-end experience that deploys and
demonstrates its capabilities within Kubernetes.

The workshop is perfect for beginners who have no prior EOEPCA knowledge and
only basic Kubernetes familiarity, but also welcomes those who have already
experimented with EOEPCA Building Blocks. Anyone interested in integrating the
EOEPCA components into their Exploitation Platform, or reusing them for Ground
Segment, EO Data Discovery, or Processing should join the session.

Participants will work through guided, browser-based tutorials hosted on our
online platform. Each tutorial runs against a live Kubernetes environment
provisioned in the cloud; no local software installation is required, just a
laptop and a GitHub account. The tutorials describe each step in context and
provide the necessary commands to deploy, configure, and utilize the platform
components.

Our team will be on hand throughout to guide, troubleshoot, and discuss how
these components can be adapted for different deployment scenarios. Everything
used in this workshop is fully open source and the tutorial source code is
publicly available on GitHub.

#### From Sensor to GeoJSON: Building an Open Source IoT Geo-Pipeline

Joram van der Vlist

Spatial datasets originate in field measurements, yet the transformation from
sensor reading to interoperable geospatial resource is often hidden in GIS
workflows. This workshop makes that "first mile" tangible by guiding
participants as they build and program their own hardware kit.

The kit uses a microcontroller, GNSS module, and environmental sensor of
choice. Measurements are transmitted to a provided Dockerized Python (FastAPI)
and PostgreSQL backend, where they are exposed as GeoJSON Features.
Emphasizing architectural clarity over complexity, the session demonstrates how
structured JSON, REST APIs, and relational storage underpin scalable
geospatial services, while outlining PostGIS and OGC API as natural extension
paths within an open standards ecosystem.

#### From QGIS to the Field and Back with Mergin Maps

Gabriel Bolbotina

This workshop provides a hands-on guide to the complete field data collection
workflow using QGIS and Mergin Maps.

Participants will learn how to:

- Configure QGIS projects by setting up background maps, smart forms, and tracking tools for offline use
- Collect data collaboratively by deploying projects to mobile devices and capturing data as a team, managing synchronization and version control
- Publish results by seamlessly sharing finished projects as interactive web maps for non-GIS stakeholders

### 14:00 - 16:00

#### Diving into pygeoapi Workshop

Tom Kralidis, Paul van Genuchten, Angelos Tzotsos, Just van den Broecke, Joana Simoes

pygeoapi is an OGC Reference Implementation supporting numerous OGC API
specifications. This workshop will cover publishing geospatial data to the Web
using pygeoapi in support of the suite of OGC API standards.

### 16:00 - 18:00

#### QGIS For You: Building a Plugin and Using Model Designer

Json Singh

If you are coming to FOSS4G you already know, or have heard, that QGIS is a
great tool for working with GIS datasets. You load data, manipulate, download,
upload, and there are thousands of plugins to choose from to make your life
even easier.

But let's say your workflow is not fitting in those available plugins, and you
have a custom Python script to make some changes to the QGIS layers. How can we
automate that or make it easier for the entire organization to run your
purpose-built script?

In this workshop we will look at two possible solutions:

- QGIS Plugin Development
- QGIS Model Designer

QGIS Plugin Development will include:

- Basic setup for plugin development
- Writing a basic Python script
- Some debugging practices
- Using QT Designer for the UI
- How to work with dependencies
- Sharing your built plugin with your team

QGIS Model Designer will include:

- Creating a model
- Saving and loading models
- Running custom Python scripts as steps
- Sharing models

After this workshop, participants should walk away with a basic understanding
of custom data manipulation capabilities of QGIS.

## Friday, 3 July 2026

### 09:00 - 13:00

#### Vector tiles with GeoServer

Andrea Aime

Learn how to build and serve vector tiles with GeoServer, and how GeoServer can
be well suited to mixed serving use cases (raster plus vector), dynamic data,
as well as handling different views based on the current user security
clearance.

#### EOPF Zarr Explorer Workshop: Web Visualization Techniques and Resources for the GeoZarr Specification

Ahmed

Presented under the efforts of the EOPF Sentinel Zarr Explorer project,
participants will learn how to leverage a modern, cloud-native tech stack to
interact with multidimensional data on object storage. We will go through the
various tools that support the development of visualizations of the GeoZarr
format.

Using Copernicus Sentinel data, we will look into building maps and dashboards
using eodash, OpenLayers, and TiTiler; write interactive narratives and
stories using EOxStorytelling; and visualize maps in notebooks using Jupyter
EOxElements.

#### Working with Point Cloud Data in QGIS

Kurt Menke

This workshop will teach you how to work with point cloud data in QGIS. You
will learn how to visualize point clouds in both 2D and 3D, style them to
highlight important features, and process and edit them to extract meaningful
information.

#### Animating spatio-temporal vector data with Gleo (WebGL)

Ivan Sanchez Ortega

A developer tutorial for the JS/WebGL Gleo library, with a technical focus on
how to create custom WebGL cartographic symbols.

### 11:00 - 13:00

#### Learn how to manage your geospatial data with PostgreSQL/PostGIS

Astrid Emde

PostgreSQL is a powerful, open source object-relational database system. It
can be extended with PostGIS which allows you to store and handle geospatial
data in the database. This combination is very powerful and provides many
possibilities.

Everything is possible in the database with some magic lines of SQL. This
workshop will help you with the first steps.

Many processes that you did before with your desktop GIS, for example
intersection, union, and buffer, can be easily done via SQL using PostGIS
functions.

### 14:00 - 18:00

#### Custom tile servers with MapLibre/Martin/Planetiler - base and overlays Workshop

Yuri Astrakhan, Bart Louwers

Create a tile server with the base map and some custom data. Build a website
with both the base map and custom data using MapLibre GL, Martin, PostgreSQL,
Planetiler, osm2pgsql, and related tools. Learn the tools needed to have your
own map server.

#### GDAL new command line interface: introduction and advanced topics

Even Rouault, Seth Girvin

GDAL 3.11 introduced a new command line interface, simply called `gdal`,
supplementing the traditional GDAL utilities such as `gdal_translate` and
`ogr2ogr`, to provide users with a more uniform, predictable, and
user-friendly experience.

#### Introduction to GeoNetwork

Jody Garnett, Jeroen Ticheler

GeoNetwork opensource is a fully featured catalog service and the most popular
catalog in Europe. This workshop provides hands-on experience setting up
GeoNetwork, using INSPIRE requirements as a guideline to explore
configuration.

#### Introduction to GeoNode

Mattia Giupponi

GeoNode is an open source web platform for the development of interoperable
spatial data infrastructures. The workshop will provide an introduction to
GeoNode starting with an overview of its functionalities for managing data,
users, and documents while also covering more advanced concepts.

#### iTowns, a JavaScript 3D data visualization framework: from the first steps to the creation of a complex 3D geographic web service

iTowns is an open-source, community-driven web framework designed for
geospatial data visualization, navigation, and interaction. It provides
seamless 3D rendering in a single, integrated package. Sponsored by the French
National Map Agency (IGN) and Ciril Group, iTowns benefits from institutional
and industry support to ensure long-term development and innovation.

Built with extensibility and interoperability in mind, iTowns out of the box
supports commonly used OGC open formats and protocols. This includes:

- fetching imagery and elevation data from WMS, WMTS, and TMS servers
- streaming large 3D datasets such as 3D Tiles and point clouds
- importing various vector formats including vector tiles, GeoJSON, and GPX
- and those requested by the community

#### Hydrological Analysis in QGIS

Hans van der Kwast

In this workshop, we will explore the diverse range of tools available in QGIS
for conducting comprehensive hydrological analysis. Participants will gain
hands-on experience with tools from GRASS, SAGA, WhiteboxTools, and PCRaster
processing provider plugins, as well as other specialized plugins designed for
hydrological studies.

Our interactive session will cover practical exercises on deriving streams and
catchments, and calculating essential morphometric parameters such as drainage
density, concentration time, and hypsometric curves. By the end of the
workshop, attendees will have a solid understanding of how to leverage QGIS for
hydrological analysis, enabling them to apply these techniques to their own
projects and research.

#### Writing spatial data utilities with GeoTools and JTS

Ian Turton

This workshop will introduce the GeoTools and JTS Java libraries to developers
who are looking to create portable scripts for cleaning, transforming, and
analyzing spatial data. GeoTools is a powerful geospatial library that allows
you to read and write a wide range of vector and raster data formats. It wraps
the JTS library to make features out of geometry objects from the JTS library
by adding attributes, and it also provides OGC compliant styling of those
features and rasters, as seen in the GeoServer web map server.

### 14:00 - 16:00

#### Create great Web Applications with Mapbender

Astrid Emde

Mapbender is a great open source solution for creating intuitive and
high-performance WebGIS applications. Mapbender offers a set of tools that you
can combine. This software solution enables users to quickly and easily publish
applications online without having to write a single line of code.
