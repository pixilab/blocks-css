Blocks custom CSS styling
=========================

As everything in Blocks is based on standard HTML5 web technologies, you can use common techniques such as CSS and web fonts to change the look of buttons, panels and blocks in general.

This repo contains various examples of such custom styling, along with blocks that use said styling, thich you can download and install into Blocks to try things out.

For more information on custom CSS styling, please refer to the documentation found here:

	https://int.pixilab.se/docs/blocks/custom_styling

The various CSS files found in this repo need to be copied into this folder of your Blocks installation (e.g., "PIXILAB-Blocks-root"):

	public/style/
	
You may need to create the _style_ folder if it doesn't already exist. 

For more complex installations, you may want to create separate style folders for different parts of the system, to keep things separate. But the examples found in this repo assumes CSS files live under public/style/. If you do rename/move CSS to another folder under _public_, then remember to update the Custom CSS file path in the blocks accordingly.

Put the contents of the StyledPanels directory into this folder of your Blocks installation (e.g., "PIXILAB-Blocks-root"):

	public/block/Main
	
This will put them into the Main group. If desired, you can put them into another block group of your choise.