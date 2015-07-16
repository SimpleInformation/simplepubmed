MODULE
------
Simple PubMed

Contents of files:
------------------

  * Installation
  * Configuration



REQUIREMENTS
------------
Drupal 7.0


DESCRIPTION/FEATURES
--------------------

Simple PubMed Module provides a simple field to import and display scientific publication data from the PubMed Database.

How it works

Simple PubMed provides a text field where you can put in a PubMed ID and Simple PubMed provides a content type in installation where you can see the imported node corresponding to PubMed IDS input.
After saving, Simple PubMed will automatically fetch Publication data results from the PubMed database and import it in to a node of the content type Pubmed content. The new nodes created contain the fields Pubmed Title, Pubmed description, Author, Author list, Journal, Pubmed id, Pagination, Pagination combined, Volume, Issue, Abstract and Published date.



Installation:
-------------
1. Copy simplepubmed folder to modules (usually 'sites/all/modules')
   directory.
2. At the 'admin/modules' page, enable the simplepubmed module.


Configuration:
--------------
At the 'admin/config/services/manage-simplepubmed' page can be used for publication from the PubMed Database.


CREDITS
--------

Parts of this module came from davidn <https://www.drupal.org/u/davidn> and his Sandbox project<https://www.drupal.org/sandbox/nellessen/1780320>
Parts of this also came from the Bibliography Module <https://www.drupal.org/project/biblio>
Parts of this plugin are based on the EntrezClient of the no longer maintained project Entrez. A lot of thanks and credits to those guys!
This module was created by Simple Information <http://www.simpleinformation.com>

