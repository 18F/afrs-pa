# US Air Force Recruiting Service Path Analysis

## Welcome!
This repository contains documentation describing the Air Force Recruiting Service (AFRS) Path Analysis engagement. It is intended to be a place where project team members, stakeholders, and other interested parties can keep track of goals and resources as we work together. 

## History

### AFRS

The mission of Air Education and Training Command (AETC) begins with the Air Force Recruiting Service (AFRS), with headquarters at JBSA-Randolph, Texas. The AFRS mission is to recruit quality men and women with the right skills, at the right time, in the right numbers to sustain the combat capability of the U.S. Air Force. 

(adapted from http://www.aetc.af.mil/Air-Force-Recruiting-Service/)

### Engagement

The Department of Defense (DoD) has engaged with 18F in a path analysis to assess the current state of Air Force Recruiting Information Support System-Total Force (AFRISS-TF) system and develop a high-level vision for a more modular and mobile-friendly system.

While 18F will not specify the future state system over the course of the eight-week effort, it will help set direction and promote alignment within AFRS around which aspects of a new system are most important to pursue.


## Users and stakeholders

AFRS comprises three regional groups and 27 squadrons with more than 1,200 recruiters assigned throughout the United States, England, Germany, Japan, Puerto Rico and Guam. The Air Force brings in nearly 24,000 active-duty enlisted accessions each year. The command is responsible for accessing 100 percent of the enlisted force, 90 percent of the service's medical officers, approximately 25 percent of the line officers (through Officer Training School) and 100 percent of Air Force chaplains.

(from http://www.aetc.af.mil/Air-Force-Recruiting-Service/)


### AFRS Project Management Office (PMO)

The system is managed by a product owner and three other deputy program managers that represent the three Air Force components (Active Duty, Reserve, and Air National Guard) 

### Vendor

A contractor and subcontractor provide project management, system administration, configuration management, and software life-cycle management as well as maintenance and sustainment, database administration, requirements validation and implementation, and help desk support. They also provide Information Assurance support (to include System Certification & Accreditation).


## System

AFRISS-TF is the system of record for all session processing activities for all three Air Force components. It contains all information collected from first contact with a candidate through an individual being sworn in and being shipped for training.

Information contained within the system includes (but is not limited to): 
 - Leads (i.e. data pertaining to recruited candidates)
 - Analysis and development of leads
 - Follow-on information and documents
 - Security clearance information for Active Duty recruits, which is used to create a SF-86 form which is sent to Office of Personnel Management (OPM)
  - A log of when recruits are shipped to basic training

The platform consists of Oracle 11g database and other associated Oracle products and is coded in PL/SQL.

The operational and training environments are currently hosted at the Defense Information Systems Agency (DISA) Defense Enterprise Computing Center (DECC). DISA provides network and hardware support for these environments.

## Development

The current team is using a Functional Review Board (FRB) with a 5-6 week cadence for making software enhancements, including patching and adding new capabilities. Generally, all components must agree on what enhancements are prioritized. 

## Product vision

- Shape the Air Force of tomorrow - Inspire, Engage, and Recruit
- A more data-centric system that users can access more readily with less training
- Present users a functional, modern interface
- Help recruiters spend more time recruiting and less time interacting with the system and waiting on approvals
- Develop better reporting so leaders and recruiters have even more information to inform their work


## Our approach
The following five sections represent prioritized areas related to AFRISS-TF that we would like to explore as we determine a path to modernize the system to better meet the needs of its users during this engagement and beyond. 
Given our limited time, we almost certainly will not explore any section comprehensively; rather, we will select from these each week as we prioritize our work relative to our capacity.

1. User research
2. Systems audit and understanding capabilities
3. Assess viability of going to COTS product
4. Development process review
5. Develop roadmap



## Planned deliverables

We will work collaboratively to conduct research, synthesize collected data, and make findings and recommendations for Air Force to achieve a modularized version of AFRISS-TF that better meets user needs.

The engagement focuses on identifying the key capabilities and characteristics of the future state system and outlining a roadmap for modernization that results in decreased training costs, increased accessibility and mobility, and greater flexibility through a more modular configuration. 

## Risks and mitigations

**Risk:** If it takes time to identify/schedule research participants, this could reduce our potential impact.  
**Mitigation:** We press hard for contacts/interviews but move forward with other work in the meantime.

**Risk:** Time is, by design, short. This engagement can go many ways as we define our eventual scope.  
**Mitigation:** Team to commit to a path early on and dig in. Partner accepts that the work done will not be a comprehensive review of everything that is possible.

**Risk:** Important concerns go unaddressed until they swell into larger problems.  
**Mitigation:** Surface obstacles and anxieties early so we can address them as they arise.

**Risk:** Balancing/prioritizing needs of three different components (Air Force, Reserve, Guard) could result in us either not targeting the highest-value opportunities or possibly spreading our efforts unnecessarily thin.  
**Mitigation:** Determine when the time is right to focus on just one component and when it is best to include all three.

**Risk:** If recommendations are not grounded in technical reality, roadmap delivered will not be actionable.  
**Mitigation:** Bring on 18F engineer to support team. Partner continue to help with access to AFRS and vendor teams.


## Tools
 - [Team notes document](https://docs.google.com/document/d/1t5LBQJKpPr0poo91VDw96UE4qhISYygmZ2OyBWXNEZA/edit#)
 - [Statement of Work](https://docs.google.com/document/d/1sRO7MsKep3qxmNSQkCK7-LgwH4ukavb6PasWjU-aCJQ/edit)
 - [Google Drive folder](https://drive.google.com/drive/u/0/folders/15_hzcako6YoYnSl_0apZHuLhLVpLTLkS) 
 - [Trello board](https://trello.com/b/1LRQgbGk/usaf-recruiting-service-path-analysis)


## Tock and staffing

- The 18F Tock code for billing time to this project is AFRS Path Analysis #784
- [18F staffing issue](https://github.com/18F/staffing-and-resources/issues/481)

## Project team and roles

### AFRS

**Lieutenant Colonel Grayln Wimberly (Product Owner)** — Serve as single point of contact for AFRS for purposes of decisions needed to move the engagement forward. Collaborate with the development team. Keep team and stakeholders informed, soliciting their feedback. Highlight and work to mitigate risks. Communicate feedback and help prioritize the team’s effort. Assist with research recruitment, data collection, and analysis.

**Master Sergeant Jared Martin** — Serve as subject-matter expert (SME). Assist with research recruitment, data collection, and analysis. Backup PO.

### 18F

**James Hupp (Content Designer/Strategist)** — Evaluate existing content artifacts. Lead research recruitment, data collection, and analysis.

**Andrew Suprenant (Product Manager)** — Articulate vision for engagement in collaboration with the product owner. Regularly select work of highest value to be prioritized in sprints. Cultivate alignment of product owner, development team, and key stakeholders. Identify and work to resolve obstacles. Highlight and work to mitigate risk. Ensure progress moves forward and that the 18F team delivers. 

**Kenny Daniel (Account Manager)** — Provide support to project team and serve as liaison between AFRS and 18F. 




## Contributing

To provide feedback on this repository, [open an issue](https://github.com/GSA/afrs-pa/issues/new).

### Public domain

This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
