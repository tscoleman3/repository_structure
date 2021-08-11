# repository_structure
This is the mandatory framework repository to outline all new GitHub repositories for beginners who wish to stay organized. This is modeled from the structure I created with Melissa Moreno and the UF library team for a larger project's "organization" page that included over 20 repositories for numerous projects and reports. The outlined structure of this repository can be downloaded and copied at the start of a new repository. A repository needs to be specific to an individual project. Each repository is stand alone, and not reliant on any other repository.
  
### Permissions 
Only  `Admins` have full access to repositories, which you set when a repository is created or can edit in settings later on. Additional collaborators can be added in the repository through branches and to review/create pull requests to update the protected `master` branch. Every repository starts with a protected `master` branch and **each collaborator can have their own individual branch** (refer to the Github Workflow documentation). Individual branches will be named after the collaborators 1st initial, middle initial (if wanted), and last name, in all lowercase (e.g., Jennifer Moore - jmoore, Melissa Moreno - mmoreno, Tyler Steven Coleman - tscoleman, Stephen Parker - sparker).
  
### Naming Standards for each Repository  
Repositories are named in the following format:   
study_location_projectsummary  
  
Examples:  
bird_bb_monitoring (Big Bend camera and survey bird monitoring project)  
oys_fl_shiny_app_landings (Florida oysters landings Shiny App)  
lcr_quarterly_report (LCR repository for quarterly reports)  
oys_spat_bb_tile (Big Bend oyster spat tile project)  
oys_bb_transect_count_pop_trends (Big Bend oyster transect count population trends project)  
oys_gom_adaptive_management (Gulf of Mexico oyster adaptive management project)  
wq_bb_leaflet_map (Big Bend water quality leaflet map repository)  
oys_lcr_heights_trends (LCR oyster transect heights trends project)
  
### Naming Standards Overview
Every folder and file is required to be in lowercase, no uppercase (camelcase) nor all caps, all names with separate words need to include an underscore ( _ ) with **no spaces**, no dates in the names unless it helps with the descriptions of the content (i.e., discharge_1941_2018_fig.tiff, landings_1986_2018_analysis.R). Folder specific naming conventions are described in each folder's README.md.  
  
Mandatory folders for all repositories are, which are included in this skeleton repo structure:  
- data  
- script  
- writing  
  
Each of the above mandatory folders include naming conventions and additional optional/mandatory folders. Every folder **MUST** contain a README.md that will describe the folder and its contents. The README.md **MUST** also include file usage information, if necessary. 
  
### Rproject (repo_structure.Rproj)  
Every repository is required to have an Rproject. An Rproject is used to create an ecosystem that connects all folders and files within the repository. The Rroject is required to be named the same as the repository.  
