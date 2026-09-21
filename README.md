# Acoustic Microdroplet Volumetric Display

**Concept by Philipp Dik — September 2026**

## Concept

This project proposes a true volumetric display based on very small water
droplets suspended and spatially organized in air.

Unlike a conventional fog screen, the goal is not to project a two-dimensional
image onto a visible cloud. Instead, individual positions inside a transparent
three-dimensional working volume would act as addressable luminous voxels.

The proposed system combines:

- a continuously replenished microdroplet aerosol;
- acoustic fields for organizing droplets into predictable spatial regions;
- optical excitation of selected droplet positions;
- programmable laser addressing;
- rapid temporal updating to form moving three-dimensional images.

The long-term objective is to reproduce real three-dimensional objects or
people in open space, including real-time volumetric telepresence.


## Acoustic Droplet Matrix

Ultrasonic transducers surrounding the working volume create standing or
dynamically controlled acoustic fields.

The droplets do not necessarily need to remain permanently fixed as individual
particles. Instead, the acoustic field can create repeatable regions in which
droplets are preferentially concentrated.

These regions form a physical three-dimensional coordinate system.

The display controller can therefore know where suitable droplet targets are
likely to exist and address those coordinates optically.

If the aerosol is disturbed — for example by a hand moving through the working
volume — continuous aerosol replenishment and the acoustic field could restore
the droplet distribution.

The project therefore investigates a statistically stable and self-replenishing
3D droplet structure rather than requiring every individual droplet to remain
permanently trapped.


## Transparent Working Volume

The droplet concentration should be low enough that the inactive working volume
remains as transparent as possible.

This creates an important engineering trade-off between:

- droplet diameter;
- droplet concentration;
- optical scattering;
- evaporation rate;
- acoustic localization;
- probability of finding a droplet at an addressable position;
- brightness of an activated voxel.

The optimal droplet size and concentration remain experimental questions.

The intended result is:

nearly transparent medium  
→ weakly visible or invisible optical paths  
→ bright selected points in space  
→ rapidly changing 3D image


## Microdroplets as Optical Elements

A nearly spherical water microdroplet can interact with light as more than a
passive scattering particle.

Depending on its size and optical conditions, a droplet may behave as a
microscopic lens or optical resonator.

Previous experiments have demonstrated optical focusing effects,
whispering-gallery resonances, nonlinear optical effects, and localized
laser-induced plasma in water microdroplets.

This project investigates whether these properties can help concentrate optical
energy inside or near a droplet and thereby reduce the external energy required
to create a visible voxel.


## Single-Beam Voxel Excitation

The simplest experimental architecture uses one focused ultrashort laser beam.

A selected acoustic droplet position is targeted and the optical energy is
focused into the droplet.

One candidate voxel-generation mechanism is laser-induced optical breakdown or
microplasma.

This architecture is useful as an initial experimental proof of concept because
it separates the acoustic positioning problem from more complicated optical
beam-combination systems.

However, sequentially moving one beam between every voxel may ultimately limit
the achievable number of voxels and frame rate.


## Multi-Beam Excitation

A second architecture distributes the optical excitation between multiple
beams positioned around the working volume.

The beams are synchronized spatially and temporally so that they converge at a
selected droplet.

The desired operating principle is:

individual optical channel  
→ insufficient to generate the intended voxel effect

multiple synchronized channels at one droplet  
→ sufficient combined or nonlinear excitation  
→ visible voxel

This could potentially improve spatial selectivity and reduce the energy carried
by any individual optical path.

However, splitting optical energy does not by itself guarantee either a lower
total energy requirement or eye safety.

The exact interaction may depend on whether the channels use:

- the same wavelength;
- different wavelengths;
- coherent or incoherent beams;
- nonlinear optical excitation;
- resonant enhancement inside the droplet.

These mechanisms must be investigated experimentally rather than assumed to be
equivalent.


## Parallel Laser Projection and Voxel Addressing

Sequentially steering a single laser through every voxel is not the only
possible display architecture.

A programmable laser projection system could instead generate multiple optical
focal points simultaneously.

The acoustic system already provides a known three-dimensional set of possible
droplet coordinates. The optical system could therefore receive the active
voxel coordinates of a 3D frame and generate a corresponding pattern of focal
points.

Possible approaches include:

- spatial light modulators;
- holographic beam shaping;
- programmable diffractive optics;
- other optical systems capable of generating multiple controlled focal points.

The proposed processing chain is:

3D model  
→ active voxel coordinates  
→ acoustic droplet coordinates  
→ programmable optical pattern  
→ simultaneous excitation of selected droplets  
→ next optical pattern / frame

Instead of producing thousands of voxels one after another, the system could
potentially address groups of voxels, spatial layers, or multiple separated
points during the same optical cycle.


## Hybrid Parallel / Sequential Addressing

A practical architecture may combine parallel projection with rapid scanning.

For example:

laser source  
→ programmable optical projection  
→ group of selected voxels  
→ rapid pattern update  
→ next group of voxels

This reduces the number of individual beam movements without requiring the
entire three-dimensional image to be generated in a single optical pulse.

The number of simultaneous voxels would depend on the available optical energy,
projection efficiency, required voxel brightness, and repetition rate.


## Energy Limitation

Parallel projection does not create additional optical energy.

If one voxel requires an optical energy E_v and N voxels are excited
simultaneously, the source must provide sufficient total energy for all active
voxel sites, including optical losses.

The architecture therefore involves a trade-off between:

- simultaneous voxel count;
- energy per voxel;
- total pulse energy;
- optical efficiency;
- voxel brightness;
- update rate;
- frame rate.

The optimal balance between parallel and sequential addressing remains an
experimental question.


## 3D Addressing

A conventional scanning system must control X, Y, and focal depth Z.

