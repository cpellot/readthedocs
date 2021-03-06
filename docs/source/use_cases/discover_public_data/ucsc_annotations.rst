UCSC Annotations
================

.. comment: begin: goto-read-the-docs

.. container:: visible-only-on-github

   +-----------------------------------------------------------------------------------+
   | **The properly rendered version of this document can be found at Read The Docs.** |
   |                                                                                   |
   | **If you are reading this on github, you should instead click** `here`__.         |
   +-----------------------------------------------------------------------------------+

.. _RenderedVersion: http://googlegenomics.readthedocs.org/en/latest/use_cases/discover_public_data/ucsc_annotations.html

__ RenderedVersion_

.. comment: end: goto-read-the-docs

`UCSC Sequence and Annotation Data`_ were loaded into Google Genomics for use in sample annotation pipelines.  This data reflects the state of `UCSC Sequence and Annotation Data`_ at a particular point in time.

Google Cloud Platform data locations
------------------------------------

* Google Cloud Storage folder `gs://genomics-public-data/ucsc/ <https://console.developers.google.com/storage/browser/genomics-public-data/ucsc/>`_
* Google Genomics `annotation sets <https://developers.google.com/apis-explorer/?#p/genomics/v1beta2/genomics.annotationSets.search?_h=11&resource=%257B%250A++%2522datasetIds%2522%253A+%250A++%255B%252210673227266162962312%2522%250A++%255D%250A%257D&>`_

Provenance
----------

Each of the annotation sets listed below was imported into the API from the source files. The source files are also mirrored in Google Cloud Storage.

UCSC GRCh38 (downloaded 12/29/2014 14:00 PST):

* http://hgdownload.cse.ucsc.edu/goldenPath/hg38/database/refFlat.txt.gz
* http://hgdownload.cse.ucsc.edu/goldenPath/hg38/database/refGene.txt.gz
* http://hgdownload.cse.ucsc.edu/goldenPath/hg38/database/knownGene.txt.gz

UCSC hg19 (downloaded 3/5/2015 17:00 PST):

* http://hgdownload.cse.ucsc.edu/goldenPath/hg19/database/refFlat.txt.gz
* http://hgdownload.cse.ucsc.edu/goldenPath/hg19/database/refGene.txt.gz
* http://hgdownload.cse.ucsc.edu/goldenPath/hg19/database/knownGene.txt.gz

