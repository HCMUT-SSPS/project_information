# HCMUT_SSPS - STUDENT SMART PRINTING SERVICE at HCMUT

## Requirements

### Domain Context

- Domain Context
- Relevant Stakeholders and their current needs
- Benefits of HCMUT_SPSS for each stakeholders

### FRs and NFRs

#### Functional Requirements

- See here.

#### Non-functional Requirements

- See here.

#### Use-case Diagram

- Image of use-case diagram here.
- Description

## System Modeling

### Activity Diagrams

### Sequence Diagrams

### Class Diagram

### Figma

## Architectural Design

### Architectual Diagram

#### Arc. Diagram

#### Arc. Description

### Component Diagram

#### Comp. Diagram

#### Comp. Description

## Project Information

HCMUT - SSPS Project Information

The university is intent to build a Student Smart Printing Service (HCMUT_SSPS) for serving students on its campuses to print their documents.
The system consists of some printers around the campuses. Each printer has an ID, brand/manufacturer name, printer model, short description, and the location (campus name, building name, and room number).

The system allows a student to print a document by uploading a document file onto the system, choosing a printer, and specifying the printing properties such as paper size, pages (of the file) to be printed, one-/double-sided, number of copies, etc. The permitted file types are limited and configured by the Student Printing Service Officer (SPSO). 

The system has to log the printing actions for all students, including student ID, printer ID, file name, printing start and end time, and number of pages for each page size.

The system allows the SPSO to view the printing history (log) of all students or a student for a time period (date to date) and for all or some printers. Of course, a student can also view his/her printing log for a time period together with a summary of the number of printed pages for each page size.

For each semester, the university gives each student a default number of A4-size pages for printing. Students are allowed to buy some more using the feature Buy Printing Pages of the system and pay the amount through some online payment system like the BKPay system of the university. The system only allows a student to print some number of pages when it does not exceed his/her account (page) balance. Note that, one A3 page is equivalent to two A4 pages. The SPSO has a feature to manage printers such as add/enable/disable a printer.

The SPSO also has a feature to manage other configurations of the system such as changing the default number of pages, the dates that the system will give the default number of pages to all students, the permitted file types accepted by the system.

The reports of the use of the printing system are generated automatically at the end of each month and each year and are stored in the system, and can be viewed by the SPSO anytime.

All users have to be authenticated by the HCMUT_SSO authentication service before using the system.

The system is provided through a web-based app and a mobile app.
