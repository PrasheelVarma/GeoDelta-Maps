# GeoDelta Maps

> **Analyse the Change.**

## Geospatial Scenario Analysis of Spatial Changes

GeoDelta Maps is a geospatial scenario analysis system that lets users
propose changes to a selected area and analyze what those changes would
bring through before-and-after comparison.

------------------------------------------------------------------------

## Project Identity

  -----------------------------------------------------------------------
  Element                             Final Definition
  ----------------------------------- -----------------------------------
  **Project Name**                    **GeoDelta Maps**

  **Academic Title**                  **Geospatial Scenario Analysis of
                                      Spatial Changes**

  **Tagline**                         **Analyse the Change.**

  **Philosophy**                      **A change should be understandable
                                      before it needs to become real.**

  **Core Question**                   **What happens when this place
                                      changes?**

  **Core Concept**                    Select an area → propose a spatial
                                      change → analyze what that change
                                      brings → compare results.
  -----------------------------------------------------------------------

### Meaning of GeoDelta

-   **Geo** --- geography, location and spatial information.
-   **Delta** --- the measurable difference between a current state and
    a changed state.
-   **Maps** --- the interactive spatial interface through which the
    change is explored.

The name reflects the central idea of the project: **understand the
spatial delta created by a proposed change.**

------------------------------------------------------------------------

## Overview

GeoDelta Maps focuses on one specific problem:

> **Given a place and a proposed spatial change, what changes would that
> modification bring to the area?**

Instead of treating a map as something to only view or navigate,
GeoDelta Maps treats it as a **scenario that can be examined and
compared**.

A user can:

1.  Select an area.
2.  Understand its current spatial state.
3.  Propose a modification.
4.  Generate a hypothetical scenario.
5.  Analyze the resulting spatial changes.
6.  Compare the original and modified states.

The actual geographic location is **not modified**. The proposed
modification exists as a **hypothetical digital scenario** for analysis.

------------------------------------------------------------------------

## Core Workflow

``` text
REAL PLACE
    ↓
CURRENT STATE
    ↓
USER-PROPOSED CHANGE
    ↓
HYPOTHETICAL SCENARIO
    ↓
ANALYSIS ENGINE
    ↓
BEFORE vs AFTER
    ↓
DELTA RESULTS
```

**Select Area → Understand Current State → Propose Change → Generate
Scenario → Analyze Changes → Compare Results**

------------------------------------------------------------------------

## What GeoDelta Maps Does

### 1. Understand the current state

The system combines available geographic and imagery information such
as:

-   Building footprints and building-related features
-   Roads and road networks
-   Land-use / land-cover information
-   Green spaces and vegetation
-   Commercial and other mapped features
-   Points of interest
-   Satellite imagery
-   Spatial relationships such as distance and proximity

The purpose is to establish a **current-state representation** before
applying a hypothetical modification.

### 2. Represent a proposed change

Users can explore changes such as:

-   Building modifications
-   Land-use changes
-   Road or spatial-infrastructure changes
-   Green-space changes
-   Conversion of selected areas between spatial categories

The system does not claim that a proposed change is legally permitted,
technically constructible, financially feasible, or environmentally
acceptable. It analyzes the spatial consequences represented by the
scenario.

### 3. Generate a hypothetical scenario

The proposed change is applied to a digital representation of the
selected area rather than to the actual geographic location.

This creates an **"if this changed..."** scenario.

### 4. Analyze the delta

The central output is the **difference between the current state and the
proposed state**.

Depending on available data and implemented modules, this can include:

-   Total area
-   Built-up area
-   Green/open area
-   Road coverage
-   Land-use distribution
-   Building count and footprint area
-   Green-space percentage
-   Distance and proximity measures
-   Accessibility/service coverage
-   Other spatial metrics derived from the scenario

### 5. Compare before and after

Results can be presented using:

-   Interactive maps
-   Scenario overlays
-   Metrics
-   Visualizations
-   Before/after comparisons

------------------------------------------------------------------------

# Existing Solutions and Project Positioning

GeoDelta Maps does **not** claim that scenario analysis is a completely
new concept. Mature tools already provide powerful mapping, GIS,
planning, engineering and simulation capabilities.

The project's differentiation is **what the experience is centered
around**.

## Google Maps / Google Earth / Google Earth AI

