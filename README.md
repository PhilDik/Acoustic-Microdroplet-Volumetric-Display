# Acoustic Microdroplet Volumetric Display

**Concept by Philipp Dik — September 2026**

## Concept

This project explores a true volumetric display based on very small water droplets suspended or spatially organized in air.

Instead of projecting an image onto a fog screen, the goal is to create individually addressable luminous points inside a transparent three-dimensional volume.

The proposed system combines:

- an aerosol of microscopic water droplets;
- acoustic fields that organize or concentrate droplets into predictable spatial regions;
- optical excitation directed toward selected droplet positions;
- rapid scanning of these positions to construct a moving three-dimensional image.

The long-term goal is a display capable of reproducing a real three-dimensional object or person in open space rather than on a flat or curved projection surface.


## Acoustic Droplet Matrix

Ultrasonic transducers would create a standing or dynamically controlled acoustic field inside the working volume.

The droplets do not necessarily need to remain permanently fixed as individual particles.

Instead, the acoustic field may produce repeatable regions of increased droplet concentration or preferred droplet positions.

These regions form a physical three-dimensional coordinate system that can be calibrated relative to the optical addressing system.

The acoustic wavelength and field geometry determine the possible spacing between these regions.

A hand or other object passing through the display could temporarily disturb the droplet distribution and therefore disturb the image.

After the object is removed, continued aerosol supply and the acoustic field could restore the working droplet distribution.


## Transparent Working Volume

The intention is not to create a visibly dense fog.

The concentration of droplets should be low enough that the unilluminated working volume remains nearly transparent and does not significantly obscure objects behind the display.

This produces an engineering tradeoff between:

- droplet diameter;
- droplet concentration;
- optical scattering;
- evaporation time;
- acoustic localization;
- probability of finding a droplet at an addressable position;
- voxel brightness.

The optimal droplet size has not yet been determined.

Droplets from the micrometer to tens-of-micrometers range should be investigated experimentally rather than assuming that the smallest possible droplet is necessarily optimal.


## Aerosol Generation

The water microdroplets could be generated using ultrasonic atomization, vibrating-mesh atomization, or another controlled aerosol-generation method.

A continuous supply of droplets could replenish the working volume.

The system therefore does not necessarily depend on permanently preserving individual droplets.

Droplets may enter, move through, evaporate, be displaced, or be consumed by optical excitation while the overall spatial distribution is continuously restored.


## Droplets as Optical Elements

A microscopic spherical water droplet is not only a target for the optical system.

Surface tension naturally causes sufficiently small free water droplets to approach a spherical shape.

Because of their geometry and refractive index, spherical microdroplets can behave as microscopic lenses and optical resonators.

Previous experiments have demonstrated optical focusing, resonant optical behavior, whispering-gallery modes, nonlinear optical effects, and highly localized laser-induced plasma inside water microdroplets.

The project therefore investigates whether the droplet itself can help concentrate optical energy inside a very small region and improve the localization of a luminous voxel.


## Optical Voxel Generation

One experimentally established candidate mechanism is laser-induced optical breakdown inside a water microdroplet.

A sufficiently intense, tightly focused ultrashort laser pulse can produce a very small plasma region inside the droplet.

The resulting optical event could potentially serve as a visible volumetric voxel.

For a display, the desired sequence would be:

**known 3D droplet region → optical targeting → short luminous event → next coordinate**

Rapid repetition across many coordinates could create the perception of a persistent three-dimensional image.

A single strongly focused ultrashort laser is the simplest experimentally supported starting point.

However, this project also proposes investigating a multi-beam architecture.


## Multi-Beam Excitation

Instead of delivering all required optical energy through one beam, the proposed architecture investigates distributing the excitation between multiple optical channels positioned around the display volume.

These channels would be synchronized spatially and temporally so that they converge on a selected microdroplet.

The desired operating condition is:

**individual optical channel → below the voxel-generation threshold**

**multiple synchronized channels at one droplet → bright optical voxel**

The purpose is to concentrate the strongest optical interaction at a selected coordinate rather than along an individual optical path.

Several configurations could be investigated:

- multiple beams of the same wavelength;
- multiple beams of different wavelengths;
- temporally synchronized pulses;
- nonlinear multi-photon excitation;
- resonantly enhanced interaction inside the droplet;
- combinations of optical channels that produce an effect only when they overlap spatially and temporally.

Whether a sufficiently efficient nonlinear interaction can be achieved in a water microdroplet under these conditions remains an open experimental question.


## Beam Splitting as a Possible Safety Mechanism

One possible implementation is to begin with a single optical source and split its pulse into several lower-energy optical paths.

The separated beams would travel through different paths around the display volume and would be recombined spatially and temporally only at the selected microdroplet.

The purpose of this architecture is not only voxel addressing.

It could potentially improve safety by reducing the optical energy carried by any individual path.

An unintended object intersecting only one optical path would therefore receive only a fraction of the total optical energy involved in voxel excitation.

A particularly interesting target condition would be:

**each separated beam individually remains below the required interaction threshold, while their combined or nonlinear interaction at the selected droplet produces the luminous voxel.**

Different wavelengths could also be separated into independent channels and recombined at the droplet if a suitable nonlinear optical process can be identified.

The spherical droplet itself may potentially contribute additional field localization through refraction, focusing, or resonant behavior.

This architecture does **not** automatically make the individual beams eye-safe.

A practical implementation would have to demonstrate that every individual optical path remains within applicable exposure limits under normal operation and foreseeable failure conditions.


## Spatial Optical Architecture

The optical modules could be positioned around the perimeter of the display rather than directly behind the image.

Multiple optical paths could approach the working volume from different directions.

The system would then calculate the required beam directions and timing for a selected voxel coordinate.

The intended relationship is:

**3D coordinate → acoustic droplet position → optical steering → pulse synchronization → luminous voxel**

Unused optical energy should not be allowed to continue freely into the surrounding environment.

Any practical implementation would require controlled beam termination, optical containment, monitoring, and automatic interruption when a person or unexpected object enters an unsafe optical path.


## Charged Droplets

Electrical charging of droplets is another possible research direction.

Electrical fields are not necessarily required to generate the droplets or to create the basic acoustic matrix.

However, charged droplets could potentially allow additional control over droplet motion, distribution, aggregation, or interaction with the optical field.

Nonlinear optical effects in charged water microdroplets have previously been experimentally observed.

A future system could therefore investigate a hybrid architecture combining:

**ultrasonic positioning + charged droplets + optical excitation**

This remains an optional research branch rather than a required component of the basic concept.


## Color

Color generation remains an open part of the project.

Possible approaches include:

- separate optical wavelengths;
- RGB optical channels;
- nonlinear wavelength conversion;
- wavelength-dependent excitation;
- nonlinear optical emission from the droplet;
- another light-emitting mechanism associated with the droplet or generated plasma.

Different combinations of optical channels could potentially correspond to different emitted colors.

However, a plasma voxel should not automatically be assumed to reproduce the colors of the incoming laser beams.

The relationship between excitation wavelength and perceived voxel color must be experimentally determined.


## Interaction

Because the display medium consists of physical droplets suspended in open space, the image could potentially be physically disturbed.

For example, a hand passing through the working volume could displace droplets and temporarily destroy part of the displayed image.

After the hand is removed, aerosol replenishment and the acoustic field could reconstruct the droplet distribution and therefore restore the image.

This behavior would distinguish the system from a conventional projection or purely optical holographic display.


## Proposed System Architecture

A possible future device could contain:

- a water reservoir;
- an ultrasonic or vibrating-mesh aerosol generator;
- controlled airflow for replenishing the working volume;
- ultrasonic transducer arrays surrounding the display region;
- sensors for monitoring the acoustic and droplet distribution;
- optical sources positioned around the perimeter;
- beam splitting and steering optics;
- focusing optics;
- timing and synchronization electronics;
- optical monitoring and safety interlocks;
- a real-time 3D rendering and voxel-addressing system.

