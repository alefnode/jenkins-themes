![image](https://jenkins-themes.alefnode.com/images/jenkins-new-design-theme-logo.jpg)
# Jenkins Themes
Improving your user experience

**Updated for Jenkins version 2.222 and above**


Website: https://jenkins-themes.alefnode.com/  

## Features
* Just one small css file (35K)
* Embed minified SVG images
* Multiple ways to install
* Customize the color and logo using the [generator][generator]

## Screenshots
[![Screenshot jenkins-material-theme main](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-main.png)](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-main.png)      [![Screenshot jenkins-material-theme legend](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-legend.png)](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-legend.png) [![Screenshot jenkins-material-theme console](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-console.png)](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-console.png)
[![Screenshot jenkins-material-theme history](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-history.png)](https://jenkins-themes.alefnode.com/images/screenshot-jenkins-theme-material-history.png)


## Installation

### Using your Jenkins Hosting
1. Choose your color:
![image](https://jenkins-themes.alefnode.com/images/pallete.png)

2. Replace `{{your-color-name}}` in the URL by the chosen color: `https://jenkins-themes.alefnode.com/dist/material-{{your-color-name}}.css`

3. Download the generated URL

4. Upload the downloaded file to your web server

4. Click `Manage Jenkins`

5. Click `Configure System` and scroll down to `Theme`

6. Set the CSS field to the uploaded URL.

7. Click `Save`


### Using Stylish (only you will be able to see the awesome theme)

1. Follow the step 1 and 2 of the previous method

1. Copy the content of the file downloaded file

1. Install the [Stylish Chrome extension][stylish]

1. Go to Stylish options and click in `Write new style`

1. Paste the theme css in the code box

1. Click in `Specify` and set your jenkins domain

1. Click in `Save`

1. Go to your Jenkins website and enable the theme in the Stylish Chrome toolbar icon


## Development

CSS file are minified and compressed with Grunt. To prepare the environment:

```
npm install
grunt
```

This will generate the following file:
- dist/material-light.css

## Compatibility
- Jenkins 2.222 and above


If you are experiencing issues please let me know! Also, feel free to contribute!

## Thanks to
- [Jenkins Theme][afonsof-repo] for the Jenkins Themes based on repo
- [Simple Theme Plugin][simple] for the Simple Theme plugin
- [Google][google] for the the material design inspiration and the icons
- [Material Design Icons][material-design-icons] for some extra icons
- [Stylish][stylish] for making the test of new versions easy
- [canon-jenkins][canon-jenkins] for the base theme
- [@Heldroe][heldroe] for Firefox and Microsoft support
- [@bootstraponline][bootstraponline] for Jenkins native plugin

[afonsof-repo]: https://github.com/afonsof/jenkins-material-theme
[simple]: https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin
[google]: https://www.google.com/design/spec/material-design/introduction.html
[material-design-icons]: https://materialdesignicons.com/
[stylish]: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe
[canon-jenkins]: https://github.com/rackerlabs/canon-jenkins
[heldroe]: https://github.com/Heldroe
[generator]: https://jenkins-themes.alefnode.com/
[bootstraponline]: https://github.com/bootstraponline
