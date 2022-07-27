# Huntr - Profile Banner Template
While trying to upload a profile banner image on huntr.co I ran into a few issues with the image being resized, and wanted to share a template that worked well for me as of 07/27/2022.

The template image files are located in this repo in the `template_files` directory, with several different options.

The most basic option is to use the [huntr_banner_template_flat.png](template_files/huntr_banner_template_flat.png) image. This can be used as a background reference in any image editing software or websites like Canva and Figma.
![Huntr Banner Template Flattend Image](/template_files/huntr_banner_template_flat.png)

For more advanced options, there is also a layered .psd for use in Adobe Photshop named [huntr_banner_template_layered.psd](/template_files/huntr_banner_template_layered.psd), and a png file with just the visible area overlayed on a transparent background named [huntr_banner_template_overlay_only.png](/template_files/huntr_banner_template_overlay_only.png)

## Notes and Examples
The way I determined the size of the profile banner was by using the Developer Tools panel in Chrome, and finding that Huntr was resizing any image I uploaded to 1280 x 800 pixels and uploading it to an Amazon S3 bucket.

![Upload Example](/examples/dev_tools_example.jpg)

### I recommend leaving some extra space around the "visible area" to be safe.

Here's an example of how I sized my banner with some overlays applied for reference:
![Profile Banner with Overlay](/examples/huntr_banner_template_example.jpg)

And here's how it actually looked on my Huntr profile:
![Profile Banner Preview](/examples/profile_preview_example.jpg)