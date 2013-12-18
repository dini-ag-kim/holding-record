# Holding Record

This is a proposal for another micro ontology. Since the [Holding Ontology] describes the item itself, this ontology may describe all the information we have in our holding records but isn't described by the [Holding Ontology].

## Ideas

* This ontology may define a main class "HoldingRecord" or "HoldingStatement" like in the [Library Holdings RDF Vocabulary]. Both should be should be subclasses to ```foaf:Document```, ```bibo:Document``` or ```dcterms:BibliographicResource```.

* The main class may be linked to the item with a property like ```foaf:topic```.

* It should define properties like date of creation, date of revision, agents envolved in the creation of this document, numbers for acquistion and purchase, retention policy, access resctrictions, statement on bugets, license, completeness etc.

* The [PROV Ontology] might be used to express the whole creation and revision part.

 * One question might be, if the availability for an item and its related services should be expressed here and not in the [Holding Ontology].

* Furthermore the [Holding Ontology] might be renamed since this ontology is more likely an ontology describing the holding?

## Discussion

The discussion should take place at the DINI KIM Working Group Holdings mailinglist http://lists.dnb.de/mailman/listinfo/dini-ag-kim-bestandsdaten

[Holding Ontology]: http://dini-ag-kim.github.io/holding-ontology/holding.html
[PROV Ontology]:  http://www.w3.org/TR/prov-o/
[Library Holdings RDF Vocabulary]: http://homepages.inf.ed.ac.uk/v1wwaite/2011/06/holdings.html
