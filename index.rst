############################
Rubin Curated SciX Libraries
############################

.. abstract::

   Technical note describing the process for maintaining the Rubin Observatory technical and scientific libraries.

========
Overview
========

Tracking scientific publications is essential for demonstrating the scholarly impact of Rubin Observatory’s data products, analysis tools, and
technical contributions to the astronomical community. The Community Science Team (CST) monitors research that uses Rubin Observatory data or
tools and curates public libraries of relevant publications on the Science Explorer (SciX) digital library portal for researchers in astronomy.
The number of scientific and technical papers published with Rubin data is an essential metric tracked and reported to Rubin and agency management.
These curated libraries are linked from the Rubin Observatory For Scientists website.

This document outlines the process used for maintaining these libraries. It explains the structure and purpose of each library,
the search strategies employed to identify relevant publications, the workflow for reviewing and adding papers, and the criteria for inclusion or exclusion.
It also describes how publication metrics are compiled and reported annually.


====================
Rubin SciX libraries
====================


Rubin maintains two distinct public libraries within SciX: one for scientific publications and one for technical publications. 
Each serves a unique purpose in documenting how Rubin’s resources are used.

The Scientific Publications Library includes refereed research that directly references Rubin Observatory data products, select technical documentation,
and non-refereed papers like arxiv preprints and research notices. As Rubin’s data offerings expand, the search criteria for this library will evolve. 

- Public Library name: `Vera C. Rubin Observatory Scientific Publications <https://scixplorer.org/public-libraries/QQ9rNp-QSZqea5vG6zESUQ>`_
- search query for library: docs(library/QQ9rNp-QSZqea5vG6zESUQ)

The Technical Publications Library focuses on Rubin’s internal and external technical outputs,  such as software documentation, system design papers, and engineering reports.
These materials are essential for understanding the infrastructure that supports Rubin’s scientific mission.

- Public Library name: `Vera C. Rubin Observatory Technical Publications <https://scixplorer.org/public-libraries/oue8xvvpTjqeYPvR5YW6VA>`_
- search query for library: docs(library/oue8xvvpTjqeYPvR5YW6VA)


======================================
Scientific library maintenance process
======================================

To capture as many relevant papers as possible, the CST designs search queries based on SciX bibcodes for Rubin data release technical documentation and data products.
Each bibcode uniquely identifies a Rubin publication or dataset within SciX. Although search results may include a wide range of papers,
only those that meet the defined inclusion criteria are added to the library.
By reviewing bibcode-based search results on a regular basis, the CST ensures that the library remains accurate and up to date with the appropriate scientific literature.
In addition to bibcode‑based queries, the CST also conducts key word and time‑frame searches to ensure that any relevant papers are identified and added to the scientific library.


Perform search
--------------

SciX allows searches in specific fields, including keywords, bibcodes, titles, and Digital Object Identifiers (DOIs).

Appendix A provides pre‑built links focused on Rubin’s data release technical documentation, data products, and time‑constrained keywords, which are sufficient for initial searches.
To perform a search, users can click the links in Appendix A or enter the criteria from the table into the SciX search bar.
SciX will then return a list of all papers citing the specified bibcode. These searches are configured to include both refereed and non‑refereed papers to maximize visibility.
Selecting the refereed option on the left side of the SciX interface will narrow the results.
Personnel maintaining the library may use this feature or design a search that incorporates this limit.

If a new query is needed, Appendix B provides instructions for constructing one.

Review papers for inclusion
---------------------------

Once the search results are displayed, each paper must be reviewed to determine whether it meets the inclusion criteria.
This involves examining the title, abstract, and sometimes the full text to assess whether Rubin Observatory data or services were substantively used.
The CST staff conducts the initial review, but final decisions are made by Rubin Science leadership to ensure consistency and quality.

A paper is eligible for inclusion if it meets the following conditions:

- It presents a scientific analysis based on Rubin Observatory data services or data products, such as data releases (e.g., DP0, DP1, DP2, DR1).
- The paper uses the data products to base some or all of its scientific conclusions.
- It is published in a refereed journal
- It is Rubin Observatory technical documentation, arxiv preprints and research notices deemed appropriate for the library
- It is a non-refereed Rubin paper deemed appropriate for the library (e.g., SITCOMTN, RTN, or other paper describing the scientific contributions of Rubin)
- It is a paper deemed appropriate for the library by the Publication Board


Exclusion criteria
------------------

We exclude the papers that have the following parameters:

- It is not a scientific analysis based on Rubin data products.
- Uses only mock catalogs, simulations, or LSST design parameters without incorporating Rubin data.
- Mentions Rubin Observatory only in passing, such as in the background/introduction, acknowledgments, or future work sections.
- Uses Rubin images solely for illustrative purposes without scientific analysis.
- Is a proposal, abstract, erratum, or unpublished preprint.
- Focuses on technical or software development (the paper is eligible for the technical publications list).


Adding a paper to the Vera C. Rubin Scientific Publications library
-------------------------------------------------------------------

The process for adding a paper to the Scientific Publications Library is as follows:

