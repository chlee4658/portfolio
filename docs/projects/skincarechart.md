# SkincareChart

## Public Summary

Recruiter-facing summary of a healthcare workflow project. It avoids patient data, credentials, private clinic details, and internal business information.

Public product landing page: [skchart.com](https://skchart.com)

## Problem

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
- Public landing page for early product validation after real workflow use

## Technologies Used

Python, Flask, SQLite, HTML, CSS, JavaScript, Git, GitHub.

## What I Learned

Clinical software has to match the order of work. Building the charting layer clarified that documentation was only one part of the operational loop; appointment communication and follow-up workflows still needed their own system design.

Launching skchart.com helped turn an internally operated workflow tool into a public-facing product surface without exposing patient data or private clinic details.

## How It Led to the Next Project

SkincareChart exposed the next workflow gap: appointment reminders, patient communication, cancellations, replies, and staff confirmation steps were still handled outside the charting workflow. That led to Skmsg.

## Career Relevance

SkincareChart demonstrates clinical workflow analysis, structured documentation design, healthcare operations knowledge, local-first data handling, public product validation, and hands-on healthcare software development.
