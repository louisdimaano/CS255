## CS-255: System Analysis and Design — DriverPass

## Overview

A complete system analysis and design project for a simulated client, DriverPass, a driver training company looking to reduce DMV test failure rates through better preparation tools. This project covers the full lifecycle from requirements gathering through system design, producing artifacts a development team could build from directly.

## The Problem It Solves

Many students fail their DMV driving test due to inadequate preparation. DriverPass needed a cloud-based system where students could take online practice tests, work through course material, and book on-the-road driving lessons with assigned instructors. The system also needed to stay synchronized with DMV updates so practice material never became outdated.

## System Requirements

Cloud-based, device-agnostic access for all user types
Online practice tests and course material delivery
Lesson scheduling and instructor assignment
Role-based access for customers, staff, and administrators
Activity logging and reporting for accountability -- tracking who created, modified, or canceled reservations
Automatic DMV sync to keep practice content current
Third-party payment processor integration

## My Approach

Requirements were gathered from a client interview transcript and translated into a formal Business Requirements Document. Every design decision traced back to a specific client request rather than assumptions. The system was then designed using UML diagrams that captured both process flow and object structure, since each perspective reveals things the other doesn't.

Key insight from the requirements phase: when the client said he needed to know who made, changed, or canceled a reservation, the underlying need was accountability -- so activity logging and reporting were designed in explicitly rather than left as an afterthought.

## Technical Highlights

UML Diagrams -- use case, activity, sequence, and class diagrams covering both process and structural perspectives
Role-based access control -- distinct permissions for customers, staff, and owner
Appointment class design -- structured to support scheduling, instructor assignment, and full audit trail
External system integration -- DMV sync and payment processor connections modeled in system design
Cloud architecture -- designed for device-agnostic access and scalability

## Technologies & Concepts

UML · Use Case Diagrams · Activity Diagrams · Sequence Diagrams · Class Diagrams · Requirements Analysis · Business Requirements Documentation · System Design · Cloud Architecture · Role-Based Access Control

## What I Learned

Requirements gathering is the foundation everything else sits on -- catching a misunderstanding early is far cheaper than finding it after the system is built
Reading between the lines of client requests to identify the underlying need produces better designs than taking requests literally
Using multiple model types -- process models and object models -- reveals different aspects of the same system
External system integrations deserve the same design attention as human user interactions

## Artifacts

Project One -- Business Requirements Document capturing client needs, system requirements, and constraints from stakeholder interview
Project Two -- System Design Document including full UML diagram suite and architectural specifications ready for development handoff
