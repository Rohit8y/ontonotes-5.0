# ontonotes-5.0

OntoNotes Release 5.0
LDC2013T19
Introduction

OntoNotes Release 5.0, Linguistic Data Consortium (LDC) catalog number LDC2013T19 and ISBN 1-58563-659-2, is the final release of the OntoNotes project, a collaborative effort between BBN Technologies, the University of Colorado, the University of Pennsylvania and the University of Southern California's Information Sciences Institute. The goal of the project was to annotate a large corpus comprising various genres of text (news, conversational telephone speech, weblogs, usenet newsgroups, broadcast, talk shows) in three languages (English, Chinese, and Arabic) with structural information (syntax and predicate argument structure) and shallow semantics (word sense linked to an ontology and coreference).

OntoNotes Release 5.0 contains the content of earlier releases -- OntoNotes Release 1.0 LDC2007T21, OntoNotes Release 2.0 LDC2008T04, OntoNotes Release 3.0 LDC2009T24 and OntoNotes Release 4.0 LDC2011T03 -- and adds source data from and/or additional annotations for, newswire (News), broadcast news (BN), broadcast conversation (BC), telephone conversation (Tele) and web data (Web) in English and Chinese and newswire data in Arabic. Also contained is English pivot text (Old Testament and New Testament text). This cumulative publication consists of 2.9 million words with counts shown in the table below.
	Arabic 	English 	Chinese
News 	300k 	625k 	250k
BN	n/a	200k	250k
BC	n/a	200k	150k
Web	n/a	300k	150k
Tele	n/a	120k	100k
Pivot	n/a	n/a	300

The OntoNotes project built on two time-tested resources, following the Penn Treebank for syntax and the Penn PropBank for predicate-argument structure. Its semantic representation includes word sense disambiguation for nouns and verbs, with some word senses connected to an ontology, and coreference.
Data

Documents describing the annotation guidelines and the routines for deriving various views of the data from the database are included in the documentation directory of this release. The annotation is provided both in separate text files for each annotation layer (Treebank, PropBank, word sense, etc.) and in the form of an integrated relational database (ontonotes-v5.0.sql.gz) with a Python API to provide convenient cross-layer access.

It is a known issue that this release contains some non-validating XML files. The included tools, however, use a non-validating XML parser to parse the .xml files and load the appropriate values.
Tools

This release includes OntoNotes DB Tool v0.999 beta, the tool used to assemble the database from the original annotation files. It can be found in the directory tools/ontonotes-db-tool-v0.999b. This tool can be used to derive various views of the data from the database, and it provides an API that can implement new queries or views. Licensing information for the OntoNotes DB Tool package is included in its source directory.
Directory Structure

Please see file.tbl for a complete file list as well as checksums for this publication.

    data/ - Contains the Ontonotes data files, subdivided by language and source.
    docs/ - Contains additional documentation and a file table.
    tools/ - Contains the OntoNotes DB Tool v0.999 beta and additional documentation.

Updates

Additional information, updates, bug fixes may be available in the LDC catalog entry for this corpus at LDC2013T19.
Acknowledgment

This work is supported in part by the Defense Advanced Research Projects Agency, GALE Program Grant No. HR0011-06-1-003. The content of this publication does not necessarily reflect the position or policy of the Government, and no official endorsement should be inferred.
Content Copyright

Portions © 2006 Abu Dhabi TV, © 2006 Agence France Presse, © 2006 Al-Ahram, © 2006 Al Alam News Channel, © 2006 Al Arabiya, © 2006 Al Hayat, © 2006 Al Iraqiyah, © 2006 Al Quds-Al Arabi, © 2006 Anhui TV, © 2002, 2006 An Nahar, © 2006 Asharq-al-Awsat, © 2010 Bible League International, © 2005 Cable News Network, LP, LLLP, © 2000-2001 China Broadcasting System, © 2000-2001, 2005-2006 China Central TV, © 2006 China Military Online, © 2000-2001 China National Radio, © 2006 Chinanews.com, © 2000-2001 China Television System, © 1989 Dow Jones & Company, Inc., © 2006 Dubai TV, © 2006 Guangming Daily, © 2006 Kuwait TV, © 2005-2006 National Broadcasting Company, Inc., © 2006 New Tang Dynasty TV, © 2006 Nile TV, © 2006 Oman TV, © 2006 PAC Ltd, © 2006 Peoples Daily Online, © 2005-2006 Phoenix TV, © 2000-2001 Sinorama Magazine, © 2006 Syria TV, © 1996-1998, 2006 Xinhua News Agency, © 1996, 1997, 2005, 2007, 2008, 2009, 2011, 2013 Trustees of the University of Pennsylvania

Contact: ldc@ldc.upenn.edu
© 2013 Linguistic Data Consortium, Trustees of the University of Pennsylvania. All Rights Reserved.
