# release-notes-21.05.000

As of now, we may use CalVer

## Instruments to provide data

* INTEGRAL
	* IBIS/ISGRI
	* JEM-X
	* SPI-ACS
* Antares
* Polar

## User accounts

* The user of ODA should login to use the service efficiently so that
	* They will receive an email upon job submission and completion
	* Upon login, the limit of INTEGRAL science windows is 500 instead of 50 for the anonymous user
	* Specific users can access private data upon usage agreement
	* Access to HPC resources can be granted abd the limit of 500 science windows raised upon special agreement

## New parameters

* The user can specify the number of science windows to be analyzed within a time interval
* the use can specify to access private data

## User experience

* A banner reports news and
* mailing list can be used for feedback
* python API code has more logging and functionalities, like asynchronous requests
* Images are visualized with js9 (an extension of ds9)
* Help pages are updated and extended

## Computation in University of Geneva Back-end facility

* a new Kubenetees cluster makes requests faster
* a powerful HPC cluster is available upon agreement for very large jobs

