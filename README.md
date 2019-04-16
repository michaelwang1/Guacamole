# UCSF Epic Clarity Onboarding
This is meant to be a general onboarding document for new clarity reporters at UCSF.  We anticipate that it may also have value for experienced report writers who may be exploring new table spaces.  Feel free to contact one of the document owners if you have suggests/ want to contibute.
  -Mike

## Guide for scoping data requests
### [Data Request Scoping Guide](https://docs.google.com/presentation/d/1NxsHZzNIuWxLmE-EiCp02ErCGnVrm7Xpy0VY3-aJC0c/edit?usp=sharing)
  
## Encounters
  The most important tables to look at when reporting on encounters are pat_enc, pat_enc_hsp, and hsp_account.  
### Inpatient 
  Inpatient encounters are fairly well defined.  The query CLIIR has been using can be found in this file.
### Outpatient
  Outpatient encounters are not as well defined as inpatient encounters.  Generally, we limit to the UCSF service area and the look for encoutners that have either a completed status or an arrival time as well as the hsp_account.ha_account_class = 'Outpatient'
### Emergency
  Emergency encounters are defined by having an ha_class as 'Emergency'.  Note that these encounters can have variable pat_enc.enc_type_c that we suspect is realted to whether the patient was actually admitted to the hospital or else discharged directly from the emergency room.  
  
## ADT Orders

## Notes
### Note edit trail
### Note Attribution
### Note Service
### Note templates

## Orders

## Medications

## Results
### Pathology Results
### Rasiology Reports

## Histories

## Diagnoses
## Access Log
## Flow sheets
