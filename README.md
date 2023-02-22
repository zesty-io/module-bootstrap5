# module-bootstrap5

 _Why install this module?_
>This module is required to be installed in every <img src="https://brand.zesty.io/zesty-io-logo.svg" style="margin-left:10px" width="15" height="15" alr="Zesty Logo"> **Zesty modules** that is dependent on the <img src="https://user-images.githubusercontent.com/55866499/217280250-1392ec17-2d71-4f8b-ae17-6a782a992b43.png" style="margin-left:10px" width="15" height="15" alr="Zesty Logo"> **Bootstrap framework** in order for the stylings to work. Aside from creating awesome content, it allows users to customize basic bootstrap default stylings such as: **Basic Font Stylings**, **Headers**, **Hyperlinks** and **Theme Colors**.


> **Warning**: Installing this module may affect existing content models that are using bootstrap stylings. Since the default bootstrap files will automatically be installed in the instance.

<br>

_How to customize bootstrap default stylings? Where to go?_
> In the **Zesty Instance Manager**, click **Settings** and choose under **WebEngine Styles & Fonts**

<img src="https://user-images.githubusercontent.com/55866499/217253593-51bdb961-5466-4d8d-85a2-56e113b393c5.png" width="25%" height="300">
<br>

📝Some of the sections may be [empty](https://user-images.githubusercontent.com/55866499/217271136-dafc9539-c807-4dc5-af81-30b0381f58e5.png), but you can add your own **"Style Variable"** settings using [Instance API](https://instances-api.zesty.org/#e90fa093-5d07-4ddb-a854-e1ec15701f47).

_What is Style Variables?_
> This variables are used as reference in the stylesheets which allows users to change the styles of the web page dynamically. Click [here](https://zesty.org/services/manager-ui/settings/less-variables#what-are-style-variables) to know more about Style Variables.

<br>

_What are the current available sections?_
### 1. Body Colors & Spacing
> The bootstrap theme colors: `Primary` `Secondary` `Success` `Info` `Warning` `Danger` `Light` `Dark` can be customized in this section using Color Picker.

<img src="https://user-images.githubusercontent.com/55866499/217267661-e4d32bd6-e63f-45f6-9eb0-c90ad779a8de.png" width="100%" height="400">
 
💡The styling will only apply to elements that has theme color classes. For example:  `class="text-primary"` `class="bg-dark"`.  

### 2. Typography
> In this section, you can customize basic font stylings for all texts including all headers. 

<img src="https://user-images.githubusercontent.com/55866499/217271679-2ac71ae0-2ceb-42bc-9a28-311b77284925.png" width="100%" height="400">

#### 2.1 Installing Fonts 
> To install a font, Under **Fonts** section click **Browse Fonts**
       
<img src="https://user-images.githubusercontent.com/55866499/217608615-fdaae863-d7f2-4a2d-8b71-46d094019ea5.png" width="25%" height="300">

>Choose a font style with sets of font weight e.g (400, 500, 700) that will be included in the installation.

<img src="https://user-images.githubusercontent.com/55866499/217614065-4e3e44b0-ff09-4b7b-84c0-c5c4eb2a46f0.png" width="100%" height="250">

<br>

> Scroll to the right side of the panel then click **Add** to apply the selected font.

<img src="https://user-images.githubusercontent.com/55866499/217614849-88baf076-c29d-4486-a63b-0f2f8d591914.png" width="100%" height="250">

<br>

> Go to **Installed Fonts** to see the fonts that are installed in the instance

<img src="https://user-images.githubusercontent.com/55866499/217615683-3d7631fe-eb26-49df-aaaf-f095a327de69.png" width="100%" height="250">


> All installed fonts will be available as an option to all settings with font picker.

<img src="https://user-images.githubusercontent.com/55866499/217616483-89aef796-6067-4129-a98f-7771e179fd14.png" width="100%" height="250">

💡Font will not be available in the **Typography** settings when its not yet installed. Font should be installed first in order to be available as a dropdown option in the settings.


### 3. Links
> Hyperlinks stylings in the web page can be customized in this section including basic hyperlinks properties such as: hover, clicked and visited.

<img src="https://user-images.githubusercontent.com/55866499/217314083-f7978774-e296-4c31-b7f0-aff2b17f5768.png" width="100%" height="400">


>💡Font colors settings only apply to default elements (without class). 
 > All color settings will based on the `Bootstrap Theme colors` from **Body Colors and Spacing** section
