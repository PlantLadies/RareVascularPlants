This readme.txt file was generated on 2020--05--27 by Brynn Zalmanek and Sarrah Trapp


----------------------
PROJECT DEFINITION, SCOPE, AUDIENCE, & USERS
----------------------
1. Group Name: Rare Plants


2. Group Members: Sarrah Trapp, Brynn Zalmanek

3. Topic: Rare Plants by State in the United States


4. Target Audience: Biology researchers; Geography researchers; Academic researchers; Conservationists; National Parks or Horticulture curators
   A. User Stories
        a. Generic: Users looking for information on rare plants in various states across                	the United States for the purposes of research, conservation, curation, or study 	can find easily accessible and manipulatable data in one place by using this data 	package on GitHub. This data is otherwise locked in PDF or excel formats across 	different websites, making the data too spread out or manageable for easy use.
   	
	b. As a biology researcher, I want to find datasets on rare or endangered plant 	species by state so I can compare endangered plants by region.
    	
	c. As a geography researcher, I want to find datasets on rare and endangered plant 	species by region to create various maps of rare plants.

   	d. As an academic researcher, I want to access similar datasets for my students to 	use in order to have examples of clean data so they may practice their data 		management skills.

   	e. As an academic researcher, I want to access as many datasets on rare and 		endangered plants by state in order to perform different analyses regarding plant 	biodiversity in the U.S.

   	f. As a conservationist, I am interested in comparing datasets on rare and 		endangered plants across states in order to create visualizations of endangered 	plants that should be considered for conservation.

   	g. As a researcher at a national park, I would like to understand which plants are 	rare and endangered in the state of my national park so that we may consider 		conservation of certain plants under the protection of the National Parks.

   	h. As a horticulture curator, I am interested in understanding the rarest plants 	in the states so that I may consider adding them to either my personal  plant 		collection or my organization’s gardens or collections.

   B. Data was taken from PDF rigid datasets on the websites of the Indiana Department of    	Natural Resources, the Maryland Department of Natural Resources, New Hampshire 		Natural Heritage Bureau Division of Forests and Lands

   C. Relevance to quarter project - These user stories show the importance of the values 	of flexibility in the data, due to the vast range of applications, depending on 	the origin of the stakeholder. Largely, this means that the data needs to be 		extracted from the pdfs provided by the resource departments in order to allow it 	to be manipulated and compared in different contexts. The current format on the 	websites is already searchable, but, although the data is similar enough for 		comparison, the format and delivery makes direct comparison difficult without 		extraction and cleaning. For the purposes of this project, this endeavor will be 	good practice with the downstream function of making premade data usable for more 	than its intended audience.


5. Collective Goals: For this project, we want to focus on the challenges and decision-making process of integrating similar datasets in order to bring smaller areas of interest together to represent a larger area of coverage (states to U.S. or U.S. Regions). Through this, we will utilize data normalization tools such as OpenRefine, etc. as well as continue to engage with standards of tidy data and metadata structure. We are also interested in discovering the potentially unique nature of licensing for data that was produced by state or other government entities.


-------------------
POLICIES: DATA COLLECTION & TRANSFORMATION
-------------------
1. Policies
   a. Submission-Based
   b. All information additions must be of government/state department origin related to 	the subject of rare vascular plants and comply explicitly with the restrictions 	and specifications detailed in the following documents:
      		i. DataDictionary_1.0_06062020.csv
         		1. All elements, schema, and variables must be reflected in the 			additional data
      		
		ii. ControlledVocabulary_1.0_06062020.csv
         		1. All additional data must comply with the vocabulary system and 			organization dictated in this document
         		
			2. Any additional information that has, according to this 				structure, extra vocabulary may be organized and submitted in the 			format of this file to be considered for integration into the 				vocabulary
     
		iii. RareVascularPlants_1.0_06062020.csv
         		1. Additional data must be formatted according to the structure of 			this dataset
            			a. If granularity of descriptive terms are in conflict, 				please submit additional documentation to suggest how to 				adjust the incoming dataset to fit with the requirements 				of this repository.

      		iv. MetadataApplicationProfile_1.0_06062020.csv
         		1. Additional data must be accompanied by a MAP entry that 				conforms and follows the structure of this file.
   c. Content and Data File Size Extent have no limits for additional data for this 		collection. All submissions should be formatted as a .csv file type and should be 	in the format and containing the information and structure detailed above.

   d. Provide a copy of the state departments open data or data reuse policy for 		administrator review.


2. Transformation - Normalization
   a. Data should be edited, using the files named in the Collection Guidelines, and the 	following issues should be edited prior to submission:
      		i. Variable consistency/compliance

      		ii. Granularity congruence with the existing dataset

      		iii. Structure/Organizational adjustments must be made to allow for a 			direct-addition to the existing dataset

      		iv. Instances of Titlecase and lowercase represented in each variable must 		be addressed
      
		v. Follow standard normalization guidelines, not limited to:
         		1. Single Unit expressions per variable
         		2. Controlled Vocabulary
        		 3. Add a state variable to identify source


-------------------
DATA GENERAL INFORMATION
-------------------


