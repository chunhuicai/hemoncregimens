
ordering bettween phases as per episode annotation guielines
* do a specific example model a course, regimen, protocol https://hemonc.org/wiki/Acute_myeloid_leukemia,_pediatric https://hemonc.org/wiki/Acute_myeloid_leukemia,_pediatric
 
 
* local vs supportive therapy
* distinguishing lines from protocols

* do we need to order cycles/regimens in regumens ? if so, how?  use owllist as per drummond et al.
  is ordering within a regimen important ? within a phase?

*  cancer vs. anti-cancer intent?

* define medication adminstration in more detail and as per Jeremy's emails
** dose
** counts
** timing?
** etc..

* medication
** dosing
** route

DONE
* add names for protocols and regimens
   name property
* haspublication
* publication - has DOI
* look at duration property - subpropoerties hasduration days
  has duration weeks.
* can i find an example of a course with cycles?
* mail jeremy
  dropbox/list of questoins ?
  - definitions
  - troble running code
  - reviewing which is the protocol/course/regimen
  - list of phases?
- treatment context -hasLine, has Phase-
- add a diagnosis - associated with a protocol


add subclasses of medication administration for local
    	       anticancer
	supportive
	

- treatment context -hasLine, has Phase-

If it is intended to be given once, but might be repeated, it is a course. A regimen that occurs in isolation is stand-alone,

-treatmentList hasTreatment someTreatment (exactly1)
 treatmentList hasPhase somePhase (exactly 1)
 protocol has treatment list
model regiment with types of medication adminsistration.
      anticancer
      local
      supportive
      treatment modality `

* regimen
* phase
* protocol  definition
* line definition* phase, line, protocol, regimen relations

- review of definitions of regimen, protocol, line, intent...

  flesh out line

-mail jeremy
      are phasess asoociated with reigmens? Lines? If we downplay protocol, where do phases fit itn ?
        depreate treatment contesxt
