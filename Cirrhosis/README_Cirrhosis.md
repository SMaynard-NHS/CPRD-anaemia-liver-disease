The cirrhosis codelist was compiled using the following search terms within the EMIS medical dictionary:

cirrho (sis/tic)  
varice (s/al)  
portal hypertensi (on/ve)  
ascit (es/ic)  
chronic hep failure  
end stage liver disease
child-pugh
MELD
hepatorenal
hepatic encephalopath
stage 4 fibrosis
decompensated liver disease

Terms were extracted from ICD-10, SNOMED codelists and existing publicly available codelists.

Terms selected were for the purpose of identifying patients with cirrhosis in CPRD data using a recorded diagnosis of cirrhosis or with complications almost entirely occurring only in the presence of cirrhosis.

NB Jaundice was not included due to low sensitivity.  
Fibrosis and sclerosis were not deemed as cirrhosis.

Exclusion terms used were:
without cirrhosis|non-cirrhotic|ascites not demonstrated|chylous|no ascites|fetal|foetal|pancreatic|cardiac ascites|varicell|venous|vulval|vaginal|scrotal|retic|genital|perineal|pelvic|ligament|sublingual|lung|retinal|pulmonary|duodenal|stomal|prostate|ovar|oral|mesenteric|small intestine|ulcer|cord|scirrhous|thrombosed|primary biliary|eczema|varices - other|malignant

For liver transplant the inclusion and exclusion search terms of the python code where updated as follows:

#Inclusion 
(?=.*liver)(?=.*transplant)|(?=.*liver)(?=.*recipient)|(?=.*hepat)(?=.*transplant)
#NB the above code allows for appearance of the terms included in any order e.g. liver tranplant OR transplantation of liver

#Exclusion
discussion|assessment|planned|donor|exploration|awaiting|present|structure
