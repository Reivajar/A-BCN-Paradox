# Code Folder 

This folder contains the necessary files for reproducing the simulations.

* **simulations**  
	* **charts**: images results charts from notebooks *results_processing_{...}.ipynb*   
	* **net01**  
		* **data**
			* *grid01-bcn_06.net.xml*: network 01 XML file for SUMO.
			* *activitygen-bcn_06.stat.xml*: activitygen configuration file with demographic data for network 01.
			* *activitygen-bcn_06.trips.rou.xml*: resulting trips file from activitygen for network 01
			* *activitygen-bcn_06.rou.xml*: routes definitions from trips from activitygen for network 01.
			* *activitygen-bcn_06.rou.alt.xml*: alternative routes definitions from trips from activitygen for network 01.    
			* *init_edgedata_additional_file.xml*: config. for additional output data for micro simulation called by *compar_002.sumo.cfg*.        
			* *init_edgedata_additional_file_meso.xml*: config. for additional output data for meso simulation called by *compar_002_meso.sumo.cfg*.   
			* *compar_002.sumo.cfg*: configuration file for launching microscopic simulation.            
			* *compar_002_meso.sumo.cfg*: configuration file for launching mesoscopic simulation.          
			
		* *net01.ipynb*: Python notebook for running simulations for network 1.
	* **net02**  
		* **data**
		* *net02.ipynb*: Python notebook for running simulations for network 2.
	* **net03**  
		* **data**
		* *net03.ipynb*: Python notebook for running simulations for network 3.
	* **net04**  
		* **data**
		* *net04.ipynb*: Python notebook for running simulations for network 4.

* *results_processing_meso_compar01-02-03.ipynb*: Python notebook for comparison of all simulations (micro- and mesoscopic) for all nets.
* *results_processing_meso_trial01.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 01 for all nets.
* *results_processing_meso_trial02.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 02 for all nets.
* *results_processing_meso_trial03.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 03 for all nets.
* *results_processing_micro.ipynb*: Python notebook for results processing and viz from microscopic simulations for all nets.

