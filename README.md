Everysport API Python 
=====================

A Python wrapper for the Everysport API. 


Example usage:


	import everysport

	events = everysport.Events(EVERYSPORT_APIKEY)

	for event in events.today().load():
		print event


	allsvenskan = events.leagues(57973)
	for event in allsvenskan.today().load():
		print event


