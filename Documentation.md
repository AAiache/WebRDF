#Web RDF

##What is Semantic Web?

- In linguistics **sematic** is ... devoted to the study of meaning ... on the syntactic level of words, phrases and sentences.[1]  
- "The Semantic Web is a web of data, in some ways like a global database" [2]  
- "First step is putting data on the Web in a form that machines can naturally understand, or converting it to that form, this creates what I call a Semantic Web : a web of data that can be processed directly or indirectly by machines" (Tim Berners-Lee, Weaving the web. Harper, San Fransisco. 1999)    
[1]: http://en.wikipedia.com/wiki/semantic       "Wikipedia"
[2]: http://w3.org/DesignIssues/semantic.html  "W3C"  

##Why Semantic Web?

Every langage has its syntax and its semantics:  
- Syntax is the grammar: **How** to say something
- Semantic is the study of meaning: the **meaning** behind what you say.  

That is to say, different syntaxes may have the same semantic (e.g: a = a + b and a+= b). In other words, syntax and semantics are all about **communication**.  

The **Web** is a system of interlinked documents accessed via the **Internet**. Web browsers use HTTP to protocol to communicate with Web servers, you can view Web pages and use hyperlinks to navigate between them. By a simple click, people can easily access any of these documents: this is the largest source of information ever.

###The problem:

- Web pages are written in HTML, which is a language that describes the structure of information: it describes the syntax not the semantics.
- If computers could understand the meaning behind information, they would be able to learn what we are interested in, and then help us find better what we are looking for. This is really what Semantic Web is about.
_ Unlike current Web, which is all about documents, the Semantic Web is about things: it can recognize people, places, companies, products, events, movies, etc. That is to say: ti can understand the relationship beween things.

![alt text](https://github.com/AAiache/WebRDF/blob/master/images/current-vs-sw.png?raw=true)  
Source: http://redlink.co/semantic-content-management/

###Solution: Resource Description Framework

**RDFA** standard for describing resources in the Web, it indentifies things using URIs (Uniform Resourse Identifiers). Besides, it uses **Triples** to descibe things: **Subject** Thing - **Predicate** Property - **Object** Velue.

###Example: RDF desciption of a person named Eric Miller  

![alt text](https://github.com/AAiache/WebRDF/blob/master/images/Rdf_graph_for_Eric_Miller.png?raw=true)  
Source: https://en.wikipedia.org/wiki/Resource_Description_Framework  

