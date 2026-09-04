# GG Finder

GG Finder is an MVP application that helps gamers find nearby players to
play with. Users can discover gamers within a 5 km radius, view their
profiles, check their availability, and send squad requests.

## 1. Project Overview

GG Finder is designed to make it easier for gamers to find suitable
players nearby. The MVP focuses on simple gamer discovery and squad
invitations.

The application allows users to:

- Browse gamers within 5 km.
- See each gamer’s username, game, rank/skill level, and online status.
- View a gamer’s full profile.
- Send a squad request to another gamer.

## 2. Target Users

GG Finder is intended for:

- Gamers looking for nearby players.
- Players who want to find teammates for their main game.
- Gamers who want to check another player’s rank, role, and availability
  before inviting them.

## 3. Problem

Gamers can have difficulty finding suitable teammates who play the same
game and are available to play.

GG Finder addresses this problem by providing a simple way to discover
nearby gamers and see useful information about them before sending a
squad request.

## 4. Main Features

### Browse Nearby Gamers

Users can browse gamers within a **5 km radius**.

Each gamer displays:

- Username
- Main game
- Rank/skill level
- Online status: **Available** or **Busy**

### View Gamer Profile

Users can tap a gamer to view their full profile, including:

- Username
- Main game
- Rank/skill level
- Preferred role/character
- Win rate (optional)
- Online status

### Send Squad Request

Users can send a squad request to another gamer to invite them to play
together.

A request can have one of the following statuses:

- Pending
- Accepted
- Rejected

## 5. Project Documentation

The detailed project documents are available below:

- [Project Charter](docs/PROJECT_CHARTER.md)
- [Requirements Specification](docs/REQUIREMENTS_SPECIFICATION.md)
- [Acceptance Criteria](docs/ACCEPTANCE_CRITERIA.md)
- [Database Design](docs/DATABASE_DESIGN.md)

## 6. MVP Scope

### Included

- Gamer profiles
- Nearby gamer discovery
- 5 km search radius
- Gamer availability status
- Gamer profile viewing
- Squad requests
- Database storage

### Not Included in the MVP

- In-app voice chat
- In-app messaging
- Game streaming
- Tournament management
- Payment features
- Advanced matchmaking

## Project Structure

``` text
GG-Finder/
│
├── docs/
│   ├── PROJECT_CHARTER.md
│   ├── REQUIREMENTS_SPECIFICATION.md
│   ├── ACCEPTANCE_CRITERIA.md
│   └── DATABASE_DESIGN.md
│
├── src/
│   └── ...
│
└── README.md
```

## Project Status

**Current status:** MVP planning and development

## Future Improvements

Possible future features include:

- In-app messaging
- Voice chat
- Friend system
- Multiple games per user
- Advanced matchmaking
- Game-specific rankings
- Notifications for squad requests
