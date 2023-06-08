# Project Advisory Board Meeting Minutes

Date: 10th May 2023

Present: Nicholas Schwarz, Alec Sandy, Alex Hexemer, Stuart Campbell, Stuart Wilkins

Discussion on the candence of the PAB meetings.  The consensus was that we should meet twice a year.
The rough agenda for these meetings should be:
  * Updates and Report from TSC on progress and future plans
  * Facility Updates
  * Feedback to TSC on future needs/directions

There should be regular (ideally in person) workshop for the Bluesky Project as a whole.  These could follow the rough format and schedule of the EPICS Collaboration
Meetings. 

There should be a process for projects to become officially adopted into the Bluesky Project, and the PAB should be the body that ratifies this. 
- Ask the TSC to propose a set of criteria and process for a project to be adopted. 

The PAB members should raise the issue of what resources are (and going to be) committed to the project.  This can take the form of local developers
at the facilities or contract effort.  

The PAB will, as needed, charge the TSC to perform a review for existing projects to ensure that their direction is meeting the needs of the facilties and users. 
In areas of emerging technologies or areas that are of importance to the facilities, the PAB will charge the TSC to produce recommendations and plans to 
meet these needs.  

Some examples of areas discussed for reviews or "focus areas" where 
* GUIs - what is the future of BS Widgets?
* Queueserver 
* Tiled 
* Detector Integration
* HKL mapping
* How Robotics integrates in the future.

There is a consensus that it would be useful for the project to generate reference architectures and implementations for areas of common interest such as:
 * Examples of simple tasks such as "How do I interface to a motor record?"
 * Deployment at an instrument and what are good patterns for a representative instrument for some techniques.
 * HPC Interaction
 * Simple Bluesky system install
 * ...

What is a good name for the above ?  Best Practices, Knowledge Base, Community Practices, 
Encourage people to adopt common solutions where it makes sense
- Task the TSC to identify how to structure a project/community wide knowledge base which includes a library of best practices - and provide at least one examples. 

Discussion on what the future of bluesky integration for Detectors should look like.   
Discussion on the needs and requirements for UIs and Visualization. 
 * Experimental setup and control
 * Queue Management
 * Monitoring
 * Feedback and Easy visualizations (1D/2D plots) 
 * Plotting tools
 * Web Tools
 * Advanced Viz (Multi-Dimensional)
 * Jupyter Ecosystem
 * CLIs and GUIs 

There was discussion on how we associate data from different sources that might have very different timescales together into a coherent data set. 

There was discussion on the subject of reciprocal space mapping and tools.  This is an area that will probably need a dedicated planning effort and requirements. 

Are there some areas of utilities and tools that might be useful (e.g. unit conversion) - what is the threshold 
where these tools actually become part of the bluesky core.

## Tasks for the Next PAB Meeting

* Perform a review of Tiled and Queueserver - The PAB will write a formal charge. 

* Charge the TSC to come up with an approach on how bluesky will architect and develop GUIs.  This should include
  - a review of current capabilities and options
  - a recommendation and plan for the architecture and development approach for 
    - experiment control and setup
    - Monitoring / Feedback and Easy Visualization
    - an estimate of the required effort
    - recommendations for the architectures for local and web based solutions
  
  Essentially what is the 'bluesky' way for making GUIs for each different 'class' 
  What form would the output take ? 
  - Projects in bluesky 'core' 
  - Projects outside bluesky. 
  - Or even just entries in the knowledgebase etc...
  - The TSC and PAB should regularly checkin on the progress (every 2 months)
    - The 1st checkin should cover:
      - What is the current landscape? and what is the 'appetite' for a common development.  


Action the PAB chair to extend an invition to a member from HZB (BESSY-II) and a 2nd member from SLAC to sit on the PAB. 



