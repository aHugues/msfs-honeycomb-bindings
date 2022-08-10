# HoneyComb Alpha/Bravo SPAD.Next bindings for Microsoft Flight Simulator

This repo contains custom SPAD.Next bindings to use a HoneyComb Bravo (with a HoneyComb Alpha yoke when relevant) with Microsoft Flight Simulator.

The provided profiles also handle lights, which means that the [Alpha](https://www.spadnext.com/forum/viewtopic.php?t=14083) version of SPAD.Next is necessary, but the [Honeycomb Bridge](https://flyhoneycomb.com/pages/drivers) should not be used.

## Camera + push to talk

Some buttons are usually left unbound: these buttons can be used inside MSFS to bind camera actions (the thumb button for instance), or as a push-to-talk button for VPilot if VATSIM is used.

On the Alpha yoke those buttons are:

- left white thumb button ;
- right white thumb button ;
- left thumb hat
- left white trigger

## Current profiles

General aviation

| Plane                 | Status                                                                                            | Remarks   |
| ---                   | ---                                                                                               | ---       |
| Cessna 152            | :heavy_check_mark: [Complete](https://github.com/aHugues/msfs-honeycomb-bindings/tree/main/C152)  |           |
| Cessna 172            | :construction: Ongoing                                                                            |           |
| Diamond DA40          | :calendar: Planned                                                                                |           |
| Diamont DA62          | :calendar: Planned                                                                                |           |
| Milviz Cessna C310R   | :calendar: Planned                                                                                |           |

Airliner

| Plane             | Status                    | Remarks   |
| ---               | ---                       | ---       |
| Citation CJ4      | :calendar: Planned        |           |
| FBW A320 Neo      | :calendar: Planned        |           |
| Fenix A320        | :construction: Ongoing    |           |
| Aerosoft CRJ      | :calendar: Planned        |           |
| PMDG Boeing 737   | :x: Not planned           |           |

## Adding a new profile

A new profile can be added by creating a new folder with the SPAD.Next XML file as well as a markdown documentation using [the provided template](https://github.com/aHugues/msfs-honeycomb-bindings/blob/main/templates/profile.md).

## Remarks

In some cases, the anonciator panel is not used even though it could completely be functional. This is a conscious choice, for example for the Cessna C152 which does not have any status light corresponding to these elements.

I might provide an alternative profile that would include those, but this is not the plan for now.
