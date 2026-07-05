# SKChart

## Public Summary

Recruiter-facing summary of a Clinical Informatics healthcare workflow project. It avoids patient data, credentials, private clinic details, and internal business information.

SKChart is presented here as a healthcare workflow platform developed from real clinical practice.

## Overview

SKChart was developed from daily clinical practice, long-term EMR use, clinic operations, and fragmented documentation workflows.

## Clinical Problem

Clinic charting, clinical photos, visit notes, consent documents, product/payment context, and operational records were fragmented across disconnected workflows.

## Why It Mattered

As a physician and clinic operator, I needed documentation to reflect the real sequence of a clinic visit. The workflow was not only about entering data; it involved clinical context, visual records, patient-facing documents, staff handoffs, and operational follow-up.

## Design Decision

I designed SkincareChart as a local-first charting and workflow system centered around the patient record. The architecture prioritized structured visit context, privacy-sensitive file handling, and a practical interface for daily clinic use.

## What I Built

- Patient profile management
- Visit documentation and visit history
- Treatment and procedure charting
- Clinical photos grouped by visit
- PDF consent and document handling
- Product and payment tracking
- Statistics and operational reporting
- Role-based access and admin/staff controls
- Local-first handling for privacy-sensitive clinic files

## Clinical Workflow Impact

- Documentation: keeps visit context, treatment notes, photos, and history connected.
- Workflow: reduces fragmentation between charting, documents, payments, and operations.
- Communication: exposed the need for a dedicated messaging workflow, which led to Skmsg.
- Operations: supports role-based review, reporting, and staff workflow coordination.

## Technologies Used

Python, Flask, SQLite, HTML, CSS, JavaScript, Git, GitHub.

## Development Log

Structured patient records, visit-based notes, photo annotation, and operational reporting were refined through real workflow observation and use.

## What I Learned

Clinical software has to match the order of work. Building the charting layer clarified that documentation was only one part of the operational loop; appointment communication and follow-up workflows still needed their own system design.

## How It Led to the Next Project

SkincareChart exposed the next workflow gap: appointment reminders, patient communication, cancellations, replies, and staff confirmation steps were still handled outside the charting workflow. That led to Skmsg.

## Future Roadmap

Continue integrating documentation, communication, and staff operations into a connected healthcare workflow platform.

## Career Relevance

SKChart demonstrates clinical workflow analysis, structured documentation design, healthcare operations knowledge, local-first data handling, Clinical Informatics implementation, and hands-on healthcare workflow development.
