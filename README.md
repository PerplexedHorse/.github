# Perplexed Horse

<table>
<tr>
<td width=160px><img src="assets/images/Logo_800.png" alt="Perplexed horse logo" width="150"></td>
<td>
<p><b>Perplexed Horse</b> is a collection of open-source, mechanically focused 3D-printing accessories and subsystems.</br>
The project prioritises <b>simple, passive, and well-defined mechanical solutions</b> that integrate cleanly with existing printers - without motors, electronics, or firmware changes.</p>
<p>The aim is not to reinvent printer hardware, but to solve specific, practical problems using constrained, transparent designs that are easy to understand, build, and adapt.</p>
</td>
</tr>
</table>

## Project Philosophy

Perplexed Horse projects share a common design philosophy:

- Prefer mechanical simplicity over powered complexity
- Reuse existing motion and energy where possible
- Avoid permanent modification to host systems
- Keep scope narrow and well defined
- Design for integration rather than replacement
- Use readily available hardware and materials

Each repository documents a **single responsibility**—with optional components and extensions clearly separated from core designs.

## Inspiration and Acknowledgements

The Perplexed Horse project was inspired by prior work exploring **passive, filament-driven rewind mechanisms**, most notably the _Filamentalist Passive Filament Driven Rewinder_ developed as a recommended option for **:contentReference[oaicite:0]{index=0}** by the :contentReference[oaicite:1]{index=1}.

The Filamentalist project itself credits earlier work by Muzi Xiaoyang's video, whose video demonstrated the fundamental concept of using filament motion as a mechanical energy source for rewind operations. Through extensive iteration and engineering refinement, the Filamentalist rewinder applies this idea at a large scale for multi-material and AMS-style systems.

Perplexed Horse draws inspiration from this same underlying principle—**reusing filament unload motion to drive passive mechanisms**—but applies it independently at a much smaller scale, with different constraints and objectives. In particular, this influenced the development of a **compact filament-driven motor** designed to operate within a sealed, container-based filament dry-box.

While the implementations differ substantially in size, architecture, and intended use, the Filamentalist project helped demonstrate the viability and usefulness of passive filament-driven rewind concepts in practical systems.

The project name itself is also a light-hearted nod to British comedy, referencing a sketch titled _“A Depressed Horse”_ from the TV series **:contentReference[oaicite:2]{index=2}**. The name was chosen in the same playful spirit as _Enraged Rabbit_—memorable and slightly absurd—while the engineering work remains intentionally serious.

## Project Structure

Each Perplexed Horse repository follows a consistent structure:

- A focused core design with a clearly defined purpose
- Optional components documented separately
- Externalised assembly and printing guides where appropriate
- Explicit design goals and scope boundaries

This approach keeps documentation readable and prevents feature creep across projects.

## Licensing

Perplexed Horse projects are released as open hardware under the **CERN Open Hardware Licence v2 – Strongly Reciprocal (CERN-OHL-S-2.0)** unless otherwise stated.

## Status

Perplexed Horse is an active, evolving project.  
Designs are published when they reach a stable and well-documented state, and iteration is expected.

Contributions in the form of testing, validation, and thoughtful feedback are welcome where aligned with the project philosophy.
