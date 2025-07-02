# Crystallon
Crystallon is an open source project for creating lattice structures using Rhino and Grasshopper3D. The goal is to generate lattice structures within Rhino’s design environment without exporting to 3rd party software, with the advantage of modularity and the ability to combine other powerful tools available for Grasshopper3D. Each tool is left as a cluster which can be opened and modified at will, in the spirit of open source. We hope the community will continue to develop and contribute through the use of the Grasshopper forums and Github.

Download: http://www.food4rhino.com/app/crystallon

Forum: https://discourse.mcneel.com/c/plug-ins/crystallon/

Source: https://github.com/fequalsf/Crystallon



What is a lattice structure?

A lattice structure is a 2D or 3D array of interconnected lines or surfaces. The geometric arrangement of features, and their symmetry, defines the physical properties of the lattice. The terminology comes from crystallography, the study of crystal structures.

The purpose of a lattice structure in additive manufacturing is to manipulate a material's mechanical properties (mass, stiffness, deflection, surface area, porosity, etc.) by manipulating its micro-structure.

Lattice structures are used for many different applications including (but not limited to):

    • Structural light-weighting (reducing weight while maintaining stiffness)
    • Energy absorption (using the material's flexibility similar to engineered foams)
    • Heat transfer (using the structure's increased surface area as a heat-sink)
    • Filtration (manipulating the structure's porosity)
    • Medical implants (manipulating porosity and surface area for bone adhesion)

Lattice structures in additive manufacturing are a fairly new phenomenon. There was no previous means of manufacturing these structures at such a small scale. Therefore there are not many software tools available yet and many are still under development. 



What is Crystallon?

Crystallon is a set of tools that break down the steps of creating a lattice structure in an understandable and modular way, so that they can be used in different workflows for different applications, and at any point in the process they can be used other plugins to enhance their capabilities. 

Each tool is left as an editable cluster made of all native Grasshopper components, meaning you can open the cluster to see how it works or modify the cluster to meet your needs.

Crystallon is not an all-in-one tool. For things like simulation or generating water-tight meshes for 3D printing, there are already powerful plugins available which can be leveraged with Crystallon.

Some plugins you might use in conjunction with Crystallon are:

    • Physics simulation:
        ◦ Kangaroo (http://www.food4rhino.com/app/kangaroo-physics)
        ◦ Flexhopper (https://www.food4rhino.com/app/flexhopper)

    • FEA
        ◦  Millipede (http://www.sawapan.eu/)
        ◦ Karamba (https://www.karamba3d.com/)

    • Genetic algorithms
        ◦ Octopus (http://www.food4rhino.com/app/octopus)

    • Volumetric modeling / Meshing / 3D printing
        ◦ Dendro (https://www.food4rhino.com/app/dendro)
        ◦ Monolith (https://www.food4rhino.com/app/monolith)
        ◦ Silkworm (https://www.food4rhino.com/app/silkworm) 
 
 Crystallon also has tools for 2D lattice structures such as "lattice hinges" made of a rigid material as described in my research here https://fequalsf.blogspot.com/p/parametric-kerf_5.html as well as tools for working with flexible materials and textiles as described in my research here https://fequalsf.blogspot.com/p/textile-composites.html.

There are also utilities for import and export to other software such as the LTCX module for working in conjunction with nTopology as well as INP modules for exporting to popular FEA software packages.

The purpose of Crystallon is to make the development of lattice software open source, so that new discoveries can happen at a much faster rate. For more information on the inspiration behind the development of Crystallon, check out this interview with FATHOM https://studiofathom.com/blog/introducing-crystallon/

The hope is that Crystallon will grow in functionality, and be modular enough that it can integrate into any workflow for any application. We will continue to develop Crystallon as we discover new possibilities, but we also invite the community to get involved and develop their own workflows and hopefully share their discoveries with the community.

If you would like to get involved and contribute, please join the forum at http://www.grasshopper3d.com/group/crystallon for general questions and discussion. Also please feel free to add any modifications or new tools to the Crystallon Github page here.
       
