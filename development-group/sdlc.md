# Baltimore County Software Development Lifecycle
The purpose of this document is to the Software Development Life Cyle standards for Development at Baltimore County

<!--## Iterative Approach
We want to use a sdlc that delivers working software on a consistent basis. Each iteration should contain a set of features that corespond with the alloted time for that weeks development.

## Requirements
Requirements should be stored as Features in TFS. Each feature should include a list of tasks that contain estimates for that task. 

When breaking down tasks, summarize a task so that the minimum estimate is 1 hour. A hour hour estimate entails what you think would take 30 minutes worth of work.-->

## Development
This section of the document focuses on what the lifecyle means to a person on the development team.

### Assumptions
* Development work can contain writing code, configuring applications, writing reports
* A developer is any resource that works on items listed in the first bullet point

![Development Diagram](https://i-msdn.sec.s-msft.com/en-in/hh126360.1_OPT(en-us,MSDN.10).gif)

### Requirements
Developers are typically not involved in this step the owner of the requirements should hand these off to architects and senior level developers. A developer **cannot** begin development without requirements.

### Design
Architects and senior level development resources design an approach for the given requirements. The architecture will be documented in a standard format, and distributed to the team.

### Write Code (Development Work)
Developers do work using the provided architecture to fufill the requirements.

**Guidelines**
* Use source control when applicable, checking in early and often
* Follow standards based on architecures (tools, code conventions, etc.)
* Another resource must be involved
* Be consistent

### Compile and Test
Products are tested, defects are reported, tracked, fixed and retested, until the product reaches the desired quality.

**Guidelines**
* Automate when possible
* Tests are documented so they can be repeated
* Code cannot be released before all tests passed

### Manage and Review
Senior level developer(s) to review requirements against the product to ensure the given requirements are met.

### Staged Testing
Product will be pushed to a staging environment for user acceptance. Release cannot be scheduled without documented user acceptance of a system.

### Release
Product is ready for release.

**Guidelines**
1. Schedule Change Control 
2. Ensure proper communication to interested parties prior to release (release datetime, downtime, etc)
3. Provide release notes for the system

----------
**References**
* [Tutorialspoint - SDLC Overview](https://www.tutorialspoint.com/sdlc/sdlc_overview.htm)
* [How Microsoft Helps Software Development Succeed](https://msdn.microsoft.com/en-in/hh126360.aspx)