The acoustic architecture potentially simplifies this problem because the
possible droplet positions form a known set of discrete three-dimensional
coordinates.

Rather than continuously searching for arbitrary points in space, the optical
system can be calibrated against this coordinate map.

The display controller can therefore treat the acoustic volume as a physical
3D voxel grid.

Possible addressing methods include:

- X/Y optical scanning with variable focal depth;
- fast optical deflection;
- programmable holographic addressing;
- simultaneous multi-focus projection;
- combinations of these methods.


## Voxel Generation Mechanisms

Several possible mechanisms should be investigated independently:

1. Laser-induced optical breakdown or microplasma in a water droplet.
2. Nonlinear optical excitation involving multiple synchronized beams.
3. Resonant optical-field enhancement inside a spherical droplet.
4. Raman or other nonlinear optical emission.
5. Optical effects involving electrically charged droplets.

These mechanisms are not assumed to be equivalent or simultaneously necessary.

The first experimental objective is to determine which mechanism provides the
best combination of brightness, repeatability, energy efficiency, and droplet
survival.


## Droplet Replacement and Self-Recovery

Some high-intensity optical processes may deform, evaporate, or destroy an
activated droplet.

The system therefore does not necessarily depend on repeatedly using the same
physical particle.

A continuous aerosol source can replenish the working volume while the acoustic
field reconstructs the statistical droplet distribution.

The display medium could therefore operate as a continuously renewed optical
material rather than as a permanently fixed particle array.


## Color

Color generation remains an open research problem.

Possible approaches include:

- separate optical wavelengths;
- wavelength-selective excitation;
- nonlinear optical conversion;
- controlled scattering;
- other light-emitting mechanisms.

A plasma voxel is not assumed to reproduce the colors of the excitation beams
directly.

RGB or full-color operation must therefore be demonstrated independently.


## Proposed System Architecture

A possible complete system consists of:

1. Microdroplet aerosol generator.
2. Controlled airflow and replenishment system.
3. Ultrasonic transducer arrays surrounding the working volume.
4. Acoustic-field control electronics.
5. One or more ultrashort-pulse laser sources.
6. Programmable optical steering or projection system.
7. Calibration system connecting acoustic coordinates to optical coordinates.
8. Real-time 3D rendering and voxel-selection controller.

The control pipeline is:

3D scene  
→ visible surface / active voxel selection  
→ acoustic coordinate map  
→ optical addressing pattern  
→ synchronized excitation  
→ emitted voxel light  
→ next pattern


## Volumetric Telepresence

One intended application is real-time volumetric communication.

A depth camera or other 3D capture system could acquire the geometry and
appearance of a person.

The captured data would be converted into active voxel coordinates and sent to
the display.

Instead of viewing the remote person on a flat screen, the observer would see a
physical three-dimensional luminous representation occupying real space.

The same architecture could potentially display:

- human faces and bodies;
- scientific data;
- CAD models;
- medical imagery;
- spatial interfaces;
- animated three-dimensional objects.


## Safety

The multi-beam and parallel-projection architectures are partly motivated by
the possibility of distributing optical energy between multiple paths.

However, this does not demonstrate that any individual beam is eye-safe.

A practical system would require independent evaluation of:

- wavelength;
- pulse duration;
- pulse energy;
- repetition rate;
- direct exposure;
- reflections;
- optical failure modes;
- maximum permissible exposure.

High-intensity laser operation should therefore be treated as a separate safety
engineering problem.


## Experimental Development Path

The concept can be tested progressively.

### Stage 1 — Acoustic positioning

Demonstrate stable acoustic trapping or concentration of water droplets without
high-power optical excitation.

### Stage 2 — Single voxel

Address one known droplet position optically and demonstrate a repeatable visible
effect.

### Stage 3 — Multiple acoustic positions

Create and calibrate several known droplet coordinates.

### Stage 4 — Sequential optical addressing

Switch rapidly between different droplet coordinates.

### Stage 5 — Parallel projection

Generate multiple optical focal points corresponding to multiple acoustic
coordinates.

### Stage 6 — Dynamic voxel patterns

Display simple moving three-dimensional point patterns.

### Stage 7 — Volumetric image

Increase voxel count, update rate, brightness, and working volume sufficiently
to display recognizable 3D objects.

### Stage 8 — Telepresence

Connect real-time 3D capture to the volumetric display.


## Main Experimental Questions

The project must determine:

- What droplet diameter provides the best optical and acoustic behavior?
- How accurately can droplets be localized acoustically?
- What 3D spacing between stable acoustic regions is achievable?
- How transparent can the inactive aerosol volume remain?
- What droplet concentration is required?
- How quickly do droplets evaporate?
- How rapidly can disturbed regions recover?
- What optical energy is required for a visible voxel?
- Can a droplet survive repeated excitation?
- How many voxels can be addressed simultaneously?
- How rapidly can programmable optical patterns be changed?
- Can multiple weak optical channels produce a useful nonlinear voxel effect?
- What is the maximum practical frame rate?
- How can full-color voxels be generated?
- What is the maximum useful display volume?
- Can every optical path satisfy the required safety limits?


## Status

**Research concept / experimental architecture.**

Individual physical effects relevant to the concept have experimental precedent,
including acoustic manipulation of droplets, optical resonances in water
microdroplets, nonlinear optical interactions, and femtosecond
laser-induced breakdown in individual water droplets.

The complete architecture proposed here — an acoustically structured,
self-replenishing, nearly transparent microdroplet volume combined with
programmable sequential and/or parallel optical voxel addressing — has not yet
been experimentally demonstrated by this project.

The immediate objective is therefore not to assume that the complete display
works, but to experimentally test each subsystem and determine whether they can
be combined into a practical volumetric display.
