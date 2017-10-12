# Sematic web

### Ontology
: linked concepts
AN ontoloy is a specification of a conceptialization
- formal description of concepts and descriptions

Ontological representation of entities and facts
subject -> predicate/property -> object

Let's say

I = URI's (unambigous but no unique identifiers of a resource)
B = Blank nodes
L = Literals

What is the domain of S, P, O? (where do they live?)
S in {I union B}
P in {I}
O in {I union B union L}


### Linked data pronciples: 
1. Use URI
2. Use HTTP URI
3. Provide info for the URI
4. Link data

Virtuoso is a Triple store

Triples (resorce description format) ex: <link> <predicate, type, population > <10000>

One method is semiautomatic is using tools to asses metrics

Another is crowdsorusing, time and cost efficient because of microtasks
non experts about the task
crowd flower, amazon mechanical tank
citiczen science projects
mark2cure

3Q she was doing the quality of the dbpedia 
1. completenes of object value
2. datatypes
3. interlinking

crowd ofr bio metadata quality

similarity:
lexical, value, concept

adaptive human-adaptive analysis platform (adhum)

She wants to create a moethod/system/platform where a lot of people "crowdfounding" with labor the quality of the data in the web

Semantic web articcle (Amrapali)
http://www.semantic-web-journal.net/system/files/swj773.pdf

linked data book
http://linkeddatabook.com/editions/1.0/#htoc1

linked open data
http://lod-cloud.net/

dbpedia
http://wiki.dbpedia.org/
query builder http://dbpedia.org/isparql/

Sparql endpoints
https://www.w3.org/wiki/SparqlEndpoints

Starting sources
http://www.michelepasin.org/blog/2011/02/24/survey-of-pythonic-tools-for-rdf-and-linked-data-programming/
http://meta-guide.com/software-meta-guide/100-best-github-linked-data
https://www.w3schools.com/xml/xml_rdf.asp
http://rdflib.readthedocs.io/en/stable/gettingstarted.html


Semantic Web Case Studies and Use Cases
https://www.w3.org/2001/sw/sweo/public/UseCases/
http://linked.earth/projects/jupyter-notebooks/
https://link.springer.com/content/pdf/10.1007/978-3-642-02121-3_37.pdf
http://www.ivoa.net/documents/Notes/RDFVORegistry/RDFVORegistry-1.0-20070920.html

rdf lib
https://github.com/RDFLib/rdflib
https://github.com/RDFLib/rdflib/tree/master/examples

Slides
https://www.slideshare.net/alchueyr/getting-the-most-out-of-sparql-with-python
https://www.slideshare.net/m_ackermann/d-bpedia-tutorialdublin2015?next_slideshow=1
https://www.slideshare.net/alchueyr/getting-the-most-out-of-sparql-with-python
https://www.slideshare.net/LeeFeigenbaum/sparql-cheat-sheet?next_slideshow=2
https://www.slideshare.net/olafhartig/an-introduction-to-sparql?next_slideshow=3
https://www.slideshare.net/ldodds/sparql-tutorial?next_slideshow=4
https://www.slideshare.net/olafhartig/querying-linked-data-with-sparql?next_slideshow=5
https://www.slideshare.net/olafhartig/tutorial-an-introduction-to-sparql-and-queries-over-linked-data-chapter-3-icwe-2012-ed?next_slideshow=6
https://www.slideshare.net/micheldumontier/link-analysis-of-life-sciences-linked-data

Visualization of linked data
http://www.glueviz.org/en/stable/
https://github.com/gsi-upm/sematch


Reproducing example
http://semanticweb.org/wiki/Getting_data_from_the_Semantic_Web.html

SELECT * WHERE {?s ?p ?o .
?s <http://www.w3.org/1999/02/22-rdf-syntax-ns#type>  <http://bio2rdf.org/drugbank_vocabulary:Drug> .} LIMIT 100

Theory semantic web
https://www.w3.org/TR/rdf11-concepts/#data-model
http://linkeddatabook.com/editions/1.0/#htoc1



