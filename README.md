# NCSSchema1516_Extended
 
NCSSchema1516_Extended is a set of schema definition files and samples to extend the standard definition to include additional data for migration between touchpoints at the end of a contract period.
 
## Installation
 
### Requirements
* None Specific
 
 
## Usage

added additional element <Custom> after <Sessions> to include additional fields 

*Additional Customer Fields included which could be imported but not part of original schema
*Addresses - Additional address lines not part of original schema
*Events - date based interations with customer (e.g forward appoints)
*Notes - generic customer notes
*References - additional references that might be useful to link data
*Diversity - additional information regarding diversity
*Actions - link to actionplan
 
```.NET
xsd.exe AbcCollectionSchema.xsd /c
```
 
## Development
CogniSoft plan to add additional elements as required, although a significant amount of work has already been performed with regards to mapping the DSS, DC1516 and general usage for NCS operations.
 
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
 
## License
The license for the schema has not changed, and remains under license to the National Careers Service.
