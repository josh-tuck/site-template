THE SAUSAGE FACTORY


MIXIN NOTES

Flex Box PARENT Variables (flex-parent):

flex-direction 		= 	row | row-reverse | column | column-reverse
flex-wrap 				= 	nowrap | wrap | wrap-reverse
justify-content 	= 	flex-start | flex-end | center | space-between | space-around | space-evenly
align-items 			= 	flex-start | flex-end | center | baseline | stretch
align-content 		= 	flex-start | flex-end | center | space-between | space-around | stretch


Flex Box CHILD Variables (flex-child):

order 						=		0 | (number)
flex-grow 				=		0 | (number)
flex-shrink 			=		1 | (number)
flex-basis 				=		auto | (number (%, em, px))
align-self: 			=		auto | flex-start | flex-end | center | baseline | stretch;


MAIN MENU NOTES

To get the main menu to work in WordPress:
1. Open /wp-includes/nav-menu-template.php
2. From line 51 remove {  'container' => 'div', 'container_class' => '', 'container_id' => '', 'menu_class' => }