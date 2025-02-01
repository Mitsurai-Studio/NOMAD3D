# NOMAD3D
Ender-3 Pro Based Cantilever-style Printer Mod

![01_MAIN_ASM_Ender_3_Pro_(1)_v1_2025-Jan-21_10-55-36AM-000_CustomizedView3777797694](https://github.com/user-attachments/assets/1537ff0b-4a0f-4703-aa06-804ca3ee2e67)

# Introduction

What if we could create a 3D printer that rivals Bambu Lab—not just in performance but in accessibility, openness, and innovation? To achieve this, we need to go beyond just developing hardware. We must rethink the entire user experience, ensuring that our printer is not only powerful but also intuitive, reliable, and customizable. 

This means:

- High-speed, high-quality printing – Competing with Bambu Lab means optimizing motion systems, cooling, and extrusion for speed without sacrificing quality.
- Seamless user experience – From automatic calibration to intuitive software, the project needs to be user-friendly and make high-end 3D printing accessible.
- Strong community collaboration – True open-source success comes from engaging the community, leveraging collective knowledge, and ensuring modularity for easy upgrades.
- Sustainability and repairability – Unlike proprietary systems, the design should prioritize easy repairs, affordable parts, and long-term support.
- Affordability – THe goal is to be able to create an alternative version that is similar in price, if not cheaper than the commercial equivalent. 

This isn't just about making another printer—it’s about redefining what open-source can achieve. 



While this could go way beyond the scope of this project, Project NOMAD3D starts with a simple step: 

**Creating a Open-Source Equivalent to Existing Consumer-Grade 3D printers.**
**and in this case, specifically, a cantilever-style 3D printer.**



This project utilize Ender 3 / Ender 3 Pro as a base and turning it into a cantilever-style 3D Printer. NOMAD conversion mod are more compact and maintains the build volume of the original Ender 3. Being based on Ender 3 / Pro, it has a few advantages: 
- Affordable – Ender 3 / Pro are widely available on the second hand market and also pretty affordable around the world.
- Large Build Volume - Easily one of the largest available cantilever-style 3D printer compared to competitors.
- Community Base - Creality Ender has one of the largest and the most active community base. 

## High-Speed, High-Quality Printing 
This project is looking to match the performance of current generation printers in the market. That means while there is a sharp increase in performance from Ender 3 / Pro, it will be an interesting challenge. 
A good goal would be : 

- 60 mm/s initial layer
- 200 mm/s outer wall, sparse infill, and solid infill
- 300 mm/s inner wall
- 200 mm/s top surface
- 5000 mm/s² acceleration

While it eventually will turn into Klipper for such speed, Marlin firmware also would be an interesting challenge to test. Current version of NOMAD runs at maximum of: 

- 40 mm/s initial layer
- 100 mm/s outer wall
- 120 mm/s inner wall
- 80 mm/s top surface
- 3000 mm/s² acceleration

This is on stock Marlin Firmware, and currently at the speed of well-tuned Ender 3 / Pro. Updates will be going soon. 

## Seamless user experience

## Community Collaboration

## Sustainability & Repairability
The project needs to be based on the existing Ender 3 / Ender 3 Pro spare parts, and not permanently changing any of the parts. The user needs to be able to reverse the build into a fully working Ender 3 / Pro. 

## Affordability
It is true that the stock parts of the Ender 3 / Pro are restrictive performance wise. Therefore, upgrades are permitted. However, the requirements for the parts need to be: 
- 3D Printed (if possible)
- Widely available (must attach link / source & available worldwide)
- Budget friendly. 
