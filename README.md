# MCL_Proteogenotypes

This respository contains code from the analysis presented in the paper: 

## Proteogenotypes Define Biologically and Clinically Distinct Disease States in Mantle Cell Lymphoma

*Julius C Enssle<sup>1,2,3,4,26</sup>, Paul J Bröckelmann<sup>5,6,26</sup>, Claus Moritz Gräf<sup>5,6,26</sup>, Björn Häupl<sup>1,2,3,7</sup>, Arber Qoku<sup>2,7,8</sup>, Rahil Gholamipoorfard<sup>6</sup>, Daniel Bachurski<sup>6</sup>, Marta Pistone<sup>9</sup>, Adrian Georg Simon<sup>9</sup>, Moritz Reese<sup>5,6</sup>, Sebastian Wolf<sup>1,2,3,10</sup>, Leon Hafner<sup>5</sup>, Sebastian Scheich<sup>1,2,3,10</sup>, Tonio Brinkschmidt<sup>1</sup>, Martine Pape<sup>1,2</sup>, Marion Bodach<sup>1,2,7</sup>, Dominique Jahn<sup>1,2,7</sup>, Heona Lee<sup>1</sup>, Charlotte Joest<sup>1</sup>, Uwe Plessmann<sup>2,11</sup>, Henning Urlaub<sup>11,12</sup>, Fabian Ullrich<sup>13,14</sup>, Julia Richter<sup>15</sup>, Hilka Rauert-Wunderlich<sup>16</sup>, Grzegorz Rymkiewicz1<sup>7</sup>, Annette M. Staiger<sup>18</sup>, German Ott<sup>19</sup>, Melanie Thelen<sup>5,6</sup>, Nima Abedpour<sup>6</sup>, Martin Peifer<sup>20</sup>, Bastian von Tresckow<sup>13</sup>, H. Christian Reinhardt<sup>13</sup>, Wolfram Klapper<sup>15</sup>, Andreas Rosenwald<sup>16</sup>, Reinhard Buettner<sup>9</sup>, Giorgio Inghirami<sup>21</sup>, Eva Hoster<sup>22,23</sup>, Michael Hallek<sup>6</sup>, Louis M. Staudt<sup>4</sup>, Florian Buettner<sup>2,3,7,8,24</sup>, Martin Dreyling<sup>25</sup>, Ron D Jachimowicz<sup>5,6,27,28#</sup>, and Thomas Oellerich<sup>1,2,3,7,27</sup>*

Affiliations:\
<sub>1 Department of Medicine, Hematology and Oncology, University Medical Center, Goethe University Frankfurt, Frankfurt am Main, Germany \
2 German Cancer Consortium (DKTK), partner site Frankfurt/Mainz, a partnership between DKFZ and UCT Frankfurt-Marburg, Frankfurt am Main, Germany \
3 Frankfurt Cancer Institute (FCI), Frankfurt am Main, Germany \
4 Lymphoid Malignancies Branch, National Cancer Institute, National Institutes of Health, Bethesda, MD, USA \
5 Max Planck Institute for Biology of Ageing, Cologne, Germany \
6 Department I of Internal Medicine, Center for Integrated Oncology Aachen Bonn Cologne Duesseldorf (CIO ABCD), Faculty of Medicine and University Hospital Cologne, University of Cologne, Cologne, Germany \
7 German Cancer Research Center (DKFZ), Heidelberg, Germany \
8 Goethe University Frankfurt, Department of Computer Science and Mathematics, Institute for Informatics, Frankfurt am Main, Germany \
9 Institute of Pathology, University Hospital Cologne, Medical Faculty, University of Cologne, Cologne, Germany \
10 University Cancer Center (UCT), Frankfurt am Main, Germany \
11 Bioanalytical Mass Spectrometry, Max Planck Institute for Multidisciplinary Sciences, Göttingen, Germany \
12 Bioanalytics, Department of Clinical Chemistry, University Medical Center Göttingen, Göttingen, Germany \
13 Cancer Research Center Cologne Essen (CCCE); Department of Hematology and Stem Cell Transplantation, West German Cancer Center and German Cancer Consortium Partner Site Essen, University Duisburg-Essen, University Hospital Essen, Germany \
14 Research Institute of Molecular Pathology, Vienna, Austria \
15 Department of Pathology, Hematopathology Section and Lymph Node Registry, University Hospital Schleswig-Holstein - Campus Kiel, Kiel, Germany \
16 Institute of Pathology, University of Würzburg, Würzburg, Germany \
17 Department of Cancer Pathomorphology, Maria Sklodowska-Curie National Research Institute of Oncology, Warsaw, Poland \
18 Department of Clinical Pathology, Robert-Bosch-Krankenhaus, Stuttgart, Germany; Dr. Margarete Fischer-Bosch Institute for Clinical Pharmacology, Stuttgart and University of Tuebingen, Tuebingen, Germany \
19 Department of Clinical Pathology, Robert-Bosch-Krankenhaus, Stuttgart, Germany  \
20 Department of Translational Genomics, Faculty of Medicine and University Hospital Cologne, University of Cologne, Cologne, Germany \
21 Division of Hematology and Medical Oncology, Department of Medicine, Weill Cornell Medicine/NewYork-Presbyterian Hospital, New York, NY, USA \
22 Institute for Medical Information Processing, Biometry, and Epidemiology (IBE), LMU Medizin, Ludwig-Maximilians-Universität München, Munich, Germany \
23 Pettenkofer School of Public Health, Munich, Germany \
24 Goethe University Frankfurt, Department of Medicine, Frankfurt am Main, Germany \
25 Department of Medicine III, LMU University Hospital, Munich, Germany \

26 These authors contributed equally \
27 These authors contributed equally  \
28 Lead contact


Corresponding author (#) email: rjachimowicz@age.mpg.de


### Following analysis code is included:
- Integration of RNA and Protein expression data using MuVI, see also: https://github.com/MLO-lab/MuVI
- Inference of MCL proteogenotypes
- WESeq data processing
- scRNA sequencing data processing integration, SEACell integration, DA testing by miloR

### Data availablity:
- WESeq and RNA expression data: EGA number to be included
- Protein expression data: https://massive.ucsd.edu/ProteoSAFe/static/massive.jsp, MSV000102760
- scRNA sequencing data: EGA number to be included

### MCL proteogenotype classifier:
https://github.com/MLO-lab/mcl-classifier

For further questions, please reach out the the corresponding author.
