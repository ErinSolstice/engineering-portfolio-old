---
title: "Cervical Collars"
categories:
    - research
tags:
    - robotics
---

Cervical collars are neck braces used for suspected spinal trauma and for post-surgical stabilization of the spine. Current cervical collars allow too much freedom of movement and have limited options for an individualized fit. I am using granular jamming and 3-D printing to resolve those problems. Granular jamming occurs when granular media, like coffee grounds, are placed under vacuum and become hard and rigid; by contrast, when not under vacuum, the bladder can be molded to the patient’s neck.

![Pouch of granular material.]({{"/assets/c-collar/granular-jamming-pouch.jpg" | relative_url}})

*Nitrile rubber pouch filled with coffee grounds; attached syringe is used to pull a vacuum.*

![Flat 3D printed shell.]({{"/assets/c-collar/shell-flat-one-piece.jpg" | relative_url}})

*3D printed shell laid flat.*

The previous prototype uses channels cut into a flat print at varying angles and spacing to allow the collar to fold up into a complex 3-D shape rather than a simple cone or cylinder. I used a 3-D scan of a person’s head, neck, and shoulders to create the initial 3-D part. Then, using Solidworks tools and a VBA script, I was able to flatten the collar into a printable shape. I placed in the top 10 engineering projects at LSU’s Discover Day of Spring 2021 with that design.

![Collar shell on person in Solidworks.]({{"/assets/c-collar/shell-on-3d-model.png" | relative_url}})

*Collar shell in Solidworks.*

![Printed collar top view.]({{"/assets/c-collar/shell-top-view-old.jpg" | relative_url}})

*Printed collar top view.*.

![Printed collar side view.]({{"/assets/c-collar/shell-left-view-old.jpg" | relative_url}})

*Printed collar side view.*

The next iteration involves cutting out the middle section of the 3-D printed shell to create two rings. These rings will then be connected by adjustable length struts to form a Stewart’s platform. This allows complete control of the rings position relative to each other. The nitrile rubber bladders fill the space between the collar and the neck.

![]({{"/assets/c-collar/generic-stewarts-platform.png" | relative_url}})

*Generic Stewart-Gough platform.*[^1]

![]({{"/assets/c-collar/collar-flat-separated.png" | relative_url}})

*Collar shell prototpye inspired by the Stewart-Gough platform shown in Dolidworks.*

[^1]: He, Jianjun & Gu, Hong & Wang, Zhelong. (2013). Solving the forward kinematics problem of six-DOF Stewart platform using multi-task Gaussian process. Proceedings of the Institution of Mechanical Engineers, Part C: Journal of Mechanical Engineering Science. 227. 161-169. 10.1177/0954406212444508. 