# Scatterplot with background image

This is a scatterplot that allows you to use a background image

## How to use
### Settings
Add object to your sheet. Fill in the settings under "Appearance".
The settings for "Background" include the the url to the background,
and the dimensions of the image.
The settings for "Plot" include the bounds of the axes, as well as
the dot size for the dots.
You can enable and disable selections from "Other"
### Dimension and Measures
After filling in the settings, add your dimension and measure(s).
There should be one dimension.
The first measure is the x coordinates
The second measure is the y coordinates
The third measure is an optional measure for color
To get the brushing effect on selection (recommended), use an expression like 
"Only( {<[Dimension Name]=>} X)"