Woof App
==================================

The Woof app is a list of dog photos with information about them including their name, age, and favorite activity. This app also uses Material Design to create a beautiful app experience for the user.
[Tutorial link](https://developer.android.com/codelabs/basic-android-kotlin-compose-material-theming?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-3-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-material-theming#6)

<div align="center">
    <img src="drawable-nodpi/woof.png" width="50%" alt="Woof App">
</div>

Introduction
------------
This came with starter code 

Content Covered
--------------
- Used Material Theme Builder
- Adding color palette to Themes
- Setting dynamicColor to match/not match device settings
- Used Card() composable to differentiate the list items
- Dimens files
- Adding darkPreview to previews
- Used `RoundedCornerShape()` for adding shape to cards and images
- Used `.clip()` to clips images into a shape
- `ContentScale.Crop` to crop the image to fit a shape
- Used and downloaded custom fonts from google fonts
- Used `Scaffold` and `TopAppBar` with `CenterAlignedTopAppBar` to create a top bar
- Used Expand More icon 
- Added IconButton() Composable with onClick for If/Else expanded scenarios
- Used remember() ad mutableStateOf() for onClick
- Modifier.weight() to set UI elements width/height proportions
- If/Else and setting onClick to hide/not hide more info and expand the item card
- Used Spring Animation
- Used animate*AsState() - particularly animateColorAsState for background changes based on expanded/not expanded
