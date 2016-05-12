# phenol-Hd
Analytical Quasi-diabatic Hamiltonians for the First Two electronic States of Phenol

This contains surfgen input files both shifted and unshifted version of phenol coupled potential energy surfaces for
the OH photodissociation process.  The coupled PESs are constructed from second order MRCI calculations and describes
the region of the PES with energies up to 60,000cm<sup>-1</sup>.  The surfaces are constructed in full 33-dimensional space
and are intended to describe all regions below the specified energy range relevant to the reaction.

Note that points are sampled using photodissociation dynamics with surface-hopping trajectories up to 100ps.
This means that ns timescale processes on the ground state, such as the dissociation of benzene HC bonds,
are not fully described by the potential.

Installation
----

To use the surfaces in your program, you must first install [surfgen evaluation libraries](https://github.com/virtualzx-nad/surfgen),
and call the `EvaluateSurfgen()` subroutine from your program.  Please consult the example code in the surfgen repository.

These input files contain definition of the expansions and should be present in the location where your program is executed.

Please contact [Xiaolei Zhu](virtualzx@gmail.com) should you need any assistance using the potentials.

Copyright Notice
----

Copyright 2011-2015 Yarkony Group, The Johns Hopkins University.
