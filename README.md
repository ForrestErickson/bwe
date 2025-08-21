# Best Widget Ever also known as: BWE
Best Widget Ever, a product development template.  
Template for documentation to help beginners when developing a project / product.

## Project plan for BWE
File version control with GitHub
Project management with GitHub project features, issues, milestone, issue templates.

Explanation of These Folders: 
- HR, holds human resources information for the company which makes the BWE. Mix of public and private files.
- assembly, holds the folders and files for assembly of the product.
- firmware, holds firmware for BWE
- legal, holds documents requiring legal skills for management. Corporate documents, patent related information for the company which makes the BWE. Mix of public and private files.
- marketing and sales, holds the marketing plans and history, Sales documents.  Mix of public and private files.
- parts, holds specifications for all parts for PCB and enclosure etc. This folder has subfolders and a simple "Parts Master" spreadsheet.
- The subfolder, "PCB" holds the schematic and PCB design files and the files generated from them.
- testing, holds the product qualification test procedure and testing specifications and the factory test procedures for BWE.

## This project milestones
From start of design to first production.
- Write and maintain both Functional Specifications and Technical Specifications. See reference below.
- Product Functional Specification Released.
- Proof of concept, sketches, drawings, Mockups, bread boards and wishful thinking.
- Schematics and drawings for all parts in folders, electrical and mechanical.
- Verify all components are RoHS.
- Test points for manufacturing / troubleshooting especially for power.
- Update parts master to assign Part Numbers
- Schematic release V0.0.1 for initial review
- Review for manufacturing, testing, loading firmware, EMC, ESD, signal integrity, power distribution, safety, maximum temperature, etc...
- Update Schematic release V0.0.2 etc...
- Setup PCB software or train self for PCB manufacturing design rules.
- Schematic approved for start of PCB layout V0.1.xx Passes schematic design rules check.
- Set PCB outline and lock.
- Set location of all parts which must constrain enclosure and lock.
- Assign and place PCB part number on PCB silk screen.
- Assign and place PCB version number on PCB silk screen.
- Place on the PCB silk screen a location for Serial Number to be applied at start of manufacture.
- Place on the PCB silk screen a logo.
- Place on the PCB silk screen a license or statement of copy write.
- Add "tooling holes" for PCB manufacturer.
- If necessary, add rails for PWA manufacturing.
- Enclosure design review. (Make cardboard Mockup, Cable Mockup. PCB Mockup.) Make sure of clearance around all mounting hardware for screw / nut drivers.
- **Enclosure design freeze for prototype PCB. PCB outline and connector placement freeze.**
- PCB outline import parts and make and connector placement. Make Mockup for fit to enclosure
- Milestone: PCB mechanical fit test, (PCB Mockup with connector fits enclosure with cables etc...)
- Component placement for optimum routing and heat and Electromagnetic compatibility.  Then route.
- Connect through hole component traces to "teardrop" pads for strength. Route so that traces can be inspected (Not under connectors for example).
- PCB passes DRC (Design rules check).
- Review of Gerbers and other files by fabricator of PCB against design rules.
- Inventory and order parts including PCB and stencils.
- Make CAD files (STEP or other) of PCB and Enclosure and test fit in an assembly.  Review and specify any required changes.
- **Build Prototype** Enclosure and printed wiring assembly(s)
- Assemble first unit(s) and engineering and compliance (Safety, EMC, other) test.
- Engineering revise and release for rest of Prototype Run. Update of engineering, sales, legal documentation with photographs measurements of real hardware.
- Firmware code review and release.
- Factory Test in place.
- RoHS incoming material verification proccess in place.
- Changes and repeat all the above for Pilot Run (First sellable units with serial numbers etc.).

## Deliverables for This Project
This product development project is done with the completion of the following deliverables.
- Final Functional Specifications and Technical Specifications.
- Product and marketing plant
- Product sales and marketing literature
- - Product pilot run (ready for production)
 - Quality Test Procedures
 - Manufacturing Test Procedure
 - Bill of Material for finished goods as packaged for sale (The **Catalog** item a distributor will stock and sell)
 - Bills of material sub assemblies
 - Troubleshooting reference materials and procedures, theory of operation.

 ## Reference Documentation
 * A design review article: https://resources.altium.com/p/pcb-design-and-review-checklist
 * Writing Functional Vs Technical Specifications: Original Link: https://doyouevenerp.com/functional-vs-technical-specifications/ (Now at the Way Back Machine: https://web.archive.org/web/20220121192628/https://doyouevenerp.com/functional-vs-technical-specifications/)
