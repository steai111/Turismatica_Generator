# Turismatica Generator

Multi-agent operational system designed to extract monthly reservation data, transform it into daily movement files, convert them into canonical TXT submissions, and upload them to the Turismatica portal through automated workflow steps.

*Structured reporting pipeline built to turn fragmented booking data into compliant daily submissions for an external tourism reporting system.*

Turismatica Generator is a modular automation system created to handle a multi-step reporting workflow that would otherwise require repetitive manual work, format conversion, and portal interaction.

The project is built around a chained operational logic: data is extracted, reorganized, converted into the required reporting format, and then uploaded through an automated submission flow.  
Its value lies in transforming a fragmented compliance process into a structured, repeatable system.

## What it does

- Extracts monthly reservation data from a property management system
- Transforms reservation information into daily movement files
- Converts daily movement data into canonical TXT files required by the Turismatica portal
- Maps and inserts required coded values such as nationality codes and reporting fields
- Uploads the generated TXT files day by day through an automated portal interaction

## System structure

- **Extraction layer**  
  An automation process enters the management software and gathers monthly reservation data.

- **Movement generation layer**  
  A second agent restructures the extracted data into daily movement files.

- **Canonical conversion layer**  
  A third agent converts daily movement data into TXT files following the exact format required by the reporting portal.

- **Submission layer**  
  A final automation process uploads the generated TXT files into the Turismatica portal day by day.

## Why it matters

Tourism reporting workflows are often operationally fragile because they depend on manual extraction, file preparation, format compliance, and repetitive submission steps.  
This project exists to remove that friction by turning the entire process into a modular reporting pipeline.

Its value is not limited to automation speed: it creates consistency, reduces submission risk, and structures a compliance workflow that would otherwise remain error-prone and time-consuming.

## Multi-agent logic

Turismatica Generator is not built as a single monolithic script.  
Its architecture is based on a sequence of distinct agents, each handling a specific operational transformation:

- extract
- restructure
- convert
- submit

This separation makes the workflow easier to reason about, validate, and evolve over time.

## Status

Active internal project with functioning extraction, movement generation, canonical TXT conversion, and automated submission logic.  
The system is already operational as a real reporting workflow for structured tourism compliance tasks.

## Scope

This project is designed as a focused internal reporting and submission system for a specific hospitality compliance workflow.  
It is not intended as a generic SaaS reporting platform, but as a custom multi-agent architecture built around concrete data flows, canonical formatting requirements, and external portal submission needs.
