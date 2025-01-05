- Custom Extensions
	- BldDeps
		- Wraps rangeresolver to handle dependecy resolutions and updates.
		- Makes my decision to separate range resolver from the maven plugin a good idea.
		- NOW Needs support from `bld-wrapper.properties` for updating extensions.
		  :LOGBOOK:
		  CLOCK: [2025-01-04 Sat 06:24:08]--[2025-01-04 Sat 06:24:09] =>  00:00:01
		  CLOCK: [2025-01-04 Sat 06:24:10]
		  :END:
	- BldBnd
		- Wraps bndlib for OSGi support. Currently only adds a manifest file and doesn't handle full bnd dependency embedding etc
		- LATER Look at supporting full bnd functionality
-