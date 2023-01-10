When energy hits an earth surface feature, it is either **reflected**, **absorbed**, or **transmitted**.

$$E_I(λ) = E_R(λ)+E_A(λ)+E_T(λ)$$
Where $E_I(λ)$ is incident energy, $E_R(λ)$ is reflected, $E_A(λ)$ is absorbed, $E_T(λ)$ is transmitted.

As reflected energy is most important to remote sensing:
$$E_R(λ) = E_I(λ)-[E_A(λ)+E_T(λ)]$$
Surface features affect different wavelengths differently, causing color differences among other effects. Two objects may seem the same in one wavelength, but another can be used to differentiate them.
## Reflection

Geometrically, objects reflect energy on a scale of **specular** to **diffuse** (also called a *"Lambertian surface"*). **Ideal specular reflectors** are mirror like in reflecting energy, near-perfect have slight diffusion in other directions. **Ideal diffuse reflectors** (*"Lambertian surfaces"*) spread out the energy in all directions equally, near-perfect are generally equal except for being slightly more concentrated at the angle of reflection. Many surface features are neither of the two extremes, but in between and near-perfect.

Diffuse reflection contains color information, and is most helpful in remote sensing.

## Spectral Reflectance

$$p_λ=\frac{E_R(λ)}{E_I(λ)}$$
Where $p_λ$ is a percentage of *spectral reflectance*, which for objects can be graphed on a *spectral reflectance curve*.
Differences between two objects' reflectance curves can be used to differentiate objects easily, though this is not always the case.

### Reflectance Curves

![[Spectral Reflectance Curves.png]]
*Spectral reflectance curves for soil, vegetation, water*

Vegetation manifests "peaks and valleys" in its spectral reflectance. Chlorophyll strongly absorbs 0.45 - 0.67 μm (called the *"chlorophyll absorption bands"*). Plant species vary in their reflectance in the range of 0.7 - 1.3 μm, which can also be affected by various stresses. More layers -> more reflectance.

Soil reflectance is more based on its content (moisture, texture, roughness, etc.). Moisture is generally the most important factor, as sandy/coarse soil is more dry (more reflectance) while finer soils are more moist. Iron oxide in soil greatly reduces reflectance in visible wavelengths.

Water in vegetation/soil strongly absorbs 1.4, 1.9, 2.7 μm (*water absorption bands*)

Regular water has distinct absorbance of [[NIR]] bands, no matter the type of body. Water conditions generally only appear in [[Visible Light]] bands. Water generally has high [[Transmittance]], especially with blue-green. Turbidity and dust particles can lower reflectance; other properties (chlorophyll, salt, etc.) also have some correlation to reflectance that can be measured.

### Signatures/Responses

**Spectral signatures** are another name for the measured spectral reflectance of an object, and are often used to determine various attributes/characteristics. They may also include *spectral emittance curves* (see [[Electromagnetic Waves#^bcf79e|here for more?]]). In contrast to **spectral response patterns**, signatures are more consistent/absolute (very similar otherwise). 

Spectral response patterns may be altered by *temporal* or *spatial* effects. Temporal effects change the object over time, which can include seasonal changes for plants. Spatial effects result in different responses from the same feature at the same time at different places, as a result of factors such as climate or disease.

The process of **change detection** seeks to measure/track the effect of temporal effects over time, such as observing the urbanization of an area.

Spectral response patterns can also be influenced by the atmosphere, which among others can affect the *brightness* (radiance) of solar energy (the main example used here). Energy undergoes [[Attenuation]] (reduces) and the atmosphere also can reflect energy, adding *path radiance* to measured signals. Thus, the incoming radiance/irradiance follows:
$$L_{tot}=\frac{pET}{\pi}+L_p$$
Where $L_{tot}$ is total measured spectral radiance; $p$ is object reflectance; $E$ is irradiance on object, incoming energy; $T$ is transmission of atmosphere; $L_p$ is path radiance from the atmosphere.

Skylight is sunlight that has been diffused by the atmosphere, and the proportions of each can vary on weather conditions. Irradiance also changes  seasonally as the solar elevation angle changes.