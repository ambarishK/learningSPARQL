## page for learning usage of SPARQL for querying chemical compounds from WIKIDATA. 

- [WikiProject_Chemistry](https://www.wikidata.org/wiki/Wikidata:WikiProject_Chemistry/Guidelines)


- Properties - 
 - P661 - [ChemSpider ID](https://www.wikidata.org/wiki/Property:P661) - instance of - Wikidata property to identify substances OR Wikidata property related to chemistry.
 
 - P3117 - [DSSTOX substance identifier](https://www.wikidata.org/wiki/Property:P3117) - instances of - Wikidata property to identify substances.
 
 - P683 [ChEBI ID](https://www.wikidata.org/wiki/Property:P683) - instance of - Wikidata property to identify substances.
 
 - P662 [PubChem CID](https://www.wikidata.org/wiki/Property:P662) - instance of - Wikidata property to identify substances 
 or Wikidata property related to chemistry, Wikidata property related to biology.
 
 - P31 [instance of](https://www.wikidata.org/wiki/Property:P31) - instance of - Wikidata property.
 
 - P279 [subclass of](https://www.wikidata.org/wiki/Property:P279) - instance of - transitive property.
 
 - P361 [part of](https://www.wikidata.org/wiki/Property:P361) - instance of - transitive property OR asymmetric Wikidata property.
 
 - P527 [has part](https://www.wikidata.org/wiki/Property:P527) - instance of - transitive property.
 
 - P1889 [different from](https://www.wikidata.org/wiki/Property:P1889) - instance of - Wikidata property to describe the elements of identity OR symmetric property.
 
 - P231 [CAS](https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P231) - instance of - Wikidata property to identify substances.
 
 - P233 [canonical SMILES](https://www.wikidata.org/wiki/Property:P233) - instance of - Wikidata property to identify substances OR Wikidata property with datatype string that is not an external identifier.
 
 - P2017 [isomeric SMILES](https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P2017) - instance of - Wikidata property to identify substances.
 
 - P232 [EC number](https://www.wikidata.org/wiki/Property:P232) - instance of - Wikidata property to identify substances OR Wikidata property for an identifier having a checksum.
 
 - P234 [InChI](https://www.wikidata.org/wiki/Property:P234) - instance of - Wikidata property to identify substances OR Wikidata property related to chemistry.
 
 - P235 [InChIKey](https://www.wikidata.org/wiki/Property:P235) - instance of - Wikidata property to identify substances. 
 
 - P235 [InChIKey](https://www.wikidata.org/wiki/Property:P235) - instance of - Wikidata property to identify substances. 
 
 
- Items - 

  wd:Q56697247

- query

All item which are part of (+,-) nicotine. 
---------------------------------------------------------------------------------------------------------------------------------------
SELECT ?item ?itemLabel ?inchikey WHERE
{

  ?item wdt:P527 wd:Q56697247.
  
}

----------------------------------------------------------------------------------------------------------------------------------------
[Results](https://w.wiki/Eh7) - 

 wd:Q14820664


 wd:Q14897692


 wd:Q22275592


 wd:Q22275593


 wd:Q22275618
 
 - item - wd:Q210479
 
 All item which are instance of 2-pentanol.
---------------------------------------------------------------------------------------------------------------------------------------
 SELECT ?item ?itemLabel WHERE
{

  ?item wdt:P31 wd:Q210479.
  
}
----------------------------------------------------------------------------------------------------------------------------------------
[Results](https://w.wiki/EhB) - 

 wd:Q20680358

 wd:Q24953060
 
 
 
 Item with PubChem CID - 998. 
---------------------------------------------------------------------------------------------------------------------------------------- 

SELECT ?item ?itemLabel 
    WHERE 
    {
      ?item wdt:P662 "998" }
      
      
 ---------------------------------------------------------------------------------------------------------------------------------------   [Results](https://w.wiki/EhJ)
 
  wd:Q424998               phenylacetaldehyde
  
  
  Item with CAS number - 10028-17-8
  --------------------------------------------------------------------------------------------------------------------------------------
  
  
   SELECT ?item ?itemLabel WHERE
{

  ?item wdt:P231 10028-17-8.
  
}

----------------------------------------------------------------------------------------------------------------------------------------

[Results](https://w.wiki/EhS)

 wd:Q54389

 wd:Q54973755
    
    
    
 Item with InChiKey - "MOQADKPFYVWPSE-UHFFFAOYSA-N"
 ---------------------------------------------------------------------------------------------------------------------------------------
 
 SELECT ?item ?itemLabel WHERE
{

  ?item wdt:P235 "MOQADKPFYVWPSE-UHFFFAOYSA-N"
        
}
----------------------------------------------------------------------------------------------------------------------------------------

[Results](https://w.wiki/EhW)

wd:Q7739
