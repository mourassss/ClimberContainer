# Climber Container
<a href="https://github.com/ClimberAB/ClimberContainer/releases/download/v1.0.0/cl-container-plus_v1.0.0.zip
" target="_blank"><img src="./screenshots/downloadbutton.png?raw=true" 
alt="Download latest release" width="400" height="40" border="0" /></a>  
 > The Climber Container allows for multiple objects in a container and have possibility to change visualizations with a tab row. There is no limitiation to the number of tabs or the type of objects to include. It's like having sheets withing sheets and the extension can be used as a navigation system within your Qlik Sense sheet. Some of the potential use cases are:  
  

* Replacing the "Fast Change" functionality of QlikView.  
![Fast Change in Qlik Sense](./screenshots/ContainerWithIcons.GIF?raw=true "Fast Change in Qlik Sense")

* Simple menu system for different charts that you want to hide/show.  
![Tab dropdown menu](./screenshots/ContainerWithIconsAndText.GIF?raw=true "Tab dropdown menu")

* Drop down menu  
![Tab dropdown menu](./screenshots/ContainerWithDropDown.GIF?raw=true "Tab dropdown menu")

* Using container in container to create a hierarchy of charts.  
![Alt Text](./screenshots/ContainerInContainer.GIF?raw=true "Container in container")


Have you built something nice with our extensions? Screenshots and animated gifs of your work is always welcome.

## Getting started
1. Add your visualizations as master items
2. Add the master item to the extensions

![Container setup](./screenshots/ContainerSetup.gif?raw=true "Container setup")


## Settings and Features
**Tab positions**

There are five alternative tab placements:

![Alt text](./screenshots/ContainerTabPlacements.png?raw=true "Tab placements")


**Tab Size/Tab Text Size**

It's possible to change the size of the tab row with two options. Default and recommended size is medium for both settings. 

**Tab Text size**
| Options  	    | Description 	   |
| ------------- | -------------    |
| S  		  	| Small text size  |
| M 		  	| Medium text size |
| L  			| Large text size  |


**Tab Size**
| Options  	    | Description 	  |
| ------------- | -------------   |
| S  		  	| Small tab size  |
| M 		  	| Medium tab size |
| L  			| Large tab size  |

**Tab alignment**

The tabs can be aligned to the right, middle and to the left. This is not applicable for the Top Dropdown option. That list is always left aligned.

**Color options**

There are options for changing the color of the tab row background, the active tab/text and for the inactive tab/text. 

**Show underline**

Options for having the selected tab underlined

**Icon**

Option for only having a icon in the tab description or showing a icon before or after the text. 

**Sync tabs**

Option to sync multiple containers active tab. Tabs with same name will be synced

![Alt text](./screenshots/ContainerSyncTabs.gif?raw=true "Sync tabs")

**Other notes**

The extension is created as a generic solution to allow for many different use cases. For instance the tab labels allow an expression so it is possible to create more dynamic solutions and we allow containers to be placed inside containers. However, we still want the solution to be user friendly so we have not exposed more technical options like the ability to assign object id with an expression. We have also kept close to the Qlik Sense design and do not allow for specific font-sizes (in pixels) to retain the possiblities for responsive design. Please have these considerations in mind when/if you suggest improvements to the extension.

## Container +

The Container + version has more functionality then the basic version

* Action on click
	- Clear selections in field
	- Select value in field
	- Select values in field
	- Set a variable

* Use expression to activate a tab
	- When the expression evaluates to the tab name the tab will be active
	
* Hide tab bar
	- Hide the tab bar and use the expression option to activate a tab

Visit www.climber.eu for more information


## Limitations
1. No pdf/png export supported. (This also means no Nprinting support)

## Installation

1. Download the latest version
2. Qlik Sense Desktop
	* To install, copy all files in the .zip file to folder "C:\Users\\%Username%\Documents\Qlik\Sense\Extensions\cl-container"
3. Qlik Sense Server
	* See instructions [how to import an extension on Qlik Sense Server](http://help.qlik.com/en-US/sense/3.2/Subsystems/ManagementConsole/Content/import-extensions.htm)

## More Climber Extensions
Like this extension? Check out the other Climber made extensions below or contact us to let us build your own extension.

**Custom Report**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=mCb2t4aNppE
" target="_blank"><img src="http://img.youtube.com/vi/mCb2t4aNppE/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberCustomReport
* https://www.youtube.com/watch?v=mCb2t4aNppE  



**Selection Bar**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=4fxrphADRKw
" target="_blank"><img src="http://img.youtube.com/vi/4fxrphADRKw/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberSelectionBar
* https://www.youtube.com/watch?v=4fxrphADRKw  


**KPI**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=9zdfYshNel4
" target="_blank"><img src="http://img.youtube.com/vi/9zdfYshNel4/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberKPI
* https://www.youtube.com/watch?v=9zdfYshNel4  


**Cards**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=k_IEt8TvB_c
" target="_blank"><img src="http://img.youtube.com/vi/k_IEt8TvB_c/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberCards
* https://www.youtube.com/watch?v=k_IEt8TvB_c  


## Change Log

See [CHANGELOG](CHANGELOG.yml)

## License & Copyright
The software is made available "AS IS" without any warranty of any kind under the MIT License (MIT).

See [Additional license information for this solution.](LICENSE.md)




