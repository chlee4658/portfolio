# Skmsg

## Public Summary

Recruiter-facing summary of a healthcare messaging automation project. It avoids patient data, credentials, private clinic details, and internal business information.

## Problem

After SkincareChart structured documentation workflows, appointment communication remained separate from scheduling and staff operations. Reminders, cancellations, rescheduling messages, inbound replies, and staff notifications required repeated coordination.

## Why It Mattered

Patient communication sits between clinical care and operations. If scheduling data, templates, replies, and staff confirmation steps are not connected, the workflow depends on memory and manual transfer between tools.

## Design Decision

I designed Skmsg as a messaging automation layer connected to appointment data. I used approved templates, API integrations, inbound webhook handling, and confirmation workflows so automation would remain controlled rather than free-form.

## What I Built

- Twilio SMS/MMS sending
- Incoming Twilio webhook handling
- Google Calendar appointment integration
- Appointment confirmation and reminder workflows
- Cancellation and rescheduling message templates
- Korean and English message templates
- Contact synchronization from SkincareChart
- Telegram confirmation flow for selected reminders
- Token-protected internal APIs for approved template messaging

## Technologies Used

Python, Flask, SQLAlchemy, SQLite, PostgreSQL, Railway, Twilio API, Google Calendar API, Telegram Bot API, Cloudflare/DNS.

## What I Learned

Healthcare automation requires guardrails. Templates, confirmation steps, auditability, deployment configuration, and failure handling are as important as the API connection itself.

## How It Led to the Next Project

Once messaging was automated, staff needed a faster operational interface for lookup and approved actions. That led to Telegram CRM Bridge.

## Career Relevance

Skmsg demonstrates healthcare workflow automation, patient communication workflow design, API integration, deployment operations, and controlled messaging patterns for clinic environments.
