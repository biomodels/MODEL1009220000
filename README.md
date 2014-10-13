

**A systems biology study of two distinct growth phases of _Saccharomyces cerevisiae_ cultures **   
AM Martins, D Camacho, J Shuman, W Sha, P Mendes, V Shulaev, Current Genomics
2004 5:649-663

This is a model of yeast glycolysis and glycerol synthesis for high medium
glucose concentration. It was constructed by joining the glycolysis model of
Teusink et al. (2000) Eur J Biochem 267, 5313, modified by Pritchard and Kell
(2002) Eur. J. Biochem. 269, 3894, with the glycerol synthesis model of
Crownright et al. (2002) Appl. Env. Microbiol. 68, 4448. Glycerol transport
was added as a first order reaction with parameters that comply with empirical
data on internal/external glycerol ratios.

**Curation notes**   
The model provided by the authors is available from
<http://www.mcisb.org/resources/models/martins04_original.xml> . It contains
one error: the kinetic law of glycerol 3-phosphate dehydrogenase has
denominator of the form  
(1+NADH/Kdhap+NAD/Kg3p)*(1+DHAP/Knadh+G3P/Knad)  
rather than  
(1+DHAP/Kdhap+G3P/Kg3p)*(1+NADH/Knadh+NAD/Knad).  
This has now been corrected; steady states of the original model may be
resolved by exchanging the order of substrates and products in
[COPASI](http://www.copasi.org/) . Some other cosmetic changes (e.g minutes to
seconds) have also been carried out.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