1. Rare Vascular Plants of Indiana, Maryland, and New Hampshire (2019)


2. Source State Departments:
	a. Indiana Department of Natural Resources
	b. Maryland Department of Natural Resources
	c. New Hampshire Natural Heritage Bureau Division of Forests and Lands
        
3. Data was collected in the year 2019.


4. Data was collected in Indiana, Maryland, and New Hampshire.


--------------------------
SHARING/ACCESS INFORMATION
--------------------------


1. Publications that this data was derived from are located at: 
	a. https://www.in.gov/dnr/naturepreserve/files/np-etrplants.pdf?		fbclid=IwAR0CwirgN-rgH-g0jQbRUa8XN6WSl16Cli9kTXfifLFVEolMvVM1f5ajXFg

	b. https://dnr.maryland.gov/wildlife/Documents/rte_Plant_List.pdf?fbclid=IwAR10jASw8YJuppP6BflAoM4Jemze-3lFtb6gHyYhZD_yMIeKgEhq7LMa7QE

	c. https://www.nh.gov/nhdfl/documents/tracking-list-plant-general.pdf


2. The data can be publicly accessed online at:
https://github.com/PlantLadies/RareVascularPlants


3. LICENSE: The data contained in this dataset follows the Attribution-NonCommerical-NoDerivatives 4.0 International License (CC-BY-NC-ND 4.0):
	a. Overview: https://creativecommons.org/licenses/by-nc-nd/4.0/

	b. Legal Code: https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode

	c. Additionally, please review the state public and open data policies of Indiana, 	Maryland, and New Hampshire to comply with their data requirements. Some of this 	data is not allowed to be reused other than for educational purposes. This dataset 	was created under the requirements of a class assignment. The above data license 	was chosen to reflect the closed nature of reuse for this data in respect to the 	state policies. Please review that and the state policies thoroughly before using.


4. Recommended citation for the data: 
Indiana Department of Natural Resources, Maryland Department of Natural Resources, and New Hampshire Natural Heritage Bureau Division of Forests and Lands (2020). Rare Vascular Plants of Indiana, Maryland, and New Hampshire. [Rare_Vascular_Plant_Full_Integrated_Dataset.csv]. Retrieved from https://github.com/PlantLadies/RareVascularPlants.


--------------------
DATA & FILE OVERVIEW
--------------------


1. File List
        A. Filename: RareVascularPlants_1.0_06062020.csv
		I. Dataset that lists rare plants in the states of Indiana, Maryland, and 		New Hampshire and their endangerment rankings by state, federal, and 			global regions in 2019. 


        B. Filename: ControlledVocabulary_1.0_06062020.csv
		I. A spreadsheet of terms that are applicable to the ranking and ranking 		qualification variables in the dataset. They are divided by which rank 			level they define and/or qualify. These terms are the only terms allowed 		in the variables of Global_Rank, Global_Rank_Range, Global_Rank_Qualifier, 		Global_Taxon, Global_Taxon_Range, Global_Taxon_Qualifier, State_Rank, 			State_Rank_Range, State_Rank_Qualifier, State_Listing, Federal_Listing


        C. Filename: DataDictionary_1.0_06062020.csv
		I. The data dictionary describes the variables presented in the 			Rare_Vascular_Plant_Full_Integrated_Dataset.csv and includes variable 			names, definitions, format, value ranges, and notes.


        D. Filename: MetadataApplicationProfile_1.0_06062020.csv
		I. This metadata application profile describes the metadata elements, 			their formats, their controls, and their details. Built from Project Open 		Data (source: DCAT) and Darwin Core (source: Dublin Core)


        E. Filename: RareVascularPlantMetadata_1.0_06062020.csv
		I. Metadata for the Rare_Vascular_Plant_Full_Integrated.csv using the 			Metadata_Application_Profile.csv




2. Normalization Notes: Existing datasets taken from the Indiana Department of Natural Resources, Maryland Department of Natural Resources, and New Hampshire Natural Heritage Bureau Division of Forests and Lands, regarding rare vascular plant rankings of plants in those states. We worked to integrate those three datasets, and many of the issues we found were centered around granularity and conflicting or similar overlap of existing controlled vocabularies. Indiana was the primary issue, as Maryland and New Hampshire overlapped almost identically. We decided that the combined ranking terms should be separated into single values (ex. G1?T3T4 is now G1 | ? | T3 | T4) in order to allow data analysis to be as specific as possible. We put together our Controlled Vocabulary as a sort of dictionary to help us define each variable indicator and define the placement of it within our elements set. This helped us to eliminate repetitive or conflicting crossover between the datasets.


3. Naming conventions are based on a (title – version – date) structure. 
	A. MetadataApplicationProfile_1.0_06062020
   		a. Title: MetadataApplicationProfile
   		b. Version: 1.0
   		c. Date: 06062020

	B. Title
   		a. Contents Title of the file
   		b. Format
      			i. Titlecase

	C. Version
   		a. If content edits are made, update the decimal value
   		b. If structural or schematic edits are made, update the integer value

	D. Date
   		a. Eight-numeral code
   		b. MMDDYYY
   		c. No punctuation

	E. General
   		a. All sections are separated by an underscore

