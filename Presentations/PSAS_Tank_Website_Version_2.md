---
layout: project
title: PSAS Composite Fuel Tank 
sponsor: Portland State Aerospace Society
sponsor_url: http://www.psas.pdx.edu/
document-date: 15 May 2017
---

## Project Objective

The objective of this project is to develop a design and a manufacturing process for a composite fuel tank intended to hold liquid oxygen propellant for use in the Portland State Aerospace Society's LV4 rocket. 

## Team

![Team Rocket]( {{ "/projects/images/PSAS_Tank_Group_Pic.jpg" | absolute_url }} )

The project team is

* Neil Benkelman
* Russell Berger
* Alex Farias
* Francesca Frattaroli
* Weldon Peterson
* Chris Wilson

## Customer/Market Requirements

PSAS requires a composite fuel tank that ...

- is liquid oxygen (LOX) safe for duration of fill cycle and launch (30 minutes to 1 hour).
- does not fail (leak, fracture, or explode) when pressurized to 6 ATM (x2 operational pressure)
- Won’t fail at expected scaled LV4 flight loadings (meets Factor of Safety = 2) for combined loads of thermal and propellant stresses.
- has a manufacturing process which can be performed in the ME department machine shop, or outsourced for a reasonable fee (<$500 per component, assuming max of 1-3 outsourced components).


## Design Challenges

The team's primary design challenges are isolating the LOX fuel from reactive materials, such as the structural Carbon Fiber layers, and maintaining a seal at room-temperature, as well as at cryogenic operational temperatures. An additional challenge is confirming the structural integrety of the pre-existing carbon-fiber airframe at cryogenic temperatures and operational pressures.

## Outcomes

The team has developed two tank designs that take the current PSAS airframe design and incorporate a LOX-compatable PTFE liner to chemically insulate the tank from LOX. The first design employs aluminum mating rings lined with a PTFE tube and sealed with shrink-fit aluminum end-caps to mechanically seal the LOX off from the atmosphere as well as the rest of the airframe structure at room and cryogenic temperatures. The advantage of this design, if successful, is that the LOX will only be in contact with PTFE and Aluminum, materials tested and used in LOX environments with success.
The second design utilizes a PTFE sheet liner held together with an aluminum bridge - generating a potential adhesive-lox interface to be mediated with LOX sealant. The endcaps of the sheet liner design are sealed to the aluminum mating rings with bolts and a PTFE gasket. The advantage of this design, if successful, is the affordability and ease of production, as it would require only an additional layer be added to the current airframe layup process.


### *ShrinkFit Tank Design*

{:.center}
![ShrinkFit Tank representation]({{ "/projects/images/PSAS_Tank_fulltank_perspective_2017-05-02.png" | absolute_url }})
<figcaption class="center">
Figure 1: ShrinkFit Tank CAD
</figcaption>

The following image shows an exploded view of our shrinkfit tank design.

{:.center}
![layer representation]({{ "/projects/images/PSAS_Tank_exploded_View_2017-05-02.png" | absolute_url }})
<figcaption class="center">
Figure 2: ShrinkFit PTFE Tube Tank Exploded View CAD
</figcaption>

### *Sheet Liner Tank Construction*

{:.center}
![Sheet Liner Tank representation]({{ "/projects/images/PSAS_Tank_Sheetliner_CAD.jpg" | absolute_url }})
<figcaption class="center">
Figure 3: Sheet Liner Tank CAD
</figcaption>

The following images show the current layup process, using the sheet liner tank design layup and a completed tank.

{:.center}
![Sheet Liner Tank Layup]({{ "/projects/images/PSAS_Tank_Layup_Process.png" | absolute_url }})
<figcaption class="center">
Figure 4: Sheet Liner Tank Layup on Prototype PLA Rings
</figcaption>

{:.center}
![Shrinkfit Completed Tank]({{ "/projects/images/PSAS_Tank_CompletedTank" | absolute_url }})
<figcaption class="center">
Figure 5: Sheet Liner Completed Tank
</figcaption>

Material cryotesting has been performed to ascertain the material properties of the PTFE, in order to create a more accurate FEA model of the tank and allow for optimization of design geometry. Complete prototypes of the two tank designs are currently being built and are being compression and hydro-burst tested at cryotemperatures to determine strength and modes of failure. Tests assessing the reactivity and transport of LOX at the various tank interfaces and pressures is to begin shortly. The tank shown to most successfully withstand structural stresses without leaks or fracture and LOX exposure without chemical reaction will be selected as the tank design recommended to PSAS.
