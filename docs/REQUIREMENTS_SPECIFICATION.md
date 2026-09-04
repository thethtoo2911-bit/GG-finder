# GG Finder MVP - Requirements Specification

## 1. Introduction

GG Finder is an application that helps gamers discover nearby players and invite them to play together.

The MVP provides nearby gamer discovery, gamer profiles, availability information, and squad requests.

## 2. Functional Requirements

### FR-01: Gamer Profile

The system shall allow each gamer to have a profile containing:

- Username
- Main game
- Rank/skill level
- Preferred role/character
- Win rate (optional)
- Location
- Online status

### FR-02: Browse Nearby Gamers

The system shall display gamers located within a 5 km radius of the current user's location.

### FR-03: Display Gamer Information

For each nearby gamer, the system shall display:

- Username
- Main game
- Rank/skill level
- Online status

### FR-04: View Gamer Profile

The system shall allow a user to select a gamer from the nearby gamer list and view their full profile.

### FR-05: Display Profile Details

The full gamer profile shall display:

- Username
- Main game
- Rank/skill level
- Preferred role/character
- Online status
- Win rate when available

### FR-06: Send Squad Request

The system shall allow a user to send a squad request to another gamer.

### FR-07: Store Squad Request

The system shall store:

- Sender
- Receiver
- Request status
- Request creation date/time

### FR-08: Request Status

A squad request shall support the following statuses:

- Pending
- Accepted
- Rejected

### FR-09: Online Status

The system shall support two availability states:

- Available
- Busy

### FR-10: Location

The system shall store the user's approximate location so that nearby gamers can be identified.

### FR-11: Search Radius

The default nearby gamer search radius shall be 5 km.

### FR-12: Prevent Self-Requests

The system shall prevent a user from sending a squad request to their own account.

## 3. Non-Functional Requirements

### NFR-01: Usability

The application should have a simple interface that allows users to find a gamer and send a squad request with minimal steps.

### NFR-02: Performance

Nearby gamer results should be returned quickly under normal operating conditions.

### NFR-03: Security

User account information should be protected and passwords should not be stored as plain text.

### NFR-04: Reliability

The system should correctly store and retrieve gamer profiles and squad requests.

### NFR-05: Maintainability

The application should use a clear structure separating the user interface, application logic, and database.

### NFR-06: Scalability

The database should support additional users, games, and squad requests as the application grows.

## 4. User Stories

### User Story 1 - Find Nearby Gamers

**As a gamer,**

I want to see gamers near me,

**so that I can find someone nearby to play with.**

### User Story 2 - View Gamer Profile

**As a gamer,**

I want to view another gamer's profile,

**so that I can decide whether they are suitable for my squad.**

### User Story 3 - Send Squad Request

**As a gamer,**

I want to send a squad request,

**so that I can invite another gamer to play together.**

### User Story 4 - Check Availability

**As a gamer,**

I want to see whether another gamer is Available or Busy,

**so that I know whether they may be available to play.**