Google provides large-scale mapping, geographic exploration, imagery and
geospatial AI capabilities. In July 2025, Google introduced **Google
Earth AI**, describing geospatial models for areas including weather,
flood forecasting, wildfire detection, urban planning and public health.

Official source:\
https://blog.google/innovation-and-ai/products/google-earth-ai/

### Main focus

Google's ecosystem broadly supports:

-   Geographic exploration
-   Maps and navigation
-   Places and location information
-   Satellite and imagery-based visualization
-   Large-scale geospatial intelligence
-   AI-assisted geographic understanding

### GeoDelta Maps

GeoDelta Maps narrows the interaction to:

> **Select a place → propose a change → generate a hypothetical scenario
> → analyze the delta → compare before and after.**

It is therefore **not another general-purpose mapping or navigation
platform**.

------------------------------------------------------------------------

## ArcGIS Pro and ArcGIS Urban

Esri's ArcGIS platform provides professional GIS capabilities for
mapping, spatial analysis, imagery, data management, 2D/3D visualization
and geoprocessing.

ArcGIS Pro supports spatial analysis workflows including overlays,
proximity analysis, imagery analysis, modeling and automation.

Official sources:

-   https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview
-   https://doc.esri.com/en/arcgis-pro/latest/help/analysis/introduction/spatial-analysis-in-arcgis-pro.html

ArcGIS Urban supports scenario-based planning, including existing and
future scenarios, development/zoning or land-use scenarios, metrics and
scenario comparison.

Official sources:

-   https://doc.esri.com/en/urban/11.5/help/help-scenarios.htm
-   https://doc.esri.com/en/urban/11.5/help/help-analyze-plan.htm

### Main focus

Professional GIS/planning systems provide a broad toolkit for:

-   Detailed spatial analysis
-   Data management
-   Mapping and cartography
-   Zoning and land-use planning
-   Development scenarios
-   Advanced metrics
-   2D/3D GIS
-   Professional workflows and collaboration

### GeoDelta Maps

GeoDelta Maps does not attempt to reproduce the breadth of a
professional GIS platform.

It focuses on a smaller workflow that can be understood without
requiring the user to operate a full professional GIS environment:

> **Choose an area → describe the change → see the scenario → understand
> the resulting spatial delta.**

The focus is therefore **simplicity of the change-analysis workflow**,
not feature breadth.

------------------------------------------------------------------------

## Civil Engineering and Infrastructure Design Software

Professional civil-engineering software such as **Autodesk Civil 3D** is
designed for engineering design, modeling, analysis and documentation of
infrastructure projects.

Civil 3D supports workflows such as:

-   Site and land-development design
-   Road and highway design
-   Terrain/surface modeling
-   Drainage and pipe-network analysis
-   Engineering documentation
-   Model-based infrastructure design

Official source:\
https://www.autodesk.com/products/civil-3d/overview

### Main focus

These systems answer engineering questions such as:

-   How should infrastructure be designed?
-   What are the dimensions and geometry of the proposed design?
-   How should surfaces, corridors, drainage and other engineering
    elements be modeled?
-   How can the design be documented for implementation?

### GeoDelta Maps

GeoDelta Maps is **not a replacement for engineering design software**.

It operates at an earlier and more exploratory level:

> **"If this spatial change is proposed here, what measurable spatial
> characteristics would change?"**

It focuses on **scenario consequences and comparison**, not
construction-ready engineering design.

------------------------------------------------------------------------

## UrbanSim and Large-Scale Simulation

UrbanSim supports scenario modeling for land use and transportation and
can model interactions involving development, transportation, economics
and policy.

Official source:\
https://www.urbansim.com/scenario-modeling

### Main focus

Large-scale simulation systems can address:

-   Long-term development patterns
-   Transportation investments
-   Land-use policies
-   Demographic/economic assumptions
-   Accessibility
-   Housing and development
-   Interacting system variables
-   Forecasting and simulation

### GeoDelta Maps

GeoDelta Maps does not attempt to simulate an entire city, economy or
transportation system.

Its central question is narrower:

> **What spatial changes result from this specific user-proposed
> modification?**

The project focuses on **direct spatial comparison of a proposed
change**, rather than building a full predictive urban simulation model.

------------------------------------------------------------------------

# What Makes GeoDelta Maps Different?

