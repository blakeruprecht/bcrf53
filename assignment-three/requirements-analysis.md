## Assignment 3 - Requirements Analysis
### Blake Rurpecht / bcrf53

### Step 1 - Identify Users of the System
- Students
- TAs
- Instructors


### Step 2 - Identify User Requirements, Step 3 - Relevant Data
#### Students
Log on to the system
- must have unique username, password
- access to service
- can't have multiple users logged in under the same name

Navigate to proper assignment
- can't access assignments that are closed, or haven't been opened yet
- choose proper assignment
- can't edit assignments
- requires username, current_assignment

Submit assignments before the deadline
- must have access to submission link
- be able to add different types of files or links
- must be able to add a message to the files
- require ability to upload files, links
- must be able to resubmit assignments without losing progress aka history tree
- requires username, current assignment, date/time, submission link, message, history tree

#### TAs
Log on to the system
- must have unique username, password
- access to service
- can't have multiple users logged in under the same name

Navigate to proper assignment
- can't access assignments they're not given permission for
- can view who has done the assignment/not done it
- requires data of which TA is accessing the assignment
- requires data of all possible assignments to access

Grade assignments
- must be able to see who posted, date/time of submission
- must be able to access the file/link
- can't change/edit files/links
- comment on assignments
- grade assignments
- requires username of TA, username of submitter, current assignement, submission link, history of edits, all comments, grade

#### Instructors
Log on to the system
- must have unique username, password
- access to service
- can't have multiple users logged in under the same name

Add/remove students, TAs, sections, courses
- see usernames of everybody added
- require data structure of how assignments are set up
- data model of all students, TAs, sections, courses
- data of who belongs to what i.e. the structure

Add/remove assignments
- give access to specific groups
- must be able to update assignment without deleting history
- determine proper submission types
- set/change deadlines
- see who has access
- see who has posted, see files/links
- change/update grades
- comment on assignments
- data of assignment name, text

### Step 4 - System Constraints and Requirements
- storage, memory, CPU, connectivity
- overall architecture of service
- can't be accessed by users without proper credentials




