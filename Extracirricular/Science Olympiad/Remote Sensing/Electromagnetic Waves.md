Electromagnetic waves (EMWs) encompass [[Visible Light]], [[UV]], [[X-Ray]] and all other parts of the [[Electromagnetic Spectrum]].

# Structure
## Wave Perspective

They travel at the [[Speed of Light]] ($c$, 299 792 458 m / s), and can be described by either their wavelength (from peak to peak; $λ$) or frequency (# of peaks per unit of time; $v$), which are *inversely related*. EMWs are comprised of a sinusoidal electric wave (E) and similar magnetic wave (M) at right angles, perpendicular to the direction of propagation. They radiate in accordance with [[Basic Wave Theory]], and obey the general equation:
$$c = vλ$$
*The [[Wave Equation]] (Modified with c for velocity)*

![[Electromagnetic Waves Diagram.png]]

For [[Remote Sensing]], EMWs are commonly classified by their location on the [[Electromagnetic Spectrum]], and commonly denoted by micrometers (also known as *microns*, µm). Division along the spectrum is not well-defined, but generally follows a logarithmic scale (changes in powers of 10). The [[Visible Light]] portion of the spectrum is small (0.4 - 0.7 µm): blue (0.4 - 0.5 µm), green (0.5 - 0.6 µm), red (0.6 - 0.7 µm). Past blue is [[UV]], and before red is [[IR]], split into three categories: near IR ([[NIR]], 0.7 - 1.3 µm), mid IR ([[MIR]], 1.3 - 3 µm), and thermal IR ([[TIR]], 3 - 14 µm; *TIR is the only form of IR related to perceived heat*). Longer wavelengths from 1 mm - 1 m are [[Microwaves]]. [[Remote Sensing]] commonly operates with [[Visible Light]], [[IR]], and [[Microwaves]]. 

## Particle Perspective

EMWs can also be thought of as a particle, giving insight into its interactions with matter. Such a theory supposes that EMWs are composed of discrete units called [[Photons]] or [[Quanta]]. Energy of a quantum is given by the equation:

![[Energy of Quantum]]

As such, the energy of a photon is derived from combining this equation with parts of the wave equation, giving the equation:

![[Energy of a Photon]]

Wavelength and energy are inversely related. EMWs with longer wavelength (such as [[Microwaves]]) are more difficult to sense as they have less energy, so sensing systems for long wavelengths must observe larger areas to get a detectable signal.

# Spectral Emittance

**All objects with a temperature above absolute zero continuously emit EMWs.** The amount of energy an object radiates is a function of its temperature: ^bcf79e

![[Stefan-Boltzmann Law]]

The spectral distribution (concentration of different wavelengths) of this emittance also varies, with that of a [[Blackbody]] at varying temperatures commonly shown with a graph. Note that the [[Sun]] radiates similar to a 6000 K blackbody.

![[Blackbody Curve.png]]

The *dominant wavelength* that is most intensely emitted is related to temperature and modelled by the equation:

![[Wien's Displacement Law]]

Such a phenomenon is clearly demonstrated in heating metal, which glows from red - orange - yellow - white. Given Earth's ambient temperature of 300 K, it emits generally 9.7 µm wavelengths (which is [[TIR]]). The [[Sun]] peaks around 0.5 µm ([[Visible Light]] which can be seen with eyes or film), and is a great way of observing the Earth using reflected light. The line between reflected and emitted [[IR]] is ~3 µm (reflected below, emitted above).