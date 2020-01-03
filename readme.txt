Design files and helpers for a modular microdrive and headstage.

Authors: Ezequiel Arneodo, Corinna Lorenz, Richard Hahnloser.

Documentation in progress.

Deliverables:

 
 - rhd_2132_with_squiggle_logic: headstage module with intan chip, squiggle drive and controller/hall sensor for position monitoring. 
				 Molex connector for the probe.
	TODO: ready, produced with swisspcb (electric), mounted with Hybrid S.A
		
	main files:
	 - rhd_board.PrjPcb (altium project)

 - rev_1_mechanic: mechanical designs that go together with rhd_2132_with_squiggle_logic.
	TODO: ready, negotiating production with and with eth physics workshop (mechanical).

	main files:
	 - drive_rev_1.SLDASM

 - probe: pcb for assembly of the carbon fiber bundle probe. Connects to rhd_2132_with_squiggle with molex connector.
 	TODO: ready, negotiating production with swisspcb (electric)
	
	main files:
	 - probe_rev1.PrjPcb

 - altium_libraries: libraries of components with relevant 3d models (for connectors/microdrive).



