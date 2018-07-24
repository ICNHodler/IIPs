---
iip: 1
title: IIP Purpose and Guidelines
status: Draft
category: Community
author: JesusThatsGreat
created: 2018-06-24
---

## What is an IIP?

IIP stands for ICONOMI Improvement Proposal. An IIP describes an idea about how to improve ICONOMI (the digital assets management platform). An IIP should follow a standard format which helps to structure the idea and ensure a minimum level of thought / effort has been put in to it.

## IIP Motivation

The ICONOMI community is a small, loyal bunch who've seen great change in how the community and community relations are maintained / operated. Rocket.chat is currently the primary, official method of communication among Iconomi users and supporters however because it's a messaging platform, it means ideas tend to get buried in real time discussion. A messaging platform also doesn't lend itself to lengthly debate around specific issues / visions due to the constant 'noise'.

IIPs encourage community members to document their ideas at length and in their own time without fear of having their idea buried as soon as it's published. Because IIPs are maintained as text files in a versioned repository, their revision history is the historical record of the idea proposal and can be referenced easily in discussions either on github, on Rocket.Chat, on reddit or any other place where the ICONOMI community gathers. 

## IIP Categories

There are four categories of IIP:
- **Community**: Ideas on how to strengthen community relations or how to help expand / organise the community.
- **Marketing**: Ideas on how to improve marketing of anything ICONOMI related - be it DAAs, the ICN token, jobs / roles that need filled etc.. 
- **Platform**: Ideas on how to improve the ICONOMI platform itself which may include new features, new data, UX improvements etc..   
- **Operations**: Ideas on how to improve productivity, efficiency, reduce costs etc...

## IIP Status

- **Draft** - IIP that is open for consideration.
- **In Progress** - confirmed as work in progress by ICONOMI or the community (if it's a community related idea that can be implemented by a community member).
- **Under Consideration** - confirmed by ICONOMI as something that *may* happen in the future.
- **Implemented** - confirmed as implemented by ICONOMI or by the community (if it's a community related idea that can be implemented by a community member). 
- **Rejected** - confirmed by ICONOMI as something that will not happen. 
- **Inactive** - no longer relevant or superceded by another IIP.

## What belongs in an IIP?

Each IIP should have the following parts:

- **Preamble** - RFC 822 style headers containing metadata about the IIP, including the IIP number, a short descriptive title (limited to a maximum of 44 characters), and the author name.
- **Description** - "If you can't explain it simply, you don't understand it well enough." Provide a simplified and layman-accessible explanation of the IIP.
- **Motivation** - The motivation should clearly explain why the existing system is inadequate to address the problem that the IIP solves.
- **Research** - Showing test cases, examples or research of how and why the idea has worked before (in other projects or other walks of life) will help strengthen the case for the IIP as will doing any community research to guage whether the idea has support.  

## IIP Formats and Templates
IIPs should be written in [markdown] format. Image files should be hosted externally e.g. using imgur.com and referenced that way.

## IIP Header Preamble

Each IIP must begin with an RFC 822 style header preamble, preceded and followed by three hyphens (`---`). The headers must appear in the following order. Headers marked with "*" are optional and are described below. All other headers are required.

` iip:` <IIP number> (this is determined by the IIP editor)

` title:` <IIP title> 

` author:` <a list of the author's or authors' name(s) and/or username(s).>

` status:` <Draft | In Progress | Under Consideration | Implemented | Rejected | Inactive>

` category:` <Community | Marketing | Platform | Operations>

` created:` <date created on, in ISO 8601 (yyyy-mm-dd) format>

## IIP Editors

The current IIP editors are

` * JesusThatsGreat (@jesusthatsgreat)`

## IIP Editor Responsibilities

For each new IIP that comes in, an editor does the following:

- Read the IIP to check if it is ready: sound and complete. The ideas must be approved regardless of whether the editor thinks they're ~stupid~ lacking in quality.
- The title should accurately describe the content.
- Check the IIP for language (spelling, grammar, sentence structure, etc.), markup ([Github flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)), code style

If the IIP isn't ready, the editor will send it back to the author for revision, with specific instructions.

Once the IIP is ready for the repository, the IIP editor will:

- Assign an IIP number (generally the PR number or, if preferred by the author, the Issue # if there was discussion in the Issues section of this repository about this IIP).

- Merge the corresponding pull request

The IIP editors monitor IIP changes, and may occassionally correct any structure, grammar, spelling, or markup mistakes we see.

The editors don't pass judgment on IIPs. We merely do the administrative & editorial part.

## Hat-tip

This document and concept in general was derived heavily from Ethereum's EIP-1 which was in turn derived from Bitcoin's BIP-0001 which in turn was derived from Python's PEP-0001. In many places text was simply copied and modified. We don't believe in reinventing wheels.
