# lpunpack

##### lpunpack.py - command-line tool for extracting partition images from super

    	usage: lpunpack.py [-h] [-p NAME] [-S NUM] SUPER_IMAGE OUTPUT_DIR

##### positional arguments:  
    	SUPER_IMAGE  
    	OUTPUT_DIR  

##### optional arguments:  
    	-h, --help show this help message and exit  
    	-p NAME, --partition NAME Extract the named partition. This can be specified multiple times or through the delimiter ["," ":"]  
    	-S NUM, --slot NUM !!! No implementation yet !!! Slot number (default is 0).  
    	--info, --no-info Displays pretty-printed partition metadata (default: False)
    	-f {text,json}, --format {text,json}  Choice the format for printing info
No implemetation extract A and B slot index
