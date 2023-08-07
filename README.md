This is an attempt at creating a library for commonly used components. It is split into the following:

- Common Capacitors: ceramic, tantalum and film capacitors (THT and SMD)
- Common Connectors: pin headers, terminal blocks, various other PCB connectors
- Common Diodes: small signal and fast/schottky diodes, both THT and SMD, power diodes, zeners
- Common Electrolytics: THT electrolytic capacitors sorted by value and voltage (most common values) - see table
- Common Ferrites - a collection of commonly used ferrites and transformers
- Common IC - ICs not found in the standard library
- Common Resistors - resistors by power and type, including SMD
- Common Transistors - MOSFETs, SMD transistors
- Common Misc - stuff that doesn't fit in the other libraries
- PCB Transformers - some mains PCB transformers

# PROJECT
This is a mere association between symbols and footprints using the KiCad Standard Library. When footprints weren't available, I created a separate footprint library.
See https://www.eevblog.com/forum/kicad/putting-together-some-common-parts-libraries/ for discussion.

# INSTALLATION
Simply download the libraries and add them using Symbol Libraries and Footprint Libraries managers.

# CONTRIBUTE
You can suggest changes and improvements and I'll try to address them as much as possible. If you want to add a component, make sure there's a suitable footprint in the standard library (or provide your own). You can suggest components and I'll try to include them, but please provide datasheets or any other useful information.

# DISCLAIMER
These components and their associated footprints are created using either the part itself (when available) or using information that I could find about it. I'm not responsible for mismatches between real world parts and library components, always double check before you send your PCB to be manufactured!
