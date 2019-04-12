# css_position_fixed_vs_absolute
Fixed vs Absolute positioning

* When position is fixed it's related to the view port
* When position is abvolute it's related to the container that has position set
 * If no position is set in container the default is static and the absolute will keep going up until it finds a container that has a position set
 * A good trick is to set the parents position to 'relative' this will make the position absolute to be set according to the parent you want.
