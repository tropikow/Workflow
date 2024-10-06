### WorkFlow for development software 
1. **Understand the requirements**
    - **Sub-steps:** Know the business model, Understand the project goals
    - **Tools:** Notion, Obsidian

2. **Model the Database**
    - **Sub-steps:** Create DB diagrams
    - **Tools:** Draw.io, DB diagram.io, Postgres.new

3. **Design the System**
    - **Sub-steps:** Define stack technologies (WebServer, Search, Balancer, etc.)
    - **Tools:** Eraser.io

4. **Design Interfaces**
    - **Sub-steps:** Apply UI/UX, Choose colors, images
    - **Tools:** Canva, Illustrator, Excalidraw, Figma

5. **Develop the software environment (pre-production)**
    - **Sub-steps:** Repository setup, Structure, Packs, Environment Variables

6. **Develop the software environment (production)**
    - **Sub-steps:** Set production variables

![diagram-workflow](./assets/Untitled%20Diagram-2.png)

### Apply the Twelve-Factor App
1. **Codebase**
    - **A codebase to support version control and multiple deployments**
2. **Dependencies**
    - **Explicitly declare and isolate dependencies**
3. **Configurations**
    - **Store configuration in the environment**
4. **Backing services**
    - **Treat backing services as pluggable resources**
5. **Build, deploy, run**
    - **Completely separate the build phase from the run phase**
6. **Processes**
    - **Run the application as one or more stateless processes**
7. **Port mapping**
    - **Publish services using port mapping**
8. **Concurrency**
    - **Scaling using the process model**
9. **Disposability**
    - **Make the system more robust by trying to achieve fast startups and safe terminations**
10. **Parity in development and production**
    - **Keep development, pre-production, and production as similar as possible**
11. **Histories**
    - **Treat histories as a stream of events**
12. **Process Management**
    - **Run management/administration tasks as one-time processes**

**If you want explain it, you can see documentation here: https://12factor.net/es/**