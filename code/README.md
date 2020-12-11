# Code Folder 

This folder contains the necessary files for reproducing the simulations.

* **simulations**  
	* [**charts**](https://github.com/Reivajar/A-BCN-Paradox/tree/master/code/simulations/charts): images results charts from notebooks *results_processing_{...}.ipynb*   
	* [**net01**](https://github.com/Reivajar/A-BCN-Paradox/tree/master/code/simulations/net01)  
		* [**data**](https://github.com/Reivajar/A-BCN-Paradox/tree/master/code/simulations/net01/data)
			* *grid01-bcn_06.net.xml*: network 01 XML file for SUMO.
			* *activitygen-bcn_06.stat.xml*: activitygen configuration file with demographic data for network 01.
			* *activitygen-bcn_06.trips.rou.xml*: resulting trips file from activitygen for network 01.
			* *activitygen-bcn_06.rou.xml*: routes definitions from trips from activitygen for network 01.
			* *activitygen-bcn_06.rou.alt.xml*: alternative routes definitions from trips from activitygen for network 01.    
			* *init_edgedata_additional_file.xml*: config. for extra output data for micro simulation called by *compar_002.sumo.cfg*.        
			* *init_edgedata_additional_file_meso.xml*: config. for extra output for meso simulation called by *compar_002_meso.sumo.cfg*.   
			* *compar_002.sumo.cfg*: configuration file for launching microscopic simulation.
			* *compar_002_meso.sumo.cfg*: configuration file for launching mesoscopic simulation.          	
		* *net01.ipynb*: Python notebook for running simulations for network 1.
	* **net02**  
		* **data**
			* *grid01-bcn_10.net.xml*: network 02 XML file for SUMO.
			* *activitygen-bcn_10.stat.xml*: activitygen configuration file with demographic data for network 02.
			* *activitygen-bcn_10.trips.rou.xml*: resulting trips file from activitygen for network 02.
			* *activitygen-bcn_10.rou.xml*: routes definitions from trips from activitygen for network 02.
			* *activitygen-bcn_10.rou.alt.xml*: alternative routes definitions from trips from activitygen for network 02.    
			* *init_edgedata_additional_file.xml*: config. for extra output data for micro simulation called by *compar_032.sumo.cfg*.        
			* *init_edgedata_additional_file_meso.xml*: config. for extra output for meso simulation called by *compar_032_meso.sumo.cfg*.   
			* *compar_032.sumo.cfg*: configuration file for launching microscopic simulation.
			* *compar_032_meso.sumo.cfg*: configuration file for launching mesoscopic simulation.
		* *net02.ipynb*: Python notebook for running simulations for network 2.
	* **net03**  
		* **data**
			* *grid01-bcn_50.net.xml*: network 03 XML file for SUMO.
			* *activitygen-bcn_50.stat.xml*: activitygen configuration file with demographic data for network 03.
			* *activitygen-bcn_50.trips.rou.xml*: resulting trips file from activitygen for network 03.
			* *activitygen-bcn_50.rou.xml*: routes definitions from trips from activitygen for network 03.
			* *activitygen-bcn_50.rou.alt.xml*: alternative routes definitions from trips from activitygen for network 03.    
			* *init_edgedata_additional_file.xml*: config. for extra output data for micro simulation called by *compar_052.sumo.cfg*.        
			* *init_edgedata_additional_file_meso.xml*: config. for extra output for meso simulation called by *compar_052_meso.sumo.cfg*.   
			* *compar_052.sumo.cfg*: configuration file for launching microscopic simulation.
			* *compar_052_meso.sumo.cfg*: configuration file for launching mesoscopic simulation.
		* *net03.ipynb*: Python notebook for running simulations for network 3.
	* **net04**  
		* **data**
			* *grid01-bcn_100.net.xml*: network 04 XML file for SUMO.
			* *activitygen-bcn_100.stat.xml*: activitygen configuration file with demographic data for network 04.
			* *activitygen-bcn_100.trips.rou.xml*: resulting trips file from activitygen for network 04.
			* *activitygen-bcn_100.rou.xml*: routes definitions from trips from activitygen for network 04.
			* *activitygen-bcn_100.rou.alt.xml*: alternative routes definitions from trips from activitygen for network 04.    
			* *init_edgedata_additional_file.xml*: config. for extra output data for micro simulation called by *compar_102.sumo.cfg*.        
			* *init_edgedata_additional_file_meso.xml*: config. for extra output for meso simulation called by *compar_102_meso.sumo.cfg*.   
			* *compar_102.sumo.cfg*: configuration file for launching microscopic simulation.
			* *compar_102_meso.sumo.cfg*: configuration file for launching mesoscopic simulation.
		* *net04.ipynb*: Python notebook for running simulations for network 4.
* *results_processing_meso_compar01-02-03.ipynb*: Python notebook for comparison of all simulations (micro- and mesoscopic) for all nets.
* *results_processing_meso_trial01.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 01 for all nets.
* *results_processing_meso_trial02.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 02 for all nets.
* *results_processing_meso_trial03.ipynb*: Python notebook for results processing and viz from mesoscopic simulations 03 for all nets.
* *results_processing_micro.ipynb*: Python notebook for results processing and viz from microscopic simulations for all nets.

