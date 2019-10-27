---
title:
- CSC 460
subtitle:
- Transparent and Touchscreen Displays
author:
- Daniel Frankcom
fontsize:
- 12pt
---

#### Note: this report is a work in progress, and will likely change as milestones are added.

# History

## Introduction

Transparent display technology, like many other technologies, began in a series of research labs under small-scale and controlled projects. Originally such technology was not for commercial or consumer purposes, but as the manufacturing and material properties of the displays have evolved, they have begun to move into those markets.

The technology to produce these displays is not particularly new, "[in] 2011 Samsung became the world's first company to mass produce transparent LCD panels." [1] Advancements in opaque OLED technology, combined with years of research and manufacturing practice has resulted in larger and more reliable transparent displays that can be sold to commercial customers, and perhaps soon to consumers.

## Research

Contributions from various research teams have contributed to the overall knowledge base that has produced these transparent displays. Below are some examples of technological steps forward that have contributed to the current state of this technology.

### Transparent Electronics

A paper from December 2009 [2] discussed a new type of "transparent thin-film-transistors (TFTs)" [2] which are a crucial component in building OLED panels. When attempting to build a fully transparent display, every opaque component reduces the amount of light that can come through the surface, so creating transparent TFTs allows more light to come through these components.

### Single Colour Plastic Coating

In 2014 researchers from MIT created a thin plastic film that could be applied to a piece of glass to provide a highly transparent, single-colour display. In contrast, produced transparent displays at the time were "directly integrated into the glass: organic light-emitting diodes for the display, and transparent electronics to control them. But such systems are complex and expensive, and their transparency is limited." [2] 

## Summary

Transparent display technology uses many of the same concepts discovered and refined for the opaque LCD and OLED markets. Transparency was not discovered and produced by any single entity, instead the technology is a result of years of research and refinements to this existing technology. Existing components used to build LCD and OLED screens could be made smaller, enlarging the transparent space between them, and some of these components could be made transparent themselves. As more light is able to come through the display service, the transparency of the device improves.

## Sources

[1] https://www.jcdecaux.com/blog/transparent-lcd-technology-out-home-first

[2] https://www.researchgate.net/publication/224079766_Transparent_electronics_for_see-through_AMOLED_displays

[3] https://news.mit.edu/2014/seeing-things-a-new-transparent-display-system-could-provide-heads-up-data-0121

# Applications

## Augmented Reality

In recent years, augmented and virtual reality systems have been gaining traction with the gradual improvement of relevant technologies [1]. While virtual reality attempts to take over a user's entire field of view to provide an immersive experience, augmented reality takes a gentler approach by blending the real world with the manufactured. This is a great application for transparent displays, as content can be overlayed in front of the user's vision, while still allowing light from the environment through the display. The figure below shows an example pair of augmented reality glasses, where the man's face can be seen through the glass around the content that is being displayed.

![A man wearing augmented reality glasses with transparent displays](images/augmented-reality.jpeg)

Other approaches prior to the introduction of transparent displays attempted to use a camera to capture the user's environment, modify it, and then deliver it to the user on an opaque display. This method of content delivery was unpopular due to the inherently latency problems, field of display restriction, and power consumption. In contrast, when a transparent display is not needed, it effectively disappears due to its transparency. The user of the device is unaffected, and maintains a full field of view with no latency. The figure below shows a patent obtained by Apple which involves overlaying mapping information for a user in real-time, to aid in city navigation.

![An Apple augmented reality navigation patent](images/apple-patent.jpg)

[1] https://www.idc.com/getdoc.jsp?containerId=prUS44511118

[F1] https://miro.medium.com/max/2592/1*AcbWxGO7OuLMk6OMirkfuA.jpeg

[F2] https://www.patentlyapple.com/.a/6a0120a5580826970c01b8d2e6ed75970c-pi

## Retail Showcases

Another popular application of transparent display technology is product showcases. Retail stores are a particularly early adopter of the technology, as it allows for the display of a product with an overlayed and sometimes interactive media element.

![A showcase box containing an item with images overlayed on a transparent display](images/transparent-showcase.jpg)

This product display method is applicable to "showcase boxes" as depicted in the figure above, as well as entire store windows as depicted by figure below. Due to the composability of these displays, media showcase elements can be constructed taking up any amount of space or any shape.

![A store window with a transparent display](images/transparent-window.jpg)

[F3] http://www.displaysky.com/images/up_images/201751162248.jpg

[F4] http://www.yipled.com/uploads/20160929/1475145340672598.jpg

## Head-up Display

Head-up displays are often considered as a subcategory of augmented reality, however there is an important distinction between the two. Augmented reality systems blend real with virtual elements, whereas head-up displays merely "[present] data without requiring users to look away from their usual viewpoints" [1].

