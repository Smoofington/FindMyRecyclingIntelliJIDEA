# FindMyRecycling

---

Design Document

Matthew Caudill
Matthew Dupont
Samuel Gehrlich
Christian Grothaus
Gabe Phan

## Introduction

Do you want to recycle, but don’t know where to take it? Have harsh chemicals that you can’t put in the trash? FindMyRecycling can help you:

-	Search for recycling centers near you
-	Save centers for easy access
-	Add centers near you

Users can interact with FindMyRecycling using either a set of RESTful service endpoints or a simple UI, or both.
## Storyboard

## Functional Requirements

1.	As a college student, I want to be able to find recycling centers near me that recycle glass, so that I will be able to recycle.  
**given**: A feed of facility data are available  
**when**: The user/service specifies the recyclable material as Glass  
**when**: The user/service specifies the location as 45236  
**then**: Blue Ash Recreational Center should be in the set of results  
2.	As a user, I want to be able to add a facility that is not already in the database  
**given**: A user is logged in, and internet connection is available  
**when**: The user fills out all required fields  
**then**: The data are saved to the database  
3.	As a college student, I want to be able to find recycling centers near me, **but** I want to see what materials   facilities can recycle near me, so that I will be able to recycle.  
**given**: A feed of facility data are available  
**when**: The user/service specifies the location as 45236  
**then**: A list of facilities in Blue Ash, OH  

## Class Diagram

### Class Diagram Description


## Scrum Roles  

UI - Samuel Gehrlich   
Business Logic and Persistence – Matthew Dupont, Christian Grothaus, Gabe Phan  
DevOps/Scrum Master – Matthew Caudill  

## Github  

## Weekly Meeting  
