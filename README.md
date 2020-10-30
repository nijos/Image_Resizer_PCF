# Image_Resizer_PCF
A PCF control to easily upload and resize one or more Images on Dynamics365 records. Works with Email and normal Notes attachments.
## Images are resized on the fly before saving to Dynamics 365 and saves your cloud storage

## Installation steps

Download the unmanaged/managed solution from the [Releases](https://github.com/nijos/Image_Resizer_PCF/tree/master/ImageUpload/ResizerSolution/bin/Release)

* Insert a section with a single column on the form.
* Add a field you would like to use that's will not be used on the form.
* Uncheck 'Display label on the form' for the field.
* Add images resizer PCF control to your field
 ![Setting control on form](https://nijoscrmworld.files.wordpress.com/2020/10/image-1.png?w=601)

* Give parameter values
* Image Height: Height of the resized image.
* Image Width: Width of the resized image.
* Image Quality Percentage: Resizing quality.
* Save and publish the form. 
* Navigate to the form and you should see the control

 ![Record Form](https://nijoscrmworld.files.wordpress.com/2020/10/image-2.png?w=601)
 
 ### Development

After cloning the project, run the below commands

`npm install` -- installs the required dependencies

`npm run start` -- local development and testing

If you are new to PCF, the [official documentation](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/implementing-controls-using-typescript).

###Creidts 
* Rama Rao for Attachment Uplaoder PCF [PCF Gallery](https://pcf.gallery/attachment-uploader/)

If this helped you, consider supporting my PCF freebies [![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://paypal.me/nijojosephraju?locale.x=en_GB)





