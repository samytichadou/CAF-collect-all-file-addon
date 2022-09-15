# CAF - collect-all-files v0.3
Blender 2.80 Addon to collect all used external files from a project

Append menu **Collect External Files** to External data File menu.

Creates **blends_ressources** folder in root of main blend file with next structure:

	*scene name*_allfiles__*date*_report.txt - text file

	Subfolders:
		Images
		Movie Clips
		Blend Libraries - linked blend files
		Sequencer Strips
		Fonts

Relocate collected data in main project file.