Examples of data presentation where it is important for the user to remain focused on their main task often involve vehicles. The figure below shows a head-up display mounted to car dashboard, which is displaying speed and fuel data for the user. A display like this can be useful as it prevents the need for the user to take their eyes off the road to glance down at the instruments behind the wheel. The display itself is transparent so that the driver's field of view is not reduced, and hazards can be seen behind the display.

![A head-up display for speed and fuel, mounted to a car dashboard](images/car-hud.png)

A more futuristic example is shown in figure below, where a head-up display is mounted to a motorbike helmet, so that the user can see their speed while maintaining their line of sight on the road. The technology shown in this image is more compact and low-powered (assuming it runs from a battery), however the core technology here is the same between these applications.

![A head-up display for speed mounted to a motorbike helmet](images/bike-hud.jpg)

[1] https://en.wikipedia.org/wiki/Head-up_display

[F5] https://sk.ru/cfs-file.ashx/__key/communityserver-blogs-components-weblogfiles/00-00-00-00-03/live-1.png

[F6] https://www.kesato.com/blog/wp-content/uploads/2014/11/BikeHUD-Adventure-Helmet-1.jpg

# Transparent LCD Technology

Transparent LCD technology is one of two major categories of transparent panels that exist on the market today. While these LCD panels use an older technology than more recent OLED panels, they also make up a smaller share of the transparent display market due to some inherent limitations in the way that the technology works. [1]

LCD technology works in a similar manner for both opaque and transparent displays, so in order to discribe the function of a transparent LCD we will first examine how a traditional, opaque panel works.

## Opaque LCDs

These panels are made up of a number of layers, with the first being a strong backlight. LCD panels rely on an always-on white light at the back of the display, which illuminates the pixels which are "turned on". This has an advantage in that each pixel does not need to generate its own light, but has a disadvantage that "off" pixels can still leak some light to the user, meaning that blacks are not as dark as desired.

The backlight emitts light through the next layer, which is a horizontal polarizing filter. Polarizing filters only allow light through if it is vibrating in a specific plane, meaning that the only light coming through the second layer is vibrating in a horizontal plane. The diagram below excludes the backlight layer, but shows the second layer which is always letting through the light represented by the arrow here. [2]

![A diagram of layers in an LCD display](images/lcd-layers.png)

The next layer of the LCD panel is a sandwich of liquid crystals between glass. These crystals have some special properties that can manipulate the vibration of light passing through them under certain conditions. As can be seen from the diagram, the crystals will rotate the light 90 degrees, making it vibrate on a vertical plane insted of horizontal. When a voltage is applied, the crystals will "untwist", and will maintain the original plane of the light.

The final layer is another polarizing filter, but this time one that is vertically aligned. The combination of this filter orientation and the properties of the liquid crystals in the previous layer allow light to be selectively blocked. If an electrical signal is applied to the crystals then the light passing through will remain horizontal, and will be blocked by the vertical polarizing filter. If a charge is then removed from the layer, the light will be twisted and will pass through the final layer of the panel.

This layered pattern is applied numerous times across the LCD display in little packages, with a number of coloured filters being applied to subsets of the stacks to produce coloured pixels. Voltage can be applied selectively to groups of 3 pixels to produce combined colours, and the amount of applied voltage can be reduced to let through a smaller amount of the backlight.

## Applying Transparency

The visibility of pixels as described in the previous section relied on the power of the backlight that is embedded in the display. In transparent LCDs, there is no backlight, and instead the visibility is depndent on the ambient light behind the display. The display layers other than the backlight in an opaque LCD are inherently transparent already, as they are designed to let the light from the backlight through to the user. If we take away that layer then we have a transparent display right away, but such a display still requires a bright light behind it in order to be seen.

Depending on the application in which such a panel is used, this requirement may already be fullfilled. For example, a product showcase box is likely to have a bright light already to light up the product on display, in which case the transparent LCD would work well. Unfortunately, a light like this does not exist in all places that a transparent display might be required, and instead a weaker light or a non-direct light source needs to be used to display the image.

Due to the inherent nature of the polarizing filters, they block a significant portion of the light passing through them. This must be accounted for when setting up a transparent LCD, as the amount of ambient light will be significantly reduced when passed through the display stack. Due to this limitation, a large focus of transparent LCD technology improvement is on increasing the transmission efficiency of these filters. If the filters were able to better allow light through, or even transform the light to be in a uniform plane, then the user would be able to see a brighter image.

[1] https://en.wikipedia.org/wiki/See-through_display

[2] https://www.explainthatstuff.com/lcdtv.html
    
[F1] https://www.researchgate.net/figure/Principle-of-operation-of-a-TN-display-in-the-normally-white-mode-Figure-adapted-from_fig2_234151598
