```
This project created to instructor Dr. Adil Ghalib for course CPIT-490 FCIT,KAU
iOptical is an Shopping Android Mobile Application for Glasses and lenses.
```
<b> Created By: </b>
```
Majed Ahmed, Abdulrahman Alahmadi and Ismail Melebari
```
## MoltenBottonNavigationBar's Attributes

| Attribute     | Type          | Description   |
| ------------- | ------------- | ------------- |
| barHeight     | double        | specify a Height for the bar, Default is kBottomNavigationBarHeight  |
| domeHeight     | double        | specify a Height for the Dome above tabs, Default is 15.0  |
| domeWidth     | double        | If domeWidth is null, it will be set to 100  |
| domeCircleColor     | Color        | If a null value is passed, the domeCircleColor will be Theme.primaryColor  |
| domeCircleSize     | double        | The size of the inner circle representing a seleted tab. Note that domeCircleSize must be less than or equal to (barHeight + domeHeight)  |
| margin     | EdgeInsets        | Spacing around the bar  |
| barColor     | Color        | specify a color to be used as a background color, Default is Theme.bottomAppBarColor  |
| tabs     | List<MoltenTab>        | List of MoltenTab, each wil have an icon as the main widget, selcted color and unselected color  |
| selectedIndex     | int        | The currently selected tab  |
| onTabChange     | Function(int index)        | callback function that will be triggered whenever a [MoltenTab] is clicked, and will return it's index.  |
| curve     | Curve        | Select a Curve value for the dome animation. Default is Curves.linear  |
| duration     | Duration        | How long the animation should last, Default is Duration(milliseconds: 150)  |
| borderSize     | double        | Applied to all 4 border sides, Default is 0  |
| borderColor     | Color        | Applied to all border sides  |
| borderRaduis     | BorderRadius        | How much each angle is curved. Note that high raduis values may decrease the dome width. |
