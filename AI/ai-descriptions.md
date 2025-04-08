---
layout: default
title: AI-generated Descriptions
permalink: /ai-descriptions
parent: AI
grand_parent: DBGallery
nav_order: 26
---

# AI-generated Descriptions

This feature uses artificial intelligence to automatically generate detailed descriptions of images and graphics. Users can provide their 
own prompts to the AI, asking it to describe specific aspects of the images.
This provides valuable extra data to find images more easily.  Alternatively it can provide structured data to support business processes: see our <a href="/custom-prompts">Custom Prompts for AI-generated Descriptions</a> blog post for more on that.

## How it works
There are 2 ways to get descriptions added to images' metadata.
1. Simply upload images.  Descriptions will be automatically added to photos and some other file types, such as PhotoShop's.
2. In the main gallery, select one or more images and press the Describe Images button.  There will be an option to modify the default prompt the AI uses to describe the images.

<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=411513&public=2/ai-descriptions-2&1273070938" alt="AI descriptions main menu button"/></p>

That default prompt is set by a system administrator, and would look something like the following:
<p style="margin-left: 5%;">“Analyze this image and provide a detailed, context-aware description. Identify key objects, people, scenes, and any significant activities. If applicable, describe the mood, colors, and overall composition. If the image contains branding, logos, or text, mention those as well. Ensure the description is useful for cataloging and retrieval in a digital asset management system. Keep it concise yet informative.”</p>

## Setting your own custom prompts
Prompts can complex and creative, providing exceptionally valuable output descriptions.

To use a one-time custom prompt, select any number of images and provide a custom prompt just for those images.  This works well when images have special attributes which could benefit from special instructions (I.e. the custom prompt).   
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419606&public=2/custom-prompt-from-main-menu&" alt="Custom prompt menu for AI-generated descriptions"/></p>
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419939&public=2/custom-prompt-popup-with-gallery-background&" alt="Custom prompt popup for AI-generated descriptions"/></p>

The prompt, be it the default or for a custom prompt for selected images, is **incredibly flexible**.  Any prompt that would be passed to ChatGPT or other LLMs would work.  It's highly recommended that you explore which prompts work best to the content in your images.

## Examples
Using the images in the above screenshot and this prompt: "If known, name the architect in these images.  Place this on the first line in this format: 'Architect: name'.  If the location of the building is known, place it on another line in city, country format.  Then mention the architectural style in a final two-sentence paragraph."  

**Result:** This places the following in DBGallery's AI Generated Description field of the first image above, which is then forever searchable:

<p style="margin-left: 5%; color: blue">Architect: Zaha Hadid</p>
<p style="margin-left: 5%;  color: blue">Location: Doha, Qatar</p>

<p style="margin-left: 5%; color: blue" >The architectural style of this building is characterized by its organic forms and fluid shapes, typical of Zaha Hadid's work. It exemplifies Deconstructivism, where the design emphasizes unpredictability and dynamic interaction with the surrounding environment.</p>

This example is likely not relevant to your company's images, but the prompt could be worded to describe any number of scenarious:
1. "This is a photo of a poverty situation. Describe the emotional state of any people as well as the general surroundings."
2. "Provide the history of styles found in this fashion photo. Start each paragraph with the style name followed by a semi-colon."  
3. "Name the colors of all those which take up more than 10% of the photo".
4. “Create an engaging social media caption and hashtags for this image.”
5. “Describe this image in detail, including lighting, composition, and mood.”
6. "Name the architectural styles in this image.  When possible, name the architect and location of the structure."

## Another Architectural Example:
Following is the description provided when this iconic Qatar building was uploaded:

<p><img style="margin-left: 5%; border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=411514&public=2/ai-descriptions-example-1&999069643" alt="AI descriptions example"/></p>


## Building complex custom prompts to describe image

Here's one great example of a complex prompt used to describe company logos, and includes structured output.  Because effective prompts can be difficult to formulate, ChatGPT was asked to provide a suggested prompt for describing logos. This is what it suggested: 

    You are an expert brand designer and marketer. I will provide the name of a company and its logo (or a brief visual reference). Your task is to describe the logo in a structured, detailed way. 

    Please follow these rules in your response:
    1. Identify the company name and logo text (if any).
    2. Provide a concise description of the logo’s overall design (shapes, main elements, colors, layout).
    3. Mention any significant symbols or icons within the logo and what they might represent.
    4. Note the primary color scheme (hex or simple color terms).
    5. Include any relevant brand attributes or style descriptors (e.g., minimalistic, bold, playful, professional).
    6. If the logo includes a tagline, mention it and explain how it relates to the design.

    Format your response as follows, with a blank line between each:
    - **Company Name:** 
    - **Visible Text:** 
    - **Overall Layout/Shape:** 
    - **Color Palette:** 
    - **Main Symbol or Icon (if any):** 
    - **Brand Impression or Style:** 
    - **Tagline (if applicable):** 
    - **Additional Observations:**

    Use clear, professional language, and stay objective while noting possible symbolic meaning or brand associations.


## More custom prompt examples

For more examples, both simple and complex, see our <a href="https://dbgallery.com/custom-prompts">Custom Prompts for AI-generated Descriptions</a> blog post. There you'll find examples for getting the most out of your AI-generated descriptions, including how to get structured data for uses beyond just searching within DBGallery. 

## IMPORTANT TIP: Making this data visible across DBGallery 
While this data field, and all others, can be found in our Full Data View (FDV) tab in image preview, consider using Data Layout Settings 
in our Tools menu to place it in the Info tab and other areas of DBGallery.  See <a href="/datalayoutsettings">Data Layout Settings</a> for more on configuring which data is shown where.

## Turning this feature on
This feature is not turned on by default in all systems.  To turn it on, admins may go to Preferences | Tools, where the option is near the bottoom of the page.
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="https://cdn.dbgallery.cloud/Download.aspx?id=419605&public=2/turning-on-ai-descriptions&" alt="Turning on AI-generated descriptions"/></p>

