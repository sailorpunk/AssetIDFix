# AssetIDFix
I created this small python program to fix an issue at my work. The product content and images exist in 2 different databases, PPL and PAL (respectively). The images are referenced in PPL via PAL asset ID type, however, most of the assets are shared via URL which does not contain the correct asset ID type for PPL to create the reference. 
Example: The end of the URL will contain this 32 digit, alphanumeric code: ...Records/af58d22aa649440d9fc6b242010be94c but PPL cannot read it. The code must follow this format: f63df1bf-212f-4c0b-9ab7-ac8a01636289. 

This can become tedious when dealing with multiple assets at a time. 

Not any more!!
