# Comment 
Another attempt to integrate text-mining (INDRA from @Ben Gyori @John Bachman) with the human curation to assist curators in finding articles related to those they have already shown interest. The workflow: 

1. Grab PMIDs currently in a diagram
2. Find PMIDs that cite the PMIDs already in the diagram (from previous step) and have interactions in the INDRA dataset (as of June 23)
3. Extract the interactions from INDRA for these new papers along with other evidentiary PMIDs for the interactions

Two suggestions arise for the PAMP pathway (http://web.newteditor.org/?URL=https://cannin.github.io/covid19-sbgn/COVID19_PAMP_signaling.xml.sbgn): 

1. The STING protein is involved in IRF3 activation yet it is not on the PAMP diagram (screenshot; full output: https://cannin.github.io/covid19-analysis/pamp_20200624.html)
2. There is evidence that IRF3 and IRF7 can heterodimerize (not show on the diagram; more info: https://www.cell.com/immunity/pdf/S1074-7613(06)00394-3.pdf) to induce IFN genes. 

I don't have any systematic output at this point, but feedback on the approach would be welcomed. 
