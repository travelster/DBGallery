---
layout: default
title: AI-generated Descriptions
permalink: /ai-descriptions
parent: AI
grand_parent: DBGallery
nav_order: 26
---

# AI-generated Descriptions

This feature uses artificial intelligence to automatically generate detailed, two-paragraph descriptions of images and graphics. Users can provide their own prompts to the AI, asking it to describe specific aspects of the images and request shorter or longer descriptions.
This provides valuable extra data to help find the images.

## How it works
There are 2 ways to get descriptions added to images' metadata.
1. Simply upload images.  Descriptions will be automatically added to photos and some other file types, such as PhotoShop's.
2. In the main gallery, select one or more images and press the Describe Images button.  There will be an option to modify the default prompt the AI uses to describe the images.

<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=411513&public=2/ai-descriptions-2&1273070938" alt="AI descriptions main menu button"/></p>

## Setting the prompt
That default prompt is set by a system administrator, and would look something like the following:
<p style="margin-left: 5%;">“Analyze this image and provide a detailed, context-aware description. Identify key objects, people, scenes, and any significant activities. If applicable, describe the mood, colors, and overall composition. If the image contains branding, logos, or text, mention those as well. Ensure the description is useful for cataloging and retrieval in a digital asset management system. Keep it concise yet informative.”</p>

To use a one-time custom prompt, select any number of images and provide a custom prompt just for those images.  This works well when images have special attributes which could benefit from special instructions (I.e. the custom prompt).   
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419606&public=2/custom-prompt-from-main-menu&" alt="Custom prompt menu for AI-generated descriptions"/></p>
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419939&public=2/custom-prompt-popup-with-gallery-background&" alt="Custom prompt popup for AI-generated descriptions"/></p>

The prompt, be it the default or for a custom prompt for selected images, is **incredibly flexible**.  Any prompt that would be passed to ChatGPT or other LLMs would work.  It's highly recommended that you explore which prompts work best to the content in your images.

**Example:** Using the images in the above screenshot and this prompt: "If known, name the architect in these images.  Place this on the first line in this format: 'Architect: name'.  If the location of the building is known, place it on another line in city, country format.  Then mention the architectural style in a final two-sentence paragraph."  

**Result:** This places the following in DBGallery's AI Generated Description field of the first image above, which is then forever searchable:

<p style="margin-left: 5%; color: blue">Architect: Zaha Hadid</p>
<p style="margin-left: 5%;  color: blue">Location: Doha, Qatar</p>

<p style="margin-left: 5%; color: blue" >The architectural style of this building is characterized by its organic forms and fluid shapes, typical of Zaha Hadid's work. It exemplifies Deconstructivism, where the design emphasizes unpredictability and dynamic interaction with the surrounding environment.</p>

This example is likely not relevant to your company's images, but the prompt could be worded to describe:
1. "This is a photo of a poverty situation. Describe the emotional state of any people as well as the general surroundings."
2. "Provide the history of styles found in this fashion photo. Start each paragraph with the style name followed by a semi-colon."  
3. "Name the colors of all those which take up more than 10% of the photo".
4. “Create an engaging social media caption and hashtags for this image.”
5. “Describe this image in detail, including lighting, composition, and mood.”
6. "Name the architectural styles in this image.  When possible, name the architect and location of the structure."

**Building complex custom prompts to describe image**

See our <a href="/custom-prompts">Custom Prompts for AI-generated Descriptions</a> blog post. There you'll find examples for getting the most out of your AI-generated descriptions, including how to get structured data for uses beyond just searching within DBGallery. 

## A 2nd Example:
Following is the description provided when this iconic Qatar building was uploaded:

<p><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=411514&public=2/ai-descriptions-example-1&999069643" alt="AI descriptions example"/></p>


## IMPORTANT TIP: Making this data visible across DBGallery 
While this data field, and all others, can be found in our Full Data View (FDV) tab in image preview, consider using Data Layout Settings 
in our Tools menu to place it in the Info tab and other areas of DBGallery.  See <a href="/datalayoutsettings">Data Layout Settings</a> for more on configuring which data is shown where.

## Turning this feature on
This feature is not turned on by default in all systems.  To turn it on, admins may go to Preferences | Tools, where the option is near the bottoom of the page.
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419605&public=2/turning-on-ai-descriptions&" alt="Turning on AI-generated descriptions"/></p>

