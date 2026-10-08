    Welcome to the **Vitalitree** organization on GitHub. Vitalitree is a modern, accessible health records and family care coordination platform built for SENG 455.  
                                                                                                                                                                       
    ---                                                                                                                                                                
                                                                                                                                                                       
    ## 🧭 Navigation & Work Tracking                                                                                                                                   
                                                                                                                                                                       
    All active planning, backlogs, and roadmaps are organized centrally across our organization:                                                                       
                                                                                                                                                                       
    * **[Organization Projects Board](https://github.com/orgs/SENG455-Vitalitree/projects)**                                                                           
      Track progress across sprints, backlogs, in-progress items, and reviews.                                                                                         
    * **[Active Issues (Vitalitree-App)](https://github.com/SENG455-Vitalitree/Vitalitree-App/issues)**                                                                
      View, filter, and report bug fixes, feature requests, and architectural tasks for the client application.                                                        
    * **[Milestones & Deliverables](https://github.com/SENG455-Vitalitree/Milestones)**                                                                                
      Documentation and project deliverables repository.                                                                                                               
                                                                                                                                                                       
    ---                                                                                                                                                                
                                                                                                                                                                       
    ## 🏷️ Issue Categorization & Standards                                                                                                                             
                                                                                                                                                                       
    To maintain clean project hygiene and clear ownership across teams, issues adhere to the following standards:                                                      
                                                                                                                                                                       
    ### 1. Title Formatting                                                                                                                                            
    Issues must follow the `[VDEV-XXX]` ticket naming convention:                                                                                                      
                                                                                                                                                                       
  [VDEV-XXX] [Area/Category] Brief, descriptive title                                                                                                                  
                                                                                                                                                                       
    *Examples:*                                                                                                                                                        
    * `[VDEV-005] [Architecture] Solidify Base App Shell, Navigation & Theme Provider`                                                                                 
    * `[VDEV-009] [Platform/iOS] Native iOS Build, Simulator & Scene Lifecycle Configuration`                                                                          
                                                                                                                                                                       
    ---                                                                                                                                                                
                                                                                                                                                                       
    ### 2. Label Taxonomy                                                                                                                                              
                                                                                                                                                                       
    Each issue must be tagged with at least one **Area** label and one **Type** label:                                                                                 
                                                                                                                                                                       
    #### **Area Labels (`area:*`)**                                                                                                                                    
    * `area: frontend` — Client-side interface, UI components, navigation, and mobile layouts.                                                                         
    * `area: backend` — Server logic, API routes, authentication, and business rules.                                                                                  
    * `area: database` — SQL scripts, migrations, schema design, and data models.                                                                                      
    * `area: devops-infra` — GitHub Actions, CI/CD, build tooling, Docker, and deployment.                                                                             
                                                                                                                                                                       
    #### **Type Labels (`type:*`)**                                                                                                                                    
    * `type: feature` — Direct user-facing additions or functional requirements.                                                                                       
    * `type: bugfix` — Resolving defects or unintended behavior.                                                                                                       
    * `type: architecture` — Foundational structure, directory hierarchy, and system design.                                                                           
    * `type: chore` — Tooling updates, dependency bumps, linting, and boilerplate maintenance.
    * `type: documentation` — Developer documentation, guides, and specifications.
    * `type: spike` — Time-boxed investigative research or technical prototyping.
  
    ---
  
    ## 👕 Effort & Story Estimation (Coming Soon)
  
    In future sprint planning cycles, issues will include **T-Shirt Size Estimation** labels to estimate effort and scope before sprint commitment:
  
    | Size | Effort / Scope | Typical Duration |
    | :--- | :--- | :--- |
    | **XS** | Trivial fix, copy change, or minor config adjustment | < 1–2 hours |
    | **S** | Small, self-contained feature, bug fix, or utility component | Half-day |
    | **M** | Standard feature, multi-screen UI flow, or single API endpoint | 1–2 days |
    | **L** | Substantial system feature, database migration, or cross-cutting module | 3–5 days |
    | **XL** | Large architectural epic requiring decomp into smaller subtasks | Full sprint+ |
  
    ---
  
    ## 🤝 Contribution Workflow
  
    1. Pick an issue from the [Projects Board](https://github.com/orgs/SENG455-Vitalitree/projects) or assign it to yourself.
    2. Create a branch linked to the ticket: `git checkout -b feature/vdev-xxx-short-description`.
    3. Submit a Pull Request targeting `main` with a reference to the issue (e.g., `Closes #XXX`).