The display controller would convert a three-dimensional model or live 3D capture into a sequence of voxel coordinates.

Each coordinate would then be synchronized with the acoustic droplet structure and optical excitation system.


## Example Application: Volumetric Telepresence

One possible application is real-time volumetric telepresence.

A person could be captured in three dimensions at one location.

The resulting continuously updated 3D data could be transmitted to another location.

The microdroplet display would reconstruct the person's visible surface as rapidly changing luminous voxels occupying real three-dimensional space.

Unlike a conventional video call, the remote representation would not be confined to a flat screen.

Unlike a conventional fog screen, the intended image would not exist only on a two-dimensional sheet of aerosol.

The goal is a genuinely volumetric representation that can be observed from different directions.


## Research Basis

Individual physical elements related to this concept have already been demonstrated independently.

These include:

- ultrasonic generation of microscopic water droplets;
- acoustic manipulation and concentration of particles and droplets;
- acoustic levitation of water droplets;
- optical focusing by spherical microdroplets;
- whispering-gallery resonances in liquid microdroplets;
- nonlinear optical effects in water microdroplets;
- laser-induced optical breakdown and localized plasma formation inside water microdroplets.

These established effects provide physical starting points for the proposed architecture.

They do **not** demonstrate that the complete display described here will operate as proposed.


## Open Research Questions

The main unresolved questions include:

- optimal water-droplet diameter;
- minimum practical droplet diameter for stable acoustic manipulation;
- achievable acoustic 3D spacing;
- stability of a large acoustic droplet matrix;
- droplet concentration required for reliable voxel generation;
- transparency of the complete working volume;
- optical scattering along beam paths;
- evaporation time;
- aerosol replenishment rate;
- recovery after physical disturbance;
- optical energy required for one visible voxel;
- achievable voxel brightness;
- voxel lifetime;
- maximum voxel repetition rate;
- effectiveness of single-beam excitation;
- effectiveness of multi-beam excitation;
- whether beam splitting can substantially reduce individual beam exposure;
- whether nonlinear interaction can make the combined excitation substantially more efficient than simple intensity addition;
- usefulness of the droplet as a microlens or optical resonator;
- usefulness of electrically charged droplets;
- practical RGB/color generation;
- maximum useful display volume;
- acoustic noise;
- optical safety;
- interaction between neighboring voxels;
- long-term stability and contamination of the aerosol system.


## Safety

The optical mechanisms considered in this project may involve ultrashort laser pulses with very high peak intensity.

Short pulse duration does not by itself make such radiation safe.

The eye can strongly focus visible and near-infrared laser radiation onto the retina.

The proposed multi-beam and beam-splitting architectures are therefore research directions for potentially reducing the energy present in each individual optical path, not proof of eye safety.

Any practical device intended for use near people would require a dedicated safety architecture, including evaluation of individual beam exposure, reflections, failure conditions, beam termination, interlocks, object detection, and applicable laser exposure limits.


## Current Status

**Research concept / experimental architecture — September 2026.**

The project currently combines experimentally established physical effects with several unverified system-level hypotheses.

In particular, the following should be treated as research questions rather than established capabilities:

- formation of a sufficiently transparent and stable large 3D microdroplet matrix;
- reliable high-speed addressing of individual droplet regions;
- multi-beam threshold excitation of water microdroplets;
- useful optical enhancement produced by the droplet itself;
- controllable full-color voxel generation;
- operation at a repetition rate sufficient for a moving volumetric image;
- reduction of individual beam exposure to a level compatible with human-accessible operation.

The purpose of this repository is to document the concept and its development before detailed physical, engineering, prior-art, and experimental validation.

A later technical review should separate each component into:

**experimentally established / physically plausible / unverified / impractical**

and update the architecture accordingly.
