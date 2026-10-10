**Adobe Color Palette Used**
 #0F172A, #2563EB, #1D4ED8, #FFFFFF, #F8FAFC

 My Adobe color palette is accessible here: "https://color.adobe.com/create/color-wheel?color-palette=0F172A%2C2563EB%2C1D4ED8%2CFFFFFF%2CF8FAFC&color-palette-name=My+Color+Theme"

 I used this color palette in order for the website to be easily readable to everybody. I chose a color scheme that I thought and understood was compliant with modern accessibility standards.

**Gradients Used**
 In my Code I used a linear gradient for the following webpage elements: Navigation buttons in the "header nav a" element and its ":hover" state across every page.

 I also used an angled linear gradient of 135 degrees in the following webpage elements: "header, footer" across all pages + every CSS file.

**All BASE Code used was sourced from the lectures with the exception of minor CSS elements such as: "text-decoration:none; , transition:transform 0.2s ease, box-shadow 0.2s ease;" used within the CSS files.**

These css elements were sourced from the following links:"https://www.w3schools.com/css/css_text_decoration.asp", "https://thoughtbot.com/blog/transitions-and-transforms", and "https://www.w3schools.com/cssref/css3_pr_box-shadow.php".

**Viewport dimensions used and why**
For my webpage I used 3 seperate CSS files for different viewports to make my website responsive to different screen dimensions. 

**Desktops/Laptops - full.css**
**Dimensions:** Here I used the following media query: *media="only screen and (min-width: 960px)"* These dimensions were used for displaying the webpage content on modern desktop and laptop environments. The reason I decided on the minimum width being 960 px was because tablets and smartphones are typically much smaller in size, and this allowed a safe minimum screen requirements before it displayed a mobile/tablet-ready version on the website as basically every single modern and even outdated computer has a resolution exceeding 960px in width.

**Tablets - tablet.css**
Here I decided to use a better-suited media query: *media="only screen and (min-width: 481px) and (max-width: 959px)"* These dimension restrictions allow your browser to automatically respond to your device's width. The reason I used the restrictions of 481px minimum and 959px maximum is because modern tablets such as iPad, Android tablets and even drawing tablets or compact wireless displays can have resolutions that fit comfortably within these width restrictions for the screen size. The media query will automatically adjust the webpage to fit on any display (predominantly tablets) within these restrictions.

**Mobile Devices/SmartPhones - smartphone.css**
With this viewport the intention is to fit modern smartphones. Now smartphones can range in size and screen dimensions. However for the most part, with the exception of foldable phones such as the Galaxy Z Fold or the iPhone Duo, most smartphones fall within the following webpage max screen px restriction: *media="only screen and (max-width: 480px)"*. This is a viewport meant for modern smart phones. and smartphones are typically smaller than 480 px in width for webpage displays.