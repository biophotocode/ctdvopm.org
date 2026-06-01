---
title: "Hardware"
permalink: "/hardware/"
---

# Hardware

## Interactive CAD model
<script type="module"
  src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.0.0/model-viewer.min.js">
</script>
<style>
                  .Hotspot {
                    display: block;
                    width: 10px;
                    height: 10px;
                    border-radius: 10px;
                    border: none;
                    background-color: white;
                    box-sizing: border-box;
                    pointer-events: none;
                  }

                  .hotspot[slot="hotspot-hand"] {
                    --min-hotspot-opacity: 0;
                    background-color: red;
                  }

                  .hotspot[slot="hotspot-foot"]:not([data-visible]) {
                    background-color: transparent;
                    border: 3px solid blue;
                  }

                  .HotspotAnnotation {
                    background-color: #aaaaaa;
                    position: absolute;
                    transform: translate(10px, 10px);
                    border-radius: 10px;
                    padding: 10px;
					font-size: 10pt;
                  }

                  model-viewer > .annotation {
                    transform: translate(10px, 10px);
                  }

                  @media only screen and (max-width: 800px) {
                    model-viewer > .annotation {
                      transform: translate(4.5rem, 10px);
                    }
                  }

                  /* This keeps child nodes hidden while the element loads */
                  :not(:defined)>* {
                    display: none;
                  }
                </style>
<model-viewer
  src="/jmanton/ctdvopm/assets/models/ctdvopm_cad_from_step_recoloured.glb"
  alt="CtDvOPM assembly"
  camera-controls
  auto-rotate
  environment-image="https://modelviewer.dev/shared-assets/environments/aircraft_workshop_01_1k.hdr"
  shadow-intensity="0.75"
  exposure="1.20"
  camera-orbit="-23.59deg 74.46deg 1m"
  field-of-view="30deg"
  tone-mapping="neutral"
  style="width: 100%; height: 800px; background-color: #eeeeee;">
  <button class="Hotspot" slot="hotspot-1" data-position="-0.00005372267801320718m 0.000443016980602921m 0.0010802868528548108m" data-normal="0m 0.9999999999999543m -3.0294627932906266e-7m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Sample</div>
    </button><button class="Hotspot" slot="hotspot-2" data-position="-0.07378572112797153m -0.02558372964383801m 0.015190624025712158m" data-normal="-0.041604236643948564m 0.10701531886033085m 0.9933865355552671m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Excitation objective
        </div>
    </button><button class="Hotspot" slot="hotspot-3" data-position="0.0003014952041057485m -0.07296856336998764m 0.02297345097406156m" data-normal="0m 0.0009364992765888758m 0.9999995614844563m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Detection bi-telecentric lens
        </div>
    </button><button class="Hotspot" slot="hotspot-4" data-position="-0.23774299209692187m -0.18845629558547672m 0.05305363502502408m" data-normal="-1.343588610839583e-7m 0m 0.9999999999999911m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Multiline laser box
        </div>
    </button><button class="Hotspot" slot="hotspot-5" data-position="0.0018423257843881158m -0.2203499392426913m -0.09560167226434364m" data-normal="0.137071583619985m 0.0004455937518821916m -0.9905610442623503m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Camera</div>
    </button><button class="Hotspot" slot="hotspot-6" data-position="-0.20645658311160583m 0.026007586443773288m 0.011690064356443389m" data-normal="-0.25433893386963846m 0.6542143811429241m 0.7122606617129973m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Reflective collimator</div>
    </button><button class="Hotspot" slot="hotspot-7" data-position="-0.1965747044402782m -0.10217393545212249m -0.06717868335545052m" data-normal="0m 0m 1m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Refractive index chock</div>
    </button><button class="Hotspot" slot="hotspot-8" data-position="-0.28544414198159007m -0.02685871277083008m -0.07718246057629585m" data-normal="0m 0m 1m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Light sheet angle adjustment</div>
    </button><button class="Hotspot" slot="hotspot-9" data-position="0.16278796108708993m -0.009026600979268551m -0.03820093454942375m" data-normal="0m 1m 0m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Z-stack stage motor</div>
    </button><button class="Hotspot" slot="hotspot-10" data-position="0.10814594603465569m -0.10078160321775392m 0.022800597300563615m" data-normal="1.343588610839583e-7m 0m 0.9999999999999911m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Sample positioning tower</div>
    </button>
</model-viewer>


## Parts list

