## Dropdowns
#### Races
- drop down button for choosing which race the texture is part of
#### Material
- the material used in certain texture (dictates the look of the texture, not the shape)
- copying from one item to another might be easier than designing your own
#### Texture map
##### Diiffuse and Specular 
- Diffuse --> flat coloolor
- Specular --> colors reflected with light, related to how intense they are (does not need to be black and white, you can reflect custom colors too :D)
- **Specular and Diffuse are usually used for old game items**
##### Normal and Multi
- Multi --> multiple types of textures together, hence the name multi
	- channels used in standard gear:
		- RED --> Ambient Occlusion (premade shadows in the texture, they are flat and don't move around with light sources)
		- GREEN --> Specular Intensity (how strong the light is reflected)
		- BLUE --> Gloss; basically opacity (simillar to specular map, makes things shiny, can make things opaque as well)
- Normal --> gives texture profoundity, a 3D look to textures; they make textures have 3D properties (instead of flat textures, they look like bumps althought they aren't realisticly there because it's computationally expensive)
	- channels used in standard gear:
		- BLUE --> Opacity of the texture
		- RED --> Light coming from the right side
		- GREEN --> Light coming from above
		- ALPHA --> Dictates which row in the color set each part of the texture will use (see texture map)
##### ColorSet
- Please make sure to click SAVE when you are done with your customizations
- Things you can pick in each row:
	- Diffuse Color --> just flat color
	- Specular Color --> reflection color
	- Emissive Color --> glowing color (usually black)
	- Gloss --> "opacity" of the ColorSet row (might be better to play around with it and see what happens)
	- Tile Material --> extra texture you can add
	- Tile Count X and Y--> it's the grid size of the ColorSet row (resolution)
	- Dye Template --> how the dye is going to affect the ColorSet row (play around with the options and check the reference sheet)
		- From reference sheet itself:
			- Templates ending with 00 --> Default colors
			- Templates ending with 01 --> Darker than the default color
			- Templates ending with 02 --> Lighter than the default color
			- Dyed Gloss Values increases as you go up in the 100's bracket from 1 to 24 (the higher the number, the glossier it's going to look)
		- You can choose to what the dye template should apply (Diffuse Color, Specular Color, Emissive Color)








