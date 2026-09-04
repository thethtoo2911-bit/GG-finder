# GG Finder MVP - Acceptance Criteria

## 1. Browse Nearby Gamers

### AC-01: Display Nearby Gamers

**Given** the user is using GG Finder,

**When** the user opens the nearby gamers screen,

**Then** the system shall display gamers located within 5 km of the user's location.

### AC-02: Display Gamer Information

**Given** nearby gamers are displayed,

**When** the gamer list is shown,

**Then** each gamer shall display:

- Username
- Main game
- Rank/skill level
- Online status

### AC-03: 5 km Search Radius

**Given** the user's location is available,

**When** the system searches for nearby gamers,

**Then** gamers within 5 km shall be included,

**And** gamers outside the default 5 km radius shall not be included.

### AC-04: No Nearby Gamers

**Given** there are no gamers within 5 km,

**When** the user opens the nearby gamers screen,

**Then** the system shall show an appropriate message indicating that no nearby gamers were found.

## 2. View Gamer Profile

### AC-05: Open Gamer Profile

**Given** a gamer appears in the nearby gamer list,

**When** the user selects that gamer,

**Then** the system shall open the selected gamer's profile.

### AC-06: Display Full Profile

**Given** the gamer's profile is open,

**Then** the system shall display:

- Username
- Main game
- Rank/skill level
- Preferred role/character
- Online status

### AC-07: Display Optional Win Rate

**Given** a gamer has provided a win rate,

**When** the profile is displayed,

**Then** the system shall display the win rate.

**And** if no win rate is available, the profile shall still load normally.

## 3. Send Squad Request

### AC-08: Send Valid Request

**Given** the user is viewing another gamer's profile,

**When** the user selects "Send Squad Request",

**Then** the system shall create a squad request between the two users.

### AC-09: Initial Request Status

**Given** a valid squad request has been created,

**Then** its initial status shall be `Pending`.

### AC-10: Prevent Self-Request

**Given** the user is viewing their own account,

**When** they attempt to send a squad request to themselves,

**Then** the system shall prevent the request from being created.

### AC-11: Request Confirmation

**Given** a valid squad request has been sent,

**Then** the system shall inform the user that the request was successfully sent.

## 4. Gamer Availability

### AC-12: Available Status

**Given** a gamer is available to play,

**Then** their online status shall be displayed as `Available`.

### AC-13: Busy Status

**Given** a gamer is unavailable,

**Then** their online status shall be displayed as `Busy`.

## 5. Database

### AC-14: Store Gamer Profile

**Given** a gamer profile exists,

**Then** the system shall store the required profile information in the database.

### AC-15: Store Squad Request

**Given** a squad request is sent,

**Then** the database shall store the sender, receiver, status, and creation time.

### AC-16: Retrieve Data

**Given** valid gamer information exists in the database,

**When** the user requests the information,

**Then** the system shall retrieve and display the correct information.
