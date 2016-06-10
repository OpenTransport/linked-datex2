#   Changes in DATEX II Ontology

### 10 June 2016 - Removed *Logical Inconsistencies*

    1. Some Classes, e.g. the  *PoorEnvironmentalConditions*  Class, showed a SuperClass - SubClass inconsistency. 

    2. In some cases, one property was declared both as ObjectProperty and  as a DataProperty. One typical example was the *charge* property. The problem was solved by removing the DataProperty definition, as in most of the cases
    complex statements were asserted that cannot be defined in OWL with Complex
    DataProperties.