1. Perform the relevant citation search from links provided in Appendix A.
2. Review the papers and decide which ones should be included in the library.
3. Select paper(s) by checking the box next to the paper, then click Bulk Actions (Figure 1).
4. From the Bulk Actions dropdown menu, select Add to Library (Figure 2).
5. Click within the Select Library bar, then choose “Vera C. Rubin Observatory Scientific Publications” (Figure 3).
6. Click “Submit” to complete the process (Figure 4).


.. figure:: .github/_static/fig1_select_papers.png
   :alt: Screenshot of SciX interface which allows users to select papers to add to the library. 
   :width: 500px
   :align: center

   Figure 1 - Select paper(s) from search results


.. figure:: .github/_static/fig2_add_to_library.png
   :alt: From the bulk actions dropdown menu, select "Add to Library" 
   :width: 500px
   :align: center

   Figure 2 - From Bulk Actions dropdown menu, select “Add to Library”


.. figure:: .github/_static/fig3_select_library.png
   :alt: Screenshot of dropdown menu where user will select the appropriate library. 
   :width: 500px
   :align: center

   Figure 3 - Select “Vera C. Rubin Observatory Scientific Publications” library


.. figure:: .github/_static/fig4_click_submit.png
   :alt: Screenshot showing the location of the submit button. 
   :width: 500px
   :align: center

   Figure 4 - Click “Submit” to complete the process



Reporting
---------


The curated scientific library currently lists the total number of papers added that meet established criteria for relevance and quality.

To compile the annual CST reporting metrics:

- Click on the library link (above)
- Click on “view results in search filter”
- filter the SciX public library for the appropriate months (within the fiscal year: 10/1/XX - 9/30/XX)
- Select for refereed papers by clicking on the refereed button on the left hand side
- note the number of search results and report into the appropriate annual report

Future enhancements to this process and CST annual report metrics may include categorization of publications by type and monitoring the pace of additions over time.

=====================================
Technical library maintenance process
=====================================

TBD - Tim Jenness



==============================
Appendix A SciX search queries
==============================

This appendix provides a reference list of Rubin Observatory resources, such as technical publications and data releases,
that are commonly cited in scientific literature.
Each entry includes its SciX bibcode and a sample search query to help identify relevant publications for inclusion in the Rubin Scientific Publications Library.


Additional searches will be included in this list as new technical notes and datasets become available. 

**NOTE - After performing the search, click on the refereed tab on the left hand side to review refereed papers.
While it is possible to construct the search which will return refereed papers, it was determined that the extra step of selecting only refereed papers provided more flexibility.**


.. list-table:: SciX search queries
   :header-rows: 1
   :widths: 20 20 15 45

   * - Bibcode and Link to SciX query
     - Title
     - Type
     - SciX Search Query

   * - 2025rubn.rept...31N
     - RTN-095, The Vera C. Rubin Observatory Data Preview 1
     - Technical note
     - citations(bibcode:2025rubn.rept...31N)

   * - 2025lsst.data....3N
     - Legacy Survey of Space and Time (LSST) Data Preview 1
     - Dataset
     - citations(bibcode:2025lsst.data....3N)

   * - Rubin Observatory AND year:2026 – Science Explorer Search
     - Rubin Observatory and Year
     - Phrase search and year
     - Rubin Observatory AND year:2026

   * - Rubin Data Preview 1 AND year:2026 – Science Explorer Search
     - Rubin Data Preview 1
     - Phrase search and year
     - Rubin Data Preview 1 AND year:2026

   * - LSST Data Preview 1 AND year:2026 – Science Explorer Search
     - LSST Data Preview 1
     - Phrase and year search
     - LSST Data Preview 1 AND year:2026

   * - LSST Data Preview 0 AND year:2026 – Science Explorer Search
     - LSST Data Preview 0
     - Phrase and year search
     - LSST Data Preview 0 AND year:2026

   * - Rubin Data Preview 0 AND year:2026 – Science Explorer Search
     - Rubin Data Preview 0
     - Phrase and year search
     - Rubin Data Preview 0 AND year:2026



===============================
Appendix B Creating new queries
===============================

As Rubin Observatory releases new data or technical notes, additional search criteria may be needed.Construct effective queries using SciX Help or the following basic guidelines:

- To find bibcodes:

  - Review DOI for data releases.  Search for the data release DOI in SciX and the bibcode is listed underneath: for example, in the search box, use  **10.71929/rubin/2570308**
  - Review DOI or bibcode for technical notes or publications. Search for and find bibcodes technical papers: for example, in the search box, use **(title:”RTN-095”)**

- To refine search for a specific timeframe:

  - For annual reviews: use **year:2025**
  - For rolling updates: use **year:2025 or year:2024**
  - For more specific date criteria: use **date:[2024-01 to 2025-12]**

- To construct a search based on a bibcode: use **citations(bibcode: XXX)**
- To use a bibcode with specific timeframe: use **citations(bibcode:XXX) AND year:2025**
- To search for multiple bibcodes: use **citations(bibcode:XXX OR bibcode:YYY)**
- To search with keywords and a timeframe: use **(title:”XXX” OR abstract:”YYY”) AND year:2025**

