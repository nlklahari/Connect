Original App Design Project
===

# Connect

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Enter profile into database for an event/organization and randomly be paired with someone to connect with.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Social Networking
- **Mobile:** Mobile experience is efficient and can connect to texting apps for virtual communication and direct to gps for meeting spots.
- **Story:** Users can form connections and grow their network. The app provides a great way to get to know some people before an event to improve confidence.
- **Market:** Colleges, Organizations, Classes, Events are all places where people are looking to network.
- **Habit:** Usage depends on how involved the user is in social activities/events
- **Scope:** Basic version includes features such as registering an event/org/etc and individual users can create profiles and add events/orgs to their profile to be matched with other people in the dataset. Future version will have advanced features such as filtering to set preferences for people to be matched with and have a home page with activity/announcements from the event.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Users can create a new account.
* Users can login.
* Users can register a new event/org/school.
* Users can join events/organizations.
* Users can view their random match who is a registered profile attending the same event/organization.
* Users can search for events/organizations/schools.
* Organizers can verify members who joined to be attending the event/org.
* Users can connect to a messaging app (SMS, Messenger) once match has been made.
* Users can request a match.
* Users can view all orgs/events that they are part of.
* Users can view all orgs/events that they organized.

**Optional Nice-to-have Stories**

* Users can choose preferences before getting matched.
* Users can view home page with event/org photos.
* Users can post photos to home page.
* User can post text content to home page.
* Users can view home page with text content from event/org.
* Users get a notification when a match is made.
* Users get notified when new members join.
* Users can set profile pictures.
* Users can search for nearby events with location.
* Users can pick a meeting spot on map and get directions.

### 2. Screen Archetypes

* Login Screen
   * Users can login.
* User Registration Screen
   * Users can create a new account.
* Organizer Registration Screen
    * Users can register a new event/org/school.
* Org/Event Screen
    * Users can join events/organizations.
    * Users can request a match.
* Search
    * Users can search for events/organizations/schools.
* Approve Screen
    * Organizers can verify members who joined to be attending the event/org.
* Match Screen
    * Users can view their random match who is a registered profile attending the same event/organization.
    * Users can connect to a messaging app (SMS, Messenger) once match has been made.
* Profile Screen
    * Users can view all orgs/events that they are part of.
    * Users can view all orgs/events that they organized.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Search
* Profile
* Match Screen

**Flow Navigation** (Screen to Screen)

* Login Screen
   * Search
   * Organizer Registration Screen
* User Registration Screen
   * Search
   * Organizer Registration Screen
* Search
    * Org/Event Screen
* Profile
    * Approve Screen

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
