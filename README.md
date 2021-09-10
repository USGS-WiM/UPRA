![WiM](wim.png)


# UPRA

GLCWRA (Great Lakes Coastal Wetland Restoration Assessment) leverages geospatial data to assess the restoration potential for wetlands along the coastline of the Laurentian Great Lakes. The Upper Peninsula Restoration Assessment (UPRA) is one of the GLCWRA study areas. 

___
## Developer Instructions

use node version 11.15.0

run `npm install` AND `bower install` to get dependencies after first cloning

`gulp watch` to run in browser with watch for debugging

`gulp build` to build project

**NOTE**: You **MUST** run the `gulp build` before committing and pushing to repo

## Deployment

Deploy to AWS S3 bucket glcwra.wim.usgs.gov, UPRA directory

## Built With

* [ArcGIS API for Javascript](https://developers.arcgis.com/javascript/) - Mapping engine
* [ArcGIS Server](http://server.arcgis.com/en/) - map services and geoprocessing services
* [NPM](https://www.npmjs.com/) - Dependency Management

## Contributing

Please read [CONTRIBUTING.md]() for details on the process for submitting pull requests to us. Please read [CODE_OF_CONDUCT.md]() for details on adhering by the [USGS Code of Scientific Conduct](https://www2.usgs.gov/fsp/fsp_code_of_scientific_conduct.asp).

#### Semver versioning/release tags

Advance the version when adding features, fixing bugs or making minor enhancement. Follow semver principles. To add tag in git,  type `git tag v{major}.{minor}.{patch}`. Example: `git tag v2.0.5`

First push tags to origin: `git push origin --tags` then, after pull request, upstream: `git push upstream --tags`  Note that your alias for the upstream repo may differ

## Authors

* **[Blake Draper](https://www.usgs.gov/staff-profiles/blake-a-draper)**  - *Lead Developer* - [USGS Web Informatics & Mapping](https://wim.usgs.gov/)


See also the list of [contributors](https://github.com/USGS-WiM/ORA/graphs/contributors) who participated in this project.

## License

This project is licensed under the Creative Commons CC0 1.0 Universal License - see the [LICENSE.md](LICENSE.md) file for details

## Suggested Citation
In the spirit of open source, please cite any re-use of the source code stored in this repository. Below is the suggested citation:

`This project contains code produced by the Web Informatics and Mapping (WIM) team at the United States Geological Survey (USGS). As a work of the United States Government, this project is in the public domain within the United States. https://wim.usgs.gov`


## About WIM
* This project authored by the [USGS WIM team](https://wim.usgs.gov)
* WIM is a team of developers and technologists who build and manage tools, software, web services, and databases to support USGS science and other federal government cooperators.
* WiM is a part of the [Upper Midwest Water Science Center](https://www.usgs.gov/centers/wisconsin-water-science-center).
