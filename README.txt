Directory structure:
source/ - Contains source documents and code
	code/ - Contains the code
		EMonCMSLib/ - Arduino Code for radio board
			libraries/ - Contains all libraries for compilation
				EMonCMS/ - Communications stack for this project
			doc/pin_mapping.txt - Hardware pin map
		EMonNodeManager/ - Java program to configure nodes
		PTMNRS485/ - Program running on sensor board
		UNUSED_CODE/ - Developed but unused code
			PTMNRS485SimpleModubus/ - Sensor interface code using simple modbus master lib
	documents/ - contains the source documents and higher reolsution images
		circuit_diagrams/ - contains high res circuit diagrams
		class_diagrams/ - contains high res class diagrams
		feature_list.odt - Features list
		report.odt - The final report
	extra/ - misc files relevant to project
		calib_data_0-1_bar.txt - calibration data for the 0-1 bar sensor at sea level
		power_usage.txt - power usage of radio board
		project_log.txt - a breakdown of time use
tis4_mmp.pdf - The final report as a PDF