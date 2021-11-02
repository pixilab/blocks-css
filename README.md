Blocks custom CSS styling
=========================

As everything in Blocks is based on standard HTML5 web technologies, you can use common techniques such as CSS and web fonts to change the look of buttons, panels and blocks in general.

This repo contains various examples of such custom styling, along with blocks that use said styling, thich you can download and install into Blocks to try things out.

For more information on custom CSS styling, please refer to the documentation found here:

https://pixilab.se/docs/blocks/custom_styling

The various CSS files found in this repo need to be copied into PIXILAB-Blocks-root/public/style/, or other suitable location under public.
	
For more complex installations, you may want to create separate style folders for different parts of the system. However, the examples included here assume that CSS files live under public/style/. If you rename/move CSS to another folder under _public_, then remember to update the Custom CSS file path in the blocks accordingly.

Put the contents of the StyledPanels directory into this folder of your Blocks installation (e.g., "PIXILAB-Blocks-root"):

	public/block/Main
	
This will put them into the _Main_ group. If desired, you can put them into another block group of your choise.

It is also possible to use Block-relative paths for custom CSS files. That's particularly useful for CSS that applies to a single block only, as this makes the CSS always follow the block (including when exporting/importing to zip). This is done by putting the CSS file into the block's directory, and then reference it from the Block beginning with a tilde, like this: 

    ~/my-style.css

Finally, you can provide a global spot CSS file using the _defaultSpotCSS_ option in the server configuration file. This will be automatically loaded into all Spots, and is useful for installation-wide, mandatory styling. More on this option here:

https://pixilab.se/docs/blocks/server_configuration_file#top_level_items
