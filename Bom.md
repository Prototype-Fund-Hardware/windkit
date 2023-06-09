The bill of materials (BOM) follows the BOM proposal of [DIN SPEC 3105](https://gitlab.com/OSEGermany/oh-tsdc/-/blob/master/OH-TsDC.md) using **TsDC-ID** (technology specific documentation criteria identifier) and unique position numbers to identify each component.

| TsDC-ID Abbreviation | Explanation                             |
| -------------------- | --------------------------------------- |
| COM                  | Component                               |
| ASM                  | Assembly                                |
| BUY                  | Proprietary components                  |
| STD                  | Standard components                     |
| MAN                  | Self-designed components to manufacture |
| MEC                  | Mechanic                                |

| Pos. | Name                           | Units | TsDC-ID (1) | Reference                                                                                                                                |
| ---- | ------------------------------ | ----- | ----------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | rotor                          | 1     | ASM-MEC     |                                                                                                                                          |
| 1.01 | rotor front mounting plate     | 3     | COM-MAN     | Laser part, aluminium/stainless steel, 2 mm thick, RotorFrontMountingPlate.dxf                                                           |
|      |                                |       |             |                                                                                                                                          |
| 1.02 | rotor blade                    | 3     | COM-MAN     | larch tree, air-dried, blade measurements: 1050 x 80 x 27 mm                                                                             |
|      |                                |       |             |                                                                                                                                          |
| 1.03 | rotor blade fastener bolt      | 9     | COM-STD     | DIN 912 M6 x 50 mm, property class 8.8, metric bolt, cylinder head with hexagon socket                                                   |
| 1.04 | rotor blade fastener slot nut  | 3     | COM-STD     | DIN 508-8-M6-8/10, T-Slot-Nut                                                                                                            |
| 1.05 | rotor blade fastener nut       | 6     | COM-STD     | DIN 985 M6, hexagon lock nut, with polyamide clamping piece                                                                              |
| 1.06 | rotor blade fastener washer    | 6     | COM-STD     | DIN 125 A M6, 6.4 x 12 x 1.6 mm, washer                                                                                                  |
| 1.07 | boiled linseed oil             | 1     | COM-BUY     | 50 ml                                                                                                                                    |
| 2    | alternator rotor               | 1     | ASM-MEC     |                                                                                                                                          |
| 2.01 | upwind magnet disc             | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, UpwindMagnetDiscSlotNut.dxf                                            |
| 2.02 | taper bush                     | 1     | COM-BUY     | Article ID.: 62250325,Taper bush 1210, bore 25 mm                                                                                        |
| 2.03 | taper bush setscrew            | 2     | COM-STD     | part of the scope of delivery of the taper bush, see pos. 2.02                                                                           |
| 2.04 | taper bush hub                 | 1     | COM-BUY     | Article ID.: 14090120, Taper bush hub for Taper Bush size 1210, 120 mm outer diameter                                                    |
| 2.05 | taper bush hub fastener bolt   | 6     | COM-STD     | DIN 912 M6 x 25 mm, property class 8.8, cylinder head with hexagon socket                                                                |
| 2.06 | taper bush hub fastener nut    | 6     | COM-STD     | DIN 985 M6, hexagon lock nut, with polyamide clamping piece                                                                              |
| 2.07 | taper bush hub fastener washer | 12    | COM-STD     | DIN 125 A, for M6, 6.4 x 12 x 1.6 mm, washer                                                                                             |
| 2.08 | magnet stencil                 | 2     | COM-MAN     | Laser part, aluminium/stainless steel, 2 mm thick, MagnetStencil.dxf                                                                     |
| 2.09 | ferrite magnet                 | 24    | COM-BUY     | Ferrit Magnet 50 x 50 x 20 mm                                                                                                            |
| 2.10 | spacer sleeve                  | 9     | COM-BUY     | Stainless steel sleeves 8 x 6 x 1 mm (up to M6), 50 mm length                                                                            |
| 2.11 | discs fastener bolt            | 9     | COM-STD     | DIN 912 M6 x 85 mm, stainless Steel A2, metric bolt, cylinder head with hexagon socket                                                   |
| 2.12 | discs fastener nut             | 9     | COM-STD     | DIN 985 M6, stainless Steel A2, hexagon lock nut, with polyamide clamping piece                                                          |
| 2.13 | discs fastener washer          | 18    | COM-STD     | DIN 125 A, for M6, 6.4 x 12 x 1,6 mm, stainless steel A2, washer                                                                         |
| 2.14 | downwind magnet disc           | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, DownwindMagnetDisc.dxf                                                 |
| 2.15 | two component epoxy adhesive   | 2     | COM-BUY     | Two-component epoxy adhesive, min. 45 min hardening time                                                                                 |
| 2.16 | exterior metal paint           | 1     | COM-BUY     | 200 ml                                                                                                                                   |
| 3    | shaft                          | 1     | COM-BUY     | "Precision shaft steel CF53, hardened,  dressed to size, chromed, 25 (h7) x 1000mm: 64762500, per windkit 125 mm needed                  |
| 4    | alternator stator              |       |             |                                                                                                                                          |
| 4.01 | mounting inlay                 | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, MountingInlayUkf205Mt60.dxf                                            |
| 4.02 | stator cast                    | 1     | COM-BUY     | Epoxy resin and hardener, approx. 1.4 l                                                                                                  |
| 4.03 | copper wire coils              | 9     | COM-BUY     | Approx. 3.6 kg of copper wire, 1.6 mm Diameter, Grade 2, 200°C heat resistant, approx. 400 g per coil, approx. 3.6 kg per windkit needed |
| 4.04 | mounting inlay fastener bolt   | 4     | COM-STD     | DIN 912 M12 x 60 mm, property class 8.8, metric bolt, cylinder head with hexagon socket                                                  |
| 4.05 | Mounting inlay fastener nut    | 4     | COM-STD     | DIN 985 M12, hexagon lock nut, with polyamide clamping piece                                                                             |
| 4.06 | mounting inlay fastener washer | 8     | COM-STD     | DIN 125 A, for M12, 13 x 24 x 2,5 mm, washer                                                                                             |
| 4.07 | stator plug                    | 1     | COM-BUY     | MT60 connector, male part                                                                                                                |
| 4.08 | exterior paint                 | 1     | COM-BUY     | 100 ml                                                                                                                                   |
| 5    | nacelle                        | 1     | ASM-MEC     |                                                                                                                                          |
| 5.01 | housing bearing                | 2     | COM-BUY     | UKF205, ball bearing unit with cast metal housing, locking on shaft via set screw                                                        |
| 5.02 | bearing mounting plate         | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, BearingMountingPlateUkf205.dxf                                         |
| 5.03 | upper spacer                   | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, UpperSpacer.dxf                                                        |
| 5.04 | lower spacer                   | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, LowerSpacer.dxf                                                        |
| 5.05 | yaw pipe                       | 1     | COM-BUY     | Cylindric pipe, steel, no surface treatment, 60.3 x 3.65 x 140 mm                                                                        |
| 5.06 | cable gland                    | 1     | COM-BUY     | M25 x 1.5, cable range 9.0 - 16.0 mm                                                                                                     |
| 5.07 | wind vane socket               | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, WindVaneSocket.dxf                                                     |
| 5.08 | exterior metal paint           | 1     | COM-BUY     |                                                                                                                                          |
| 6    | wind vane                      | 1     | ASM-MEC     |                                                                                                                                          |
| 6.01 | vane                           | 1     | COM-MAN     | plywood, birch waterproof glued BFU100, 650 x 350 x 6 mm                                                                                 |
| 6.02 | vane pipe                      | 1     | COM-BUY     | Cylindric pipe, steel, no surface treatment, 33.7 x 2.5 x 400 mm                                                                         |
| 6.03 | vane mounting                  | 1     | COM-MAN     | Laser part, steel S235 or S355, 6 mm thick, no surface treatment, VaneMounting.dxf                                                       |
| 6.04 | vane fastener bolt             | 7     | COM-STD     | DIN 912 M6 x 25 mm, property class 8.8, metric bolt, cylinder head with hexagon socket                                                   |
| 6.05 | vane fastener nut              | 7     | COM-STD     | DIN 985 M6, hexagon lock nut, with polyamide clamping piece                                                                              |
| 6.06 | vane fastener washer           | 14    | COM-STD     | DIN 125 A, for M6, 6.4 x 12 x 1.6 mm, washer                                                                                             |
| 6.07 | u bolt clamp bolt              | 4     | COM-STD     | DIN 3570, Form A, nominal size DN25, dimension A = 38 mm, M10, steel strap for tubes, for pipe outer diameter 30 -34 mm                  |
| 6.08 | u bolt clamp washer            | 8     | COM-STD     | DIN985 M10, hexagon lock nut, with polyamide clamping piece                                                                              |
| 6.09 | u bolt clamp nut               | 8     | COM-STD     | DIN 125 A, for M10, washer                                                                                                               |
| 6.10 | boiled linseed oil             | 1     | COM-BUY     | 50 ml                                                                                                                                    |
| 6.11 | exterior wood paint            | 1     | COM-BUY     | 200 ml                                                                                                                                   |
