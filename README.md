# AngularTest2
Setup Bootstrap 4 in asp.net core default Angular template

<h3>How to set up your development environment:</h3>

Visual Studio has it's own npm in External Webtools in options. That can cause an issue if you have it installed outside VS and I found that using that is a bad practice. So let's install our own:

 - https://nodejs.org/en/download/
 - verify in terminal if 'node -v' and 'npm -v' returns values
 - In Visual Studio go to Tools -> Options -> Projects and Solutions -> External Web Tools
 - move $(PATH) above $(VSINSTALLDIR)\Web\External
 - optionally you can add the path of the global npm installation to the top of the list (which is )
 - if you have an existing project using npm, than right click npm under Dependencies and Restore Packages
 
