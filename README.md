## planning-feature-values

Extracted feature values for a large collection of [planning instances](https://github.com/fawcettc/planning-instances),
using our [feature extractors](https://github.com/fawcettc/planning-features), on the [Compute-Calcul Canada WestGrid Orcinus cluster](https://www.westgrid.ca/support/systems/orcinus).

The extracted features are provided in both CSV and JSON format, documented in the planning-features project.

### Organization

All feature files in this repository are organized roughly as follows:

    <root>/<source - competition, etc.>/<domain>/<csv,json>/<instance_key>.<csv,json>

We also provide merged feature files for each of the domains and sources, along with
a merged file for all instances and all unique instances.

### Analysis

TODO

### Contributors

 * Chris Fawcett

### Papers

 * *Improved Features for Runtime Prediction of Domain-Independent Planners*  
   Chris Fawcett, Mauro Vallati, Frank Hutter, Joerg Hoffmann, Holger H. Hoos, Kevin Leyton-Brown  
   Proceedings of the 24th International Conference on Automated Planning and Scheduling \(ICAPS-14\), 2014.

