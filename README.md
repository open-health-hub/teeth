#Mouth Map

Developed at NHS hack day London 2015 the weekend of 16/17 May 2015. It’s a prototype written in JavaScript to run on any web browser, supporting the broader vision of a three layer abstraction model to support a richer picture for the clinician.

The three layers are:
1. an actual photograph of the patient’s teeth
1. A commonly understood graphical representation, the dental chart
1. The coded data describing the dental chart in a way that will allow analysis for payment, research and quality assurance etc

The work at the weekend focused exclusively on the dental charting layer.

This richer data representation will support the broader ambitions of OpenOdonto to deliver an open source solution of the scope identified in the model below.
We have yet to fully explore the different options for a technical architecture to support these goals and these will be driven by understanding the different use cases for community dental services, based on their current and futures needs and technical capabilities. The client layer will be web based but there are many options for the structure of other architectural layers.

## Proposed Architecture Diagram

![Proposed Architecture Diagram](https://github.com/open-health-hub/teeth/blob/master/teeth_structural_diagram.png "Proposed Architecture Diagram")
