---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* B.S. in Mechanical Engineering, University of California, Los Angeles (UCLA), 2025

Work experience
======

### Researcher (Autonomous Vehicle Safety) — UCLA B. John Garrick Institute for the Risk Sciences (GIRS)
*Nov 2024 – Present*  
Supervisor: Dr. Ali Mosleh, Dr. Camila Correa-Jullian, Jean-Paul Velez (SFCTA)

- Built a safety measurement and benchmarking framework for SFCTA to compare AV performance using consistent definitions and exposure-normalized rates.
- Developed a tiered metric library (45+ implementable metrics) and mapped each metric to the specific data fields required to compute it using STPA-based safety logic.
- Combined CPUC operational reporting, CA DMV disengagements, and NHTSA SGO crash reports into a consistent analysis structure with shared context tags (weather, lighting, road type, surface, initiator).
- Produced dashboards, briefings, and reporting recommendations specifying what data should be reported so agencies can monitor trends and compare operators reliably.

### Systems Integration Engineering Intern (Airbus A320neo FFS) — CAE + Flight Simulation Training Centre (FSTC), Gurgaon, India
*Jul 2024 – Sep 2024*  
Supervisor: Jean-Michel (CAE), Kuldeep Adhana (FSTC)

- Coordinated systems integration and commissioning of the CAE 7000XR A320neo Full Flight Simulator, coordinating day-to-day execution across CAE specialists, the FSTC site team, contractors, and logistics.
- Integrated the simulator visual stack (Tropos 6000, projectors, BP screen) and executed alignment, calibration, and functionality checks during bring-up.
- Led facility readiness and electrical integration work including power protection and grounding, transformer configuration changes, and resolving infrastructure issues that blocked commissioning (trenches, routing, climate-control/CVAC plumbing fixes).
- Performed troubleshooting and verification across motion and safety subsystems including actuator alignment corrections, VESDA smoke detection testing, and envelope testing to identify and escalate clearance constraints before acceptance.

### Production Engineering Intern — Complete Surveying Technology, Noida, India
*Jul 2023 – Sep 2023*  
Supervisor: Retd. Col Raj Suri

- Built and tested prototype parts for the 412D Digital Measuring Wheel including the spoke wheel and hand grip.
- Led an electronics upgrade by integrating a custom circuit board and microcontroller to add capability while reducing the electronics footprint.
- Ran supervised injection-molding prototype trials on a Mitsubishi 350-ton machine to produce trial parts and check fit and assembly.
- Verified durability using simulation and physical testing, and documented key manufacturing steps across two plants so design choices matched real production constraints.

### Production Engineering Intern — AGM Jactex AG, Schaffhausen, Switzerland
*Jun 2022 – Sep 2022*  
Supervisor: Mark Feer

- Executed hot-press gluing experiments for Vulcan fiber sheet production and managed sheet preparation workflows from raw material through pressing.
- Optimized adhesive distribution for Vulcan fiber sheets using ABAQUS FEA and 5-axis CNC machining to improve manufacturing precision and consistency.
- Built a harness rewinding improvement to reduce spool changeover time and increase hourly production; performed dye-change preparation and manual bobbin changes on braiding machines.
- Established preventive maintenance schedules and performed repair work on harness braiding machines, reducing downtime by 20%.

### Student Billing Analyst — UCLA Library Financial Services, Los Angeles, CA
*May 2022 – Sep 2024*  
Supervisor: Ami Baxley

- Managed invoice payments and ensured Los Angeles County tax compliance in Alma; built a Python automation to identify and aggregate county invoices, improving processing efficiency and reducing manual rework.

### Student IT Consultant — UCLA Undergraduate Information Technology (UIT), Los Angeles, CA
*May 2022 – Dec 2022*  
Supervisor: Tommy Chiu, Peter Blase

- Provided front-line IT support across walk-up, phone, and ticketing workflows covering MyUCLA, Gradebook, Outlook, and account access issues; onboarded new staff and created checklists to standardize recurring workflows and speed resolution.
  
Skills
======

- **Safety analysis methods:** Systems-Theoretic Process Analysis (STPA); Fault Tree Analysis (FTA); Event Tree Analysis (ETA); Failure Modes and Effects Analysis (FMEA); Quantitative Risk Assessment (QRA); Monte Carlo methods.
- **Safety standards awareness:** UL 4600; ISO 21448 (SOTIF).
- **Data and analytics tools:** Python; SQL; R; Power BI; Excel.
- **Engineering modeling and simulation tools:** MATLAB; Simulink; ANSYS (FEA); ABAQUS (FEA); SolidWorks (CAD); Fusion 360 (CAD).
- **Systems integration and verification (flight simulation):** troubleshooting and fault isolation; verification and acceptance testing; visual alignment and calibration; actuator alignment support; VESDA safety system testing; CVAC integration exposure.
- **Manufacturing and prototyping:** injection molding prototyping; CNC and 5-axis CNC exposure; hot-press and lamination process exposure; stress–strain testing (ZwickRoell).
- **Technical communication and coordination:** technical writing; stakeholder briefings; structured documentation; cross-team coordination; process standardization (rubrics, templates, checklists).

Projects
======

<ul>
  {% for p in site.portfolio %}
    <li><a href="{{ p.url | relative_url }}">{{ p.title }}</a></li>
  {% endfor %}
</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======

### Research Mentorship — UCLA B. John Garrick Institute for the Risk Sciences (GIRS)

- Supervised two volunteer undergraduate students (UCLA and Georgia Tech) contributing to research projects leading to conference publications.

### Facilitator (Team Lead) — Challenge Course, UCLA Recreation

- Trained and supervised 25+ Program Assistants and facilitated high and low element sessions using structured briefings, safety discipline, and end-of-session debriefs.

### Philanthropy Chair — Sigma Pi Fraternity, UCLA

- Organized fundraising concerts, campus tabling events, and a beach cleanup; raised $11K for A Place Called Home and LA wildfire relief.


