#Bozboz HTML Template

This is a template for kick starting a website. It includes {less} in the css directory for those that do, and a starting point for the css for those that don't.

As with everything, we are always evolving this. if you have any comments or suggestions please raise an issue or if you're feeling brave, branch and push. Simple.

The IE conditional HTML title hack, should only be included when needed, it should not be required by default - if you need it:

	<!--[if lt IE 7]> <html lang="en-us" class="lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
	<!--[if IE 7]>    <html lang="en-us" class="lt-ie9 lt-ie8"> <![endif]-->
	<!--[if IE 8]>    <html lang="en-us" class="lt-ie9"> <![endif]-->
	<!--[if gt IE 8]><!--> <html lang="en-us"> <!--<![endif]-->