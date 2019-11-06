<!--
	Title: Student Worker Adobe Entitlements - DRAFT
	Author: Glen Piper
	Date: 19.11.04

	(State & outline the reasons for, and approach to, managing requests for student workers to get Adobe entitlements.)
-->

### DRAFT: Scope, Case, and Workflow - Granting & Managing Adobe Entitlements for Student Workers

STATEMENT
Some student workers have a business requirement need to have access to the latest version of Adobe apps, both on a personal laptop and/or an office computer.

- Employment office business requirements dictate that a student worker must use the latest version to create work for submission outside the employment office (e.g., output submitted to Marcom for processing).
- The serial key version (SK), used in the labs & currently made available on computers allocated specifically as "student worker use" desktops in CMDB, cannot be used, as the packaged version only gets updated once or twice a year.
- The Adobe entitlement allows the user to install & keep apps updated via the Adobe CC desktop app on a personal laptop as well as on an office desktop that is shared with other entitlement holders.

CURRENT SCOPE:

- Full-time faculty & staff (FS) are granted access via entitlements.
- Students (STU) are granted entitlements on a semesterly basis, if they are enrolled in a course that is specified by the Dean of Students' office.
	- All ART course sections & specified MCOM course sections.
- Both FS & STU entitlement lists use AD groups that are synced with the entitlement server.
- The student AD group is created based on a table view export of course enrollment data from Banner, and kept up-to-date by daily(?) checks
- The FS AD group is created based on the members of the Banner “Faculty Staff" role, and checked/reconciled on a daily(?) basis.
- No STU in FS AD group.
- FS enrolled in a course will consume 2 entitlements
- Student workers are supposed to be covered by SK (above).

NEEDS: 
Since there are edge use cases that are not covered by current programatic processes (e.g., student workers not currently enrolled in an entitlement-eligible course, who are working in a position that precludes the use of the SK solution).
 
- IT@Sam needs to provide a solution that fully supports these edge use case "exceptions”.

PROPOSED:

- Define exception request process/procedure.
- Document the edge use-cases, as they are encountered, when standard (SK) solution won’t suffice for student workers.
- SD Manager will:
	- Document requests.
	- Manage the lifecycle of adding/removing eligible student worker usernames from the new, manually managed, AD group.
- Server Admin will need to create a new AD group and ensure that this group sync with the Adobe entitlements server.