# Telegram CRM Bridge

## Public Summary

Recruiter-facing summary of a staff operations assistant project. It avoids patient data, credentials, private clinic details, and internal business information.

## Problem

After charting and messaging workflows were implemented, staff still needed a faster way to look up operational context and trigger approved communication actions without unsafe free-form write access.

## Why It Mattered

Staff-facing automation has to be quick, predictable, and controlled. A useful interface should support daily operations while preserving permission boundaries, confirmation steps, and privacy-conscious logging.

## Design Decision

I separated lookup actions from write actions. I added approved templates, confirmation gates, audit behavior, reversible feature flags, and compatibility with existing command workflows to make rollout safer.

## What I Built

- Telegram Bot API webhook service
- Customer lookup
- Booking lookup
- Approved template message preview and send flow
- Confirmation gates before external messaging actions
- Audit logging
- Reversible feature flags
- Legacy command compatibility
- Privacy-conscious audit behavior that avoids storing raw staff messages

## Technologies Used

Node.js, TypeScript, Telegram Bot API, HTTP webhook service, feature flags, JSON action schemas, allowlisted actions, automated tests, Mac mini LaunchAgent.

## What I Learned

Operational interfaces need clear boundaries. Lookup, messaging, confirmation, logging, and rollout controls have to be designed together so staff can use the system without bypassing safeguards.

## How It Led to the Next Project

Telegram CRM Bridge completed the first iteration from clinical documentation to patient communication to staff operations. It shaped my current focus on safer healthcare automation patterns and recruiter-facing Clinical Informatics roles.

## Career Relevance

Telegram CRM Bridge demonstrates staff-facing workflow design, controlled automation, privacy-aware logging, TypeScript implementation, and live-environment rollout planning.
