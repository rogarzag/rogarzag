# Use Case Analysis — News Channel Program

## Objective

Identify the actors involved in a television news program, define the system's main use cases, and document how each actor participates in those use cases.

## 1. Identify the actors

| Actor | Type | Role and interactions |
|---|---|---|
| News producer | Primary | Plans segments, selects topics, assigns reporters, and coordinates with reporters during live coverage. |
| Reporter | Primary | Gathers information, conducts interviews, contributes stories to segments, and reports live. |
| Viewer | Secondary | Watches the broadcast and shares comments or feedback through social media. |
| Technical team | Secondary | Sets up, maintains, and troubleshoots the equipment used for the broadcast. |
| Advertiser | Secondary | Submits advertisements and agrees on their placement with the channel. |

## 2. Define the use cases

| Use case | Description |
|---|---|
| Create news segment | Select a topic, gather material, and assign a reporter to prepare a segment for broadcast. |
| Report news live | Deliver news, interviews, and updates on air as events unfold. |
| View program | Watch the live news broadcast. |
| Interact via social media | Comment on stories, share feedback, or participate in a discussion about the broadcast. |
| Manage broadcast equipment | Prepare and check cameras, microphones, and broadcast software, and resolve faults during production. |
| Provide advertisement | Submit an advertisement and coordinate when it will air during a commercial break. |

## 3. System boundary and diagram

The system boundary is **News channel program**. The five actors are placed outside the boundary and the six use cases inside it. Each use case appears once, with associations connecting the actors to the relevant use cases.

See the [use case diagram](./diagrams/use-case-diagram.svg) or [open the interactive Lucidchart version](https://lucid.app/lucidchart/7390e644-b2a4-4605-9f86-4769b1048ace/edit?viewport_loc=-1254%2C-430%2C3877%2C2181%2C0_0&invitationId=inv_35b30263-e9a3-411a-b19a-b6acc66fbd94).

## 4. Define the relationships

| Actor | Use case | Participation |
|---|---|---|
| News producer | Create news segment | Plans and develops the segment. |
| News producer | Report news live | Supports the broadcast by coordinating with reporters. |
| Reporter | Report news live | Delivers the story on air. |
| Reporter | Create news segment | Contributes interviews and information for the segment. |
| Viewer | View program | Watches the live broadcast. |
| Viewer | Interact via social media | Comments on the program and gives feedback. |
| Technical team | Manage broadcast equipment | Checks equipment and resolves technical problems. |
| Advertiser | Provide advertisement | Submits an ad and coordinates placement. |

## 5. Reflection

**What could make the roles difficult to distinguish?**  
Both the producer and the reporter contribute to a segment. The producer coordinates the work, while the reporter contributes the reporting.

**How does the diagram clarify the program?**  
The associations show which actors participate in each use case. The participation descriptions explain each person's contribution, especially where responsibilities overlap.

**How could the channel engage viewers?**  
It could invite viewers to submit questions during a segment and answer selected questions on air.
