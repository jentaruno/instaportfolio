## Data Pipelines
### Select Profile
- Prompt the user to input their Instagram profile name
- Ensure the name is valid (i.e. exists)
	- Query instagram -- check for 404?
	- If not, prompt the user to input a valid name

### Preview Photos
- Load 30 most recent photos
	- PIL -> image to store in memory
- Display photos in a grid
    - Array of photos


### Select Photos
- Allow user to select photos from loaded photos
    - Removes unselected photos from array

### Generate Portfolio
- For each selected photo:
	- Take photo
	- Place photo in template
- Convert to PDF/Docx
- Allow user to download