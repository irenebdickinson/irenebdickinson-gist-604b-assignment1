# Open Source Repository Review

**Student:** Irene Dickinson
**Course:** GIST 604B – Open Source GIS  
**Assignment:** GitHub Repository Management  

---

## Repository 1

Gdal
(https://github.com/OSGeo/gdal)  

### Purpose
What does this project do?
GDAL is an open source library that translates between raster and vector geospatial data. QGIS uses it to read and write spatial data. 

### Repository Structure
What folders or files stand out?
 gcore/, ogr/ , fuzzers/

### Documentation
How helpful is the README?
The README is short but works well as a hub. It opens with build-status badges, gives a one-line summary of the project. A beginner wouldn’t learn how to use GDAL from the README alone, but it clearly shows where to find everything.
### Activity
Is the repository actively maintained?
Yes, it’s very actively maintained. GDAL 3.13 was released on 25 May 2026, and the latest stable release is 3.13.3, from 18 August 2026.

### Key Observation
One thing this project does well.
GDAL handles project governance and quality control very well. The README badgesmake it clear how decisions are made and how outsiders can get involved, which matters for a library that so much other GIS software relies on.
---

## Repository 2

QGIS
(https://github.com/qgis/QGIS) 

### Purpose
What does this project do?
QGIS is an open sources GIS program. 

### Repository Structure
What folders or files stand out?
debian/, vcpkg/, linux/
### Documentation
How helpful is the README?
The README is excellent and much more detailed than most. It reads almost like a product page, with a table of contents and sections on features, cartography, analysis, extensibility, and QGIS Server.
### Activity
Is the repository actively maintained?
Yes, it’s extremely active. The repo has over 99,000 commits, 14.3k stars, 3.5k forks, 5k+ open issues, and 59 open pull requests.
### Key Observation
One thing this project does well.
QGIS uses its README to serve both users and developers.

## Repository 3

GeoPandas
(https://github.com/geopandas/geopandas)

### Purpose
What does this project do?
GeoPandas is a Python library that adds geographic data support to pandas, a data library.
### Repository Structure
What folders or files stand out?
geopandas/, benchmarks/, examples/
### Documentation
How helpful is the README?
The README is very helpful, especially for beginners.
### Activity
Is the repository actively maintained?
Yes. Version 1.1.3 came out on March 10, 2026.
### Key Observation
One thing this project does well.
GeoPandas teaches by example.It shows short code snippets with their actual output and maps, so a new user can see what the tool does.
## Repository 4

Shapely
https://github.com/shapely/shapely
### Purpose
What does this project do?
This repository creates and analyzes flat geometric objects.
### Repository Structure
What folders or files stand out?
src/shapely/, benchmarks/, docker/ 
### Documentation
How helpful is the README?
The README is clear to read and explains how it relates to PostGIS. It is a bit more technical than other READMEs
### Activity
Is the repository actively maintained?
Yes. The most recent release was 2 weeks ago.l
### Key Observation
One thing this project does well.
It focuses well on one thing and runs with it. 
---

## Reflection

In 3–5 sentences, explain what you learned about how open source projects are organized.

Reviewing GDAL, QGIS, GeoPandas, and Shapely showed me that successful open source projects share a common foundation: a clear README, an open license, contributing guidelines,and Issues for tracking bugs and features. Their documentation styles differed. Seeing thousands of commits, frequent releases, and active issue tracking across all four made it clear that open source GIS is built through ongoing, transparent collaboration.


