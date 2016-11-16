---
layout: post
title:  "A Human Planet"
date:   2016-11-16 08:34:20
categories: space,physics,gravity
author: K. Newman
image: https://upload.wikimedia.org/wikipedia/commons/0/01/J%C3%BApiter_e_Io.jpg
---

What if we took all the humans on Earth, and put them in a ball in space? What would the gravity be like? How about the pressure at the centre?

---

Morals and logistics aside, this is a relatively simple problem if we make a few assumptions. First, as humans are mostly water, it's reasonable to assume that their density, $$\rho$$, is similar, i.e. $$\rho=1000~\mathrm{kgm^{-3}}$$. Second, we assume that humans are fundamentally uncompressable, as it makes the maths a lot easier. We could set aside this assumption later, but its reasonable, humans are mostly water, and water can only be compressed a very small amount, and it takes an awful lot of force to do it.

Now we have a density, we could do with finding a mass. In an [article](http://download.springer.com/static/pdf/469/art%253A10.1186%252F1471-2458-12-439.pdf?originUrl=http%3A%2F%2Fbmcpublichealth.biomedcentral.com%2Farticle%2F10.1186%2F1471-2458-12-439&token2=exp=1479285558~acl=%2Fstatic%2Fpdf%2F469%2Fart%25253A10.1186%25252F1471-2458-12-439.pdf*~hmac=91367edeb913edb72f82b0324539541a1d3fad3c5addc59a7c26768e7e278d34) for BMC Public Health in 2012, Walpole et. al. give an average body mass globally as $$62~\mathrm{kg}$$. Multiplying this by $$7\times 10^9$$ (there are varying numbers for Earth population, and it is obviously growing, so this gives a decent lower bound pretty much everyone aggrees on), we arrive at a total mass of $$4.34\times 10^{11}~\mathrm{k}g$$. We can then work out the volume all these people would make if we somehow forced them into a sphere, by using the relationship between mass, volume and density $$\rho=\frac{M}{V}$$. This gives a volume of $$4.34\times 10^8~\mathrm{m^3}$$. If this were a uniform sphere, it would have a radius of $$470~\mathrm{m}$$. This radius puts it a little larger than one of the smallest known moons of Saturn, Aegaeon, which makes up for its slightly smaller size by a larger number of vowels, and by being not entirely composed of human flesh<sup>[citation needed]</sup>.

![Aegaeon Image](http://photojournal.jpl.nasa.gov/browse/PIA11148.jpg "Aegaeon, from the Cassini Mission"){:class="img-responsive"}
The above image, from NASA's Cassini mission, shows the small moon Aegaeon. Note the lack of compressed humans.

We can now work out the pressure at the centre of this sphere, using the Uniform Density Central Pressure Equation (which sounds grander than it is), $$P=(\frac{3\pi}{8})(\frac{GM^2}{R^4})$$, where $$M$$ is the mass, $$R$$ is the radius, and $$G$$ is Newton's gravitational constant. This gives a central pressure of $$303.5~\mathrm{Pascals}$$, or about a third of the atmospheric pressure on Mars!

---

Now, we've assumed a sphere here, but whether astronomical bodies become spherical under their own gravity is a seperate question. To find out the minimum radius $$R_c$$ for a body to become spherical, we need the crushing strength of the material (in this case human flesh!). A quick search puts me on a watchlist, but also reveals a [study](http://www.doitpoms.ac.uk/tlplib/bones/bone_mechanical.php) by the materials science department at Cambridge that gives a compressive strength $$S_c$$ for bone (in the transverse direction, taken here as a lower limit) of around $$ 5\times 10^7 ~\mathrm{Pascals}$$. Using a formula I dredged up from some astrophysics notes years ago, we have $$S_c=\frac{\pi}{2} G \rho^2 R_c^2$$. Plugging in our numbers, we get a minumum radius $$R_c$$ of $$690~\mathrm{km}$$, much more than the $$470~\mathrm{m}$$ of our hideous flesh planet. This is nearer the size of some more well known moons, such as Charon, the moon of the not-a-planet Pluto, or only half the radius of Pluto itself. To make a flesh planet this size, we would need around $$2.2\times 10^{19}$$ humans, or around $$1.7\times 10^{19}$$ Americans (really!). 

---

So there obviously cannot be enough humanity to make a naturally spherical planet, even if all the humans who had ever lived (approximately $$1.07\times 10^{11}$$). However, what if we took all living organisms, from tiny bacteria up to blue whales? There seem to be varying estimates of the total world biomass, but a number of around $$10^{15} \mathrm{kg}$$ crops up in a number of sources. Unfortunately, this is still not enough to form a spherical planet, by about six orders of magnitude!
