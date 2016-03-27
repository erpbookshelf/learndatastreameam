# Preventive Workorder

The WORKWOST install parameter determines the first status of the PM work order when it is released. Ensure that the user/group that would be generating the WO has the Status Authorization from 'A' (Awaiting Release) to the status code set for the WORKWOST install paramter.

## Duplicate PM

When releasing Duplicate PM work orders, ensure that the checkbox for Duplicate PMs is selected on the Generate WO screen. On the Preview tab, if you select a later Duplicate PM entry, the system will prompt you to indicate that you want to skip the older entries (thus allowing a bypass of the old entries if they are at a past date).