The project does not claim superiority over these systems. Its intended
distinction is **focus**.

  -----------------------------------------------------------------------
  System Type             Primary Focus           GeoDelta Maps Focus
  ----------------------- ----------------------- -----------------------
  Maps / Earth platforms  Explore and visualize   Propose and analyze a
                          geographic information  spatial change

  Professional GIS        Broad spatial data and  A focused
                          analysis workflows      change-to-analysis
                                                  workflow

  Planning platforms      Zoning, land-use and    Direct user-proposed
                          development scenarios   spatial changes and
                                                  measurable deltas

  Civil engineering       Detailed engineering    Exploratory spatial
  software                design and              consequences
                          documentation           

  Large-scale simulators  Long-term system-level  Localized hypothetical
                          modeling and            change and before/after
                          forecasting             comparison

  **GeoDelta Maps**       **Propose a change →    **Focused
                          analyze what it brings  scenario-analysis
                          → compare the delta**   experience**
  -----------------------------------------------------------------------

The differentiation is therefore **not novelty of scenario planning
itself**.

The project focuses on:

1.  A simple user-driven change workflow.
2.  A clear current-state → scenario → analysis pipeline.
3.  Before/after comparison as the central result.
4.  Measurable spatial deltas rather than only visual changes.
5.  Accessibility for users who may not be GIS specialists.
6.  A deliberately narrower scope than full GIS, engineering and
    simulation platforms.

------------------------------------------------------------------------

# System Architecture

``` text
                  ┌───────────────────────┐
                  │         User          │
                  │ Select area + change  │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │    Flutter Frontend   │
                  │  Interactive Map / UI │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │     Flask Backend     │
                  │ Processing / APIs     │
                  └───────────┬───────────┘
                              │
             ┌────────────────┼────────────────┐
             ▼                ▼                ▼
      ┌─────────────┐  ┌─────────────┐  ┌─────────────┐
      │ Map / OSM   │  │ Satellite   │  │ Geospatial  │
      │ Data        │  │ Imagery     │  │ Processing  │
      └──────┬──────┘  └──────┬──────┘  └──────┬──────┘
             │                │                │
             └────────────────┼────────────────┘
                              ▼
                  ┌───────────────────────┐
                  │ Current-State Model   │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │ Scenario Generation  │
                  │ User Proposed Change  │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │     Analysis Engine   │
                  │    GIS + CV + Metrics │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │ Before vs After       │
                  │ Delta Visualization   │
                  └───────────────────────┘
```

------------------------------------------------------------------------

# Technology Stack

### Frontend

-   Flutter
-   Dart
-   Interactive map and scenario interface

### Backend

-   Python
-   Flask
-   API endpoints and processing pipeline

### Geospatial Data

-   OpenStreetMap
-   Overpass API
-   Nominatim
-   Geographic coordinates, roads, buildings, land-use and mapped
    features

### Satellite / Remote-Sensing Data

-   Satellite imagery
-   Image-derived spatial features where appropriate

### Computer Vision / Machine Learning

-   OpenCV
-   Image feature extraction
-   Texture and variance analysis
-   Edge detection
-   Image-based feature analysis/classification

### GIS / Geospatial Processing

-   Geographic-to-grid transformation
-   Polygon processing
-   Spatial overlays
-   Area calculations
-   Proximity and accessibility calculations
-   Road and feature processing
-   Scenario comparison

### Version Control

-   Git
-   GitHub

------------------------------------------------------------------------

# GIS and Computer Vision

### GIS

**Geographic Information System (GIS)** techniques handle spatial
geometry and relationships such as:

-   Building footprints
-   Roads
-   Polygons and areas
-   Distances
-   Proximity
-   Spatial overlays
-   Land-use distributions
-   Before/after geographic comparison

### Computer Vision

**Computer Vision (CV)** techniques are used where image-based
information is useful, especially for satellite imagery:

-   Image feature extraction
-   Visual/texture analysis
-   Edge information
-   Land-cover or feature classification
-   Green/vegetation-related visual information
-   Built-up or surface-related visual information

In simple terms:

> **GIS tells the system where spatial features are and how they relate
> geographically; CV helps extract or characterize information from
> imagery.**

------------------------------------------------------------------------

# Example Scenario

### User request

A user selects an area and proposes:

> **Convert a selected built/open area into a green space.**

### Before

``` text
Built-up Area       ██████████
Green/Open Area     █████
Road Coverage       ███
```

### Proposed Change

``` text
Selected Area
      ↓
Green Space
```

### After

``` text
Built-up Area       ███████
Green/Open Area     ████████
Road Coverage       ███
```

