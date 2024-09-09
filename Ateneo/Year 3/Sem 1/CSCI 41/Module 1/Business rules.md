Statements that define some aspect of the business
* assert business structure
* control business behavior
* In terms familiar to end users
* automated through DBMS software

Good business rules:
* Declarative
* Precise
* Atomic; one statement only
* Consistent
* Expressible; structured, natural language
* Distinct; non-redundant
* Business-oriented; understood by non-technical people

Data names:
* related to the business
* non-technical
* may be characteristics
* self-documenting

Data definitions
*Term*: phrase with a specific meaning
*Fact*: association between two or more terms

Conceptual data model:
* graphical model showing characteristics and relationships among entities
* independent of:
	* how data is stored
	* the data model
	* the type of DBMS

Entity-Relationship Diagram (ERD) is the most commonly used conceptual model
*Entity*: noun the organization wishes to maintain data about; represented by a rectangle
*Entity type*: collection of all occurrences of a given type of entity
*Entity instance*: single occurrence of an entity type; can have many instances
Entity **should** be:
* something that will have many instances
* composed of multiple attributes
* used to model something
Entity **should not** be:
* a user of the database system
* output of the database system e.g. report

Attributes describe an entity:
* required vs optional
* simple vs composite (can be broken into component parts e.g. address; enclosed in parenthesis)
* single-valued vs multi-valued (more than one value for each instance; enclosed in curly braces)
* stored vs derived (enclosed in square brackets)
* identifiers (uniquely identifies individual instances of an entity type)

Identifiers:
* unique
* not null
* will not change

Time-stamping leads to an attribute that is multi-valued and composite.

ERD contains only the attribute type not the values.

Relationship: association between instances, labeled by a verb.
Relationship type: line between entity types
Relationship instance: relationship between instances.

Degree: number of entity types that participate in the relationship
* Unary: recursive within a single entity type
* Binary: between two entity types
* Ternary: between three entity types

Cardinality:
* one-to-one
* one-to-many
* many-to-many
* mandatory vs optional