As much as possible we have tried to use a single supplier (Thorlabs) to simplify purchasing. Links to individual products are included in the table below and all Thorlabs parts, in appropriate quantities, can be [added to your cart](https://www.thorlabs.com/cart) in one go using code 4UTE3Z8UUS1C.

{: .notice--warning}
**Note: all parts are metric!**

| Supplier        | Part no                                                                                            | Description                                                                                                                   | Price / € | Quantity |      Subtotal |
| --------------- | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------: | :------: | ------------: |
| Cobolt          | [Skyra](https://hubner-photonics.com/products/lasers/multi-line-lasers-and-laser-combiners/skyra/) | Fibre-coupled multiline (405, 488, 561, 638 nm) laser                                                                         | 17,334.47 |    1     |     17,334.47 |
| Edmund Optics   | [#15-872](https://www.edmundoptics.com/p/069x-cobalttlt-telecentric-lens/44825/)                   | 0.69X CobaltTL Telecentric Lens                                                                                               |  2,820.00 |    1     |      2,820.00 |
| IDS             | [U3-31R2SE-M Rev.1.2](https://en.ids-imaging.com/store/u3-31r2se-rev-1-2.html)                     | Monochrome CMOS camera                                                                                                        |  2,540.35 |    1     |      2,540.35 |
| Thorlabs        | [TL2X-SAP](https://www.thorlabs.com/item/TL2X-SAP)                                                 | 2X Super Apochromatic Microscope Objective, 0.1 NA, 56.3 mm WD                                                                |  1,380.24 |    1     |      1,380.24 |
| Thorlabs        | [ZFS25B](https://www.thorlabs.com/item/ZFS25B)                                                     | 25 mm Travel, Compact Stepper Motor Actuator, Ø3/8" Mounting Barrel                                                           |  1,335.65 |    2     |       2671.30 |
| Thorlabs        | [RC12APC-P01](https://www.thorlabs.com/item/RC12APC-P01)                                           | Protected Silver Reflective Collimator, 450 nm - 20 µm, RFL = 50.8 mm, FC/APC                                                 |  1,093.01 |    1     |      1,093.01 |
| Thorlabs        | [LX20/M](https://www.thorlabs.com/item/LX20_M)                                                     | Self-Contained XY 25 mm Translation Stage, M6 x 1.0 Taps                                                                      |    962.29 |    1     |        962.29 |
| Thorlabs        | [MVS1/M](https://www.thorlabs.com/item/MVS1_M)                                                     | 25.0 mm Travel Vertical Translation Stage, M4 and M6 Taps                                                                     |    955.63 |    1     |        955.63 |
| Xometry         | (Quote)                                                                                            | CNC machined parts                                                                                                            |    900.72 |    1     |        900.72 |
| Thorlabs        | [B3060A](https://www.thorlabs.com/item/B3060A)                                                     | Nexus Breadboard, 300 mm x 600 mm x 60 mm, M6 x 1.0 Mounting Holes                                                            |    794.83 |    1     |        794.83 |
| Thorlabs        | [KDC101](https://www.thorlabs.com/item/KDC101)                                                     | K-Cube Brushed DC Servo Motor Controller                                                                                      |    751.52 |    2     |      1,503.04 |
| Thorlabs        | [XR25P/M](https://www.thorlabs.com/item/XR25P_M)                                                   | 25 mm Travel Linear Translation Stage, Side-Mounted Micrometer, M6 x 1.0 Taps                                                 |    488.91 |    1     |        488.91 |
| Eureca          | [Coverglass removal](https://www.eureca.de/21-1-Removing-Covers.html)                              | Cover glass removal                                                                                                           |    480.00 |    1     |        480.00 |
| Thorlabs        | [XRN25C/M](https://www.thorlabs.com/item/XRN25C_M)                                                 | Compact 25 mm Travel Linear Translation Stage, End Micrometer, M6 x 1.0 Taps                                                  |    456.49 |    1     |        456.49 |
| Thorlabs        | [ACY254-100-A](https://www.thorlabs.com/item/ACY254-100-A)                                         | f = 100.0 mm, Ø1" Cylindrical Achromat, AR Coating: 350 - 700 nm                                                              |    434.44 |    1     |        434.44 |
| Xometry         | (Quote)                                                                                            | 3D printed parts                                                                                                              |    345.27 |    1     |        345.27 |
| Thorlabs        | [CRM1PT/M](https://www.thorlabs.com/item/CRM1PT_M)                                                 | Precision Cage Rotation Mount with Micrometer Drive, Ø1" Optics, M4 Tap                                                       |    233.39 |    1     |        233.39 |
| Thorlabs        | [AP90RL/M](https://www.thorlabs.com/item/AP90RL_M)                                                 | Large Right-Angle Bracket, M6 Holes                                                                                           |    189.50 |    1     |        189.50 |
| Thorlabs        | [KCB2C/M](https://www.thorlabs.com/item/KCB2C_M)                                                   | Right-Angle Kinematic Mirror Mount with Smooth Cage Rod Bores, 60 mm Cage System and SM2 Compatible, M4 and M6 Mounting Holes |    185.78 |    1     |        185.78 |
| Thorlabs        | [CFS1/M](https://www.thorlabs.com/item/CFS1_M)                                                     | Sliding Filter Mount with Two CFS1-F1 Inserts, M4 Tap                                                                         |    176.77 |    1     |        176.77 |
| Thorlabs        | [BB2-E02](https://www.thorlabs.com/item/BB2-E02)                                                   | Ø2" Broadband Dielectric Mirror, 400 - 750 nm                                                                                 |    159.87 |    1     |        159.87 |
| Thorlabs        | [KCB1C/M](https://www.thorlabs.com/item/KCB1C_M)                                                   | Right-Angle Kinematic Mirror Mount with Smooth Cage Rod Bores, 30 mm Cage System and SM1 Compatible, M4 and M6 Mounting Holes |    150.42 |    2     |        300.84 |
| Thorlabs        | [CBB1/M](https://www.thorlabs.com/item/CBB1_M)                                                     | 30 mm Cage System U-Bench, M6 x 1.0 and M4 x 0.7 Tapped Holes, SM1-Threaded Mount                                             |     87.24 |    1     |         87.24 |
| Thorlabs        | [BB1-E02](https://www.thorlabs.com/item/BB1-E02)                                                   | Ø1" Broadband Dielectric Mirror, 400 - 750 nm                                                                                 |     79.00 |    2     |        158.00 |
| Thorlabs        | [LCP34T/M](https://www.thorlabs.com/item/LCP34T_M)                                                 | 60 mm Cage Plate, SM2 Threads, 0.9" Thick, M4 Tap (Two SM2RR Retaining Rings Included)                                        |     43.32 |    1     |         43.32 |
| Thorlabs        | [LCP31/M](https://www.thorlabs.com/item/LCP31_M)                                                   | 60 mm Blank Cage Plate, M4 x 0.7 Tap                                                                                          |     41.30 |    2     |         82.60 |
| Thorlabs        | [RS100/M](https://www.thorlabs.com/item/RS100_M)                                                   | Ø25.0 mm Pillar Post, M6 Taps, L = 100 mm                                                                                     |     32.46 |    4     |        129.84 |
| Thorlabs        | [AB90H](https://www.thorlabs.com/item/AB90H)                                                       | Slim Right-Angle Bracket with Counterbored Slots                                                                              |     29.74 |    1     |         29.74 |
| Thorlabs        | [RS75/M](https://www.thorlabs.com/item/RS75_M)                                                     | Ø25.0 mm Pillar Post, M6 Taps, L = 75 mm                                                                                      |     29.12 |    5     |        145.60 |
| Thorlabs        | [SM1L30](https://www.thorlabs.com/item/SM1L30)                                                     | SM1 Lens Tube, 3.00" Thread Depth, One Retaining Ring Included                                                                |     28.43 |    1     |         28.43 |
| Thorlabs        | [AV4/M](https://www.thorlabs.com/item/AV4_M)                                                       | Ø27.0 mm Sorbothane Feet, Internal M6 Mounting Thread, 4 Pieces                                                               |     26.00 |    1     |         26.00 |
| Thorlabs        | [CP36](https://www.thorlabs.com/item/CP36)                                                         | 30 mm Cage Plate, Ø1.2" Double Bore for SM1 and C-Mount Lens Tubes                                                            |     23.57 |    1     |         23.57 |
| Thorlabs        | [SM1A12](https://www.thorlabs.com/item/SM1A12)                                                     | Adapter with External SM1 Threads and Internal M25 x 0.75 Threads                                                             |     23.34 |    1     |         23.34 |
| Thorlabs        | [LCPB1/M](https://www.thorlabs.com/item/LCPB1_M)                                                   | Cage Plate Mounting Base for 60 mm Cage Plates, Metric                                                                        |     22.89 |    2     |         45.78 |
| Thorlabs        | [RS12/M](https://www.thorlabs.com/item/RS12_M)                                                     | Ø25.0 mm Pillar Post, M6 Taps, L = 12.5 mm                                                                                    |     21.12 |    4     |         84.48 |
| Thorlabs        | [CP33/M](https://www.thorlabs.com/item/CP33_M)                                                     | SM1-Threaded 30 mm Cage Plate, 0.35" Thick, 2 Retaining Rings, M4 Tap                                                         |     18.57 |    4     |         74.28 |
| Thorlabs        | [SM1L05](https://www.thorlabs.com/item/SM1L05)                                                     | SM1 Lens Tube, 0.50" Thread Depth, One Retaining Ring Included                                                                |     13.24 |    1     |         13.24 |
| Thorlabs        | [ER6](https://www.thorlabs.com/item/ER6)                                                           | Cage Assembly Rod, 6" Long, Ø6 mm                                                                                             |      9.11 |    8     |         72.88 |
| Thorlabs        | [PH20/M](https://www.thorlabs.com/item/PH20_M)                                                     | Ø12.7 mm Post Holder, Spring-Loaded Hex-Locking Thumbscrew, L=20 mm                                                           |      7.94 |    4     |         31.76 |
| Thorlabs        | [ER3](https://www.thorlabs.com/item/ER3)                                                           | Cage Assembly Rod, 3" Long, Ø6 mm                                                                                             |      6.94 |    4     |         27.76 |
| Thorlabs        | [ER2](https://www.thorlabs.com/item/ER2)                                                           | Cage Assembly Rod, 2" Long, Ø6 mm                                                                                             |      6.41 |    4     |         25.64 |
| Thorlabs        | [TR20/M](https://www.thorlabs.com/item/TR20_M)                                                     | Ø12.7 mm Optical Post, SS, M4 Setscrew, M6 Tap, L = 20 mm                                                                     |      5.24 |    4     |         20.96 |
| **Total**       |                                                                                                    |                                                                                                                               |           |          | **37,581.60** |