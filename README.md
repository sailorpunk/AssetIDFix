# AssetIDFix
I created this small python program to fix an issue at my work. In the product content and images exist in 2 different databases, PPL and PAL (respectively). The images are referenced in PPL via PAL asset ID type, however, most of the assets are shared via URL which does not contain the correct asset ID type for PPL to create the reference. 
