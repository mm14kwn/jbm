---
layout: post
title:  "What would a cubic planet be like?"
date:   2016-11-16 16:26:00
categories: Physics Gravity Planets
author: K. Newman
---

The original question, the one that launched the journal.

A couple of small problems, however, firstly, I've forgotten most of what we worked out, and secondly, when I looked it up to try remember, I found someone has already written a [paper](http://www98.griffith.edu.au/dspace/bitstream/handle/10072/52169/86009_1.pdf?sequence=1) on it. I'll try and summarise it here, then see if we can work out the situation for other planets.

We can work out a really simple approximation at first by thinking of a point mass, and our position on a cube around that mass. Wheras on a spherical planet, our distance would be constant, here it will vary between corners, edges and the centre of faces. The gravitational accelleration at distance $$r$$ from a point mass $$M$$ is given by $$g=\frac{GM}{r^2}$$, and if we stick on the surface of a cube, $$r=\sqrt{x^2 + y^2 + z^2}$$. This means we have $$g=\frac{GM}{x^2 +y^2 +z^2}$$. Plotting this for a unit cube and unit mass, we have the following map of varying $$g$$:

![g on a unit cube](/jbm/img/g_cubeplanet_pointmass.png){:class="img-responsive"}

If we want to be more accurate, we have to think about the different mass distribution inside a cube planet. Returning to the [paper](http://www98.griffith.edu.au/dspace/bitstream/handle/10072/52169/86009_1.pdf?sequence=1) mentioned earlier (full reference at the bottom), we work out the gravitational potential of a cube of uniform density. If the cube has side length 2L, the potential $$V(X_1,X_2,X_3)$$ at point $$(X_1,X_2,X_3)$$ is the volume integral:
$$
V(X_1,X_2,X_3)=-G\rho\int^L_{-L} \int^L_{-L} \int^L_{-L} \frac{1}{\sqrt{x_1^2+x_2^2+x_3^2}}dx_1 dx_2 dx_3
$$
where $$(x_1,x_2,x_3)$$ is the 3D position of each infinetesemal mass element of the cube relative to our position $$(X_1,X_2,X_3)$$.
Working through this integral, we eventually end up with:
$$
V(X_1,X_2,X_3)=-G\rho\sum_{j=1}^3 [\sum_{i=1}^3 (\frac{x_1 x_2 x_3}{x_i} ln(x_i +1) - \frac{x_i^2}{2} \arctan{\frac{x_1 x_2 x_3}{x_i^2 \sqrt{x_1^2 + x_2^2 + x_3^2}}})]^{L-X_j}_{-L-X_j}
$$

Also pretty complicated, so what does it mean? One of the best ways to think about it is to think what would happen to a lake or ocean on such a planet. A fluid (if we assume its density is much less than that of the planet) will follow a line of constant gravitational potential around the planet. The below image, from the [Chappell et. al. paper](http://www98.griffith.edu.au/dspace/bitstream/handle/10072/52169/86009_1.pdf?sequence=1) what that would look like.

![Lakes on a cubic planet, from Chappell et. al. (2012)](/jbm/img/cube_lake.png){:class="img-responsive"}

So what would it feel like to live on that planet? Leaving aside that such a planet with reasonable size and density would likely form a sphere under its own gravity (see the discussion in [A Human Planet](/jbm/physics/space/gravity/2016/11/16/human-planet.html)), if you were standing on one face, everything would appear totally flat (because it is), however walking towards an edge or corner would feel like climbing a hill. As the atmosphere would still tend to be nearly spherical, these corners, being around $$3000~\mathrm{km}$$ "higher" than the centre of the faces, would appear like vast mountains rising out of the atmosphere into space.

----
Chappell, J.M., Chappell, M.J., Iqbal, A. and Abbott, D., 2012. The Gravity Field of a Cube. *Physics International*, **3**(2), pp. 50-57.