# CCO Extensions
Extension Modules from the Common Core Ontologies, created by Cameron More, unless otherwise stated, and openly free to use by anybody for anything.

## CCO_MFR_Extension (Vehicle Manufacturing Extension)

This module extends CCO to reason over vehicles, models, years, and manufacturer. I defined 'manufacturer' broadly enough to be easily extendable to other types of commodities than just vehicles. My core strategy is to assert that manufacturers like General Motors are instances of some cco:IncorporatedOrganization that is the 'agent in' some Act of Artifact Processing. Artifact Models, such as Accord or Civic, specify the Artifacts that are produced, and those models are the specified input of the Act of Manufacturing. The user manuel can be found on the wiki [here](https://github.com/cameronmore/CCOExtensions/wiki/CCO-Car-Extension).
