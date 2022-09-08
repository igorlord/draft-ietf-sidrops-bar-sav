Hi all,

We (the authors) had presented this draft at the IETF 114 SIDROPS meeting in Philly.
Thanks for the discussion and comments we received at the mike and during individual conversations (especial thanks to Ben and Job for extensive and in-depth comments and ideas).
We have addressed several those comments in the updated version -01 draft which is available here:

https://datatracker.ietf.org/doc/html/draft-sriram-sidrops-bar-sav-01
 
In particular, we have added a new Section 6 with these topic areas: 

6.  Operations and Management Considerations</br>
  6.1.  Applicability of ASPA and ROA</br>
  6.2.  BAR-SAV and Routing Policy</br>
  6.3.  Where to Deploy BAR-SAV</br>
  6.4.  Automation is the Key</br>
  6.5. Implementation Guidelines</br>
    6.5.1. Management of Local RPKI Repository Caches</br>
    6.5.2. Management of Objects Temporarily Missing from RPKI Repositories

Please let us know your thoughts on the above additions (Sections). We are open to any further suggestions.

We have received ideas about creating special "SAV" ASPA and ROA RPKI objects.
We have not added them to this version of the draft, but we are interested in discussing the need for them.
We would be especially interested in learning about situations when creating a regular ROA object just for SAV purposes would have any detrimental effect on the prefix owner.

Thank you.

Igor / Sriram / Doug 