### Delta

The system can report changes such as:

-   Built-up area: decrease
-   Green/open area: increase
-   Green-space percentage: increase
-   Land-use distribution: changed
-   Proximity/accessibility metrics: potentially changed depending on
    the scenario

The exact result depends on the selected location, available data and
implemented analysis model.

------------------------------------------------------------------------

# Scope Boundary

## GeoDelta Maps is

-   A **scenario-based geospatial analysis system**
-   A tool for exploring **hypothetical spatial changes**
-   A system for **before-and-after comparison**
-   A way to understand measurable spatial differences caused by a
    proposed modification

## GeoDelta Maps is not

-   A navigation application
-   A general-purpose replacement for GIS software
-   A construction-ready civil engineering design tool
-   A legal or regulatory approval system
-   A complete digital twin of a city
-   A traffic forecasting system by itself
-   An autonomous city-planning or recommendation system
-   A replacement for professional engineering or planning studies

The system provides an analytical representation of a scenario; it does
not make implementation decisions for the user.

------------------------------------------------------------------------

# Data and Uncertainty

Geospatial analysis is only as reliable as the data and models used.

Where appropriate, GeoDelta Maps distinguishes between:

-   **Observed** --- directly available from a data source
-   **Derived** --- calculated from geographic or image data
-   **Simulated** --- created from the user's proposed scenario
-   **Estimated** --- inferred where exact information is unavailable

Estimated or simulated information should not be presented as
authoritative real-world data.

For example, if an exact building height is unavailable, an estimate
should not silently be presented as an exact measurement.

------------------------------------------------------------------------

# Future Scope

The current project focuses on the core 2D scenario-analysis workflow.

Potential future enhancements include:

-   Data-derived **3D scenario visualization**
-   More detailed building representation
-   Improved land-cover classification
-   More advanced accessibility and network analysis
-   Additional scenario types
-   Improved change detection from imagery
-   More data providers and geospatial sources
-   Richer scenario comparison and reporting
-   Additional environmental and infrastructure metrics
-   Confidence/uncertainty visualization

**3D is intentionally treated as a future enhancement, not a dependency
of the core system.**

------------------------------------------------------------------------

# Development Philosophy

> **A change should be understandable before it needs to become real.**

GeoDelta Maps follows a simple principle:

**Change → Calculate → Explain**

The user proposes the change.\
The system calculates measurable spatial differences.\
The system explains those differences through maps, metrics and
comparisons.

------------------------------------------------------------------------

# Project Goals

1.  Build a practical geospatial scenario-analysis workflow.
2.  Combine geographic data and imagery into a usable current-state
    representation.
3.  Allow users to create hypothetical spatial modifications.
4.  Calculate meaningful before-and-after spatial differences.
5.  Present those differences through an accessible interactive
    interface.
6.  Keep the system focused instead of trying to reproduce the full
    breadth of professional GIS, engineering or simulation platforms.

------------------------------------------------------------------------

# Project Status

**Status:** Active development

The repository contains the development work for the GeoDelta Maps major
project.

The implementation is being developed incrementally, beginning with the
core:

> **Current State → Proposed Change → Scenario → Analysis → Before/After
> Delta**

Advanced capabilities are treated as extensions of this core workflow
rather than requirements for the basic concept.

------------------------------------------------------------------------

# References

Official sources used for project positioning:

-   Google Earth AI ---
    https://blog.google/innovation-and-ai/products/google-earth-ai/
-   Esri ArcGIS Pro ---
    https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview
-   ArcGIS Pro Spatial Analysis ---
    https://doc.esri.com/en/arcgis-pro/latest/help/analysis/introduction/spatial-analysis-in-arcgis-pro.html
-   ArcGIS Urban Scenarios ---
    https://doc.esri.com/en/urban/11.5/help/help-scenarios.htm
-   ArcGIS Urban Metrics ---
    https://doc.esri.com/en/urban/11.5/help/help-analyze-plan.htm
-   Autodesk Civil 3D ---
    https://www.autodesk.com/products/civil-3d/overview
-   UrbanSim Scenario Modeling ---
    https://www.urbansim.com/scenario-modeling

------------------------------------------------------------------------

## Final One-Line Definition

> **GeoDelta Maps is a geospatial scenario analysis system that lets
> users propose changes to a selected area and analyze what those
> changes would bring through before-and-after comparison.**
