# Exploring REST Design Practices in ML Web APIs: A Qualitative Approach

## Master Project Information Sciences

* At directory /papers you can find the papers referenced for the study.

* At directory /methodology the diagrams exhibiting the methodology followed for answering RQ1 and RQ2. They are provided in both .png image format (at the directory /exports), and .drawio, the format used for making the diagrams with the tool Drawio. <https://www.drawio.com/>
	
	* providers.xls contains the list of the ML cloud providers from which APIs were used as objects of analysis. The providers generated revenue from their cloud offering are also specified.

* At directory /thematic_analysis, you can find the outcome of thematic analysis, the method used for answering RQ1.
	
	* The directory /web_pages contains all the downloaded API documentation in .pdf format. Each .pdf file has annotations of highlighted text with codes as a result of the open coding phase.
	
		* The subdirectory "Ilia_codes" contains the same documentation file than its parent directory but annotated by another researcher.
	
	* data.xls contains several sheets resulting from the coding process.
	
		* "open coding" contains a compilation of annotations taken from API documentation with their corresponding codes, the file from which the annotation is taken from, and the ML platform it belongs to.
		
		* "axial coding" contains the hierarchical groups of codes merged into categories.
		
		* "urls" contains a mapping of the API documentation files used for the analysis, with the url from which it is downloaded.
		
		* "characteristics" contains a set of characteristics derived from the sub categories are grouped together, and compared per provider. They have been formatted into “yes” or “no” questions and have a category assigned.
		
		* "code definitions" contains a list of the most important codes with their corresponding definitions.
		
		* "endpoints" contains a summary of which type of endpoints do APIs have.
		
	* At directory /diagrams, you can find the diagrams emerged from the hierarchical relationship derived from the axial coding phase. Each diagram represents a thematic hierarchy. In addition, the HigherOrderDiagram represents the relationship of themes, and is the result from the selective coding phase. The diagrams are in a ".drawio" format, and the corresponding image exports can be found at the directory /exports.
	
	* At directory /examples, graphical representations in a ".drawio" format  and PDFs exports of examples of HTTP requests.
	
* At directory /rest_compliance you can find the outcome of the analysis of REST rule compliance on the studied APIs.
	
	* rules.xls contains several sheets indicating the outcome of the analysis of REST rule compliance on the studied APIs.
	
		* "rules" contains a list of references on both documentation and tested HTTP requests per rule, and per API, where it is visible whether the rule is complied or not.
		
		* "rules simplified" is a simplified version of the sheet "rules", where both sources documentation and HTTP requests have been merged. Each rule has been classified per API according to their adherence.
		
		* "compliance chart" contains a summary of the overall rule compliance.
		
		* "urls" contains the online locations where the API documentation has been downloaded from, and the URLs of the tested endpoints.
		
	* The file Thesis_REST_APIs.postman_collection.json is a postman collection containing all the HTTP requests used for the analysis. It can be easily imported to the software tool Postman. <https://learning.postman.com/docs/introduction/overview/>
	
	* The directory /web_pages contains all the downloaded documentation referenced at rules.xls. The documentation is in .pdf format and contains annotations in highlighted text where it is visible whether certain REST rules are either followed or violated by the APIs.
	
	* At directory /examples, graphical representations in a ".drawio" format (image exports at the directory /exports) of examples of REST rule violations.
