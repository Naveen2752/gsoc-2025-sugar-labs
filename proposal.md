# GSoC 2025 Proposal - Sugar Labs

**Title**: Git Backend for Turtle Blocks and Music Blocks

## Personal Information:
- **Name**: Naveen N  
- **Email**: [naveennarasimha27@gmail.com](mailto:naveennarasimha27@gmail.com)  
- **GitHub**: [https://github.com/Naveen2752](https://github.com/Naveen2752)  
- **University**: AMC College, Bengaluru  
- **Course**: MCA (Master of Computer Applications)  

---

## Synopsis:
This project focuses on integrating Git-based version control into Sugar Labs' educational tools: Turtle Blocks and Music Blocks. These platforms allow learners to explore music and programming concepts through block-based interfaces.

Currently, users can publish their projects to a server called "Planet," but there is no support for versioning, collaboration, or project history.

The proposal aims to build a backend system powered by Git that supports project history, forks, checkouts, and other core Git features. This system will be integrated with the frontend so young learners can access version control through an intuitive and simplified interface. The project seeks to empower students with real-world tools and promote collaborative and reflective learning.

---

## Benefits to the Community:
- Promotes collaborative learning by enabling users to fork and build upon each other’s projects.
- Introduces Git concepts in a beginner-friendly way, fostering early familiarity with industry tools.
- Enhances project tracking by allowing users to view project history, revert changes, and maintain personal portfolios.
- Encourages experimentation by providing a safe way to explore and roll back.
- Improves existing publishing features by integrating real version control, increasing overall project robustness.

---

## Deliverables:
- **Week 1–4**: Research and design the Git backend structure and APIs  
- **Week 5–7**: Implement core Git functionalities (`init`, `commit`, `push`, `pull`, `history`, `checkout`)  
- **Week 8–10**: Develop frontend integration for Turtle Blocks and Music Blocks (project history, version control buttons, etc.)  
- **Week 11–13**: Add support for forking and collaborative workflows  
- **Week 14–16**: Final testing, bug fixes, documentation, and user guide  

---

## Time Commitment Note:
I have my semester exams scheduled during May or June. During the exam period, I will still dedicate focused time to the project with a reduced work schedule (2 PM – 5 PM and 8 PM – 10 PM IST). After the exams, I will be able to commit full-time hours to the project.

---

## Timeline:

### Community Bonding (Before May 20):
- Deep dive into the existing Turtle Blocks and Music Blocks codebase  
- Connect with mentors and community  
- Finalize design and tools for backend  
- Build and test small example projects to explore current architecture  
- **Working hours**: 2 PM – 5 PM and 8 PM – 10 PM IST (reduced schedule)

### Phase 1 (May 20 - June 17):
- Set up Git backend server  
- Expose Git APIs to handle `init`, `commit`, and retrieve project versions  
- Initial UI integration to show commit history  
- **Working hours**: 2 PM – 5 PM and 8 PM – 10 PM IST (due to exams)

### Phase 2 (June 17 - July 15):
- Integrate Git features with the frontend (project history, version view)  
- Implement UI for versioning operations  
- **Working hours**: Full-time post exams

### Phase 3 (July 15 - August 12):
- Add forking and branching functionality  
- Enable collaborative edits and conflict handling  
- Write documentation, record demos, and finalize code

---

## Technical Approach:
- **Git Backend**: Use Node.js or Python to interact with Git via CLI or libraries like `isomorphic-git` or `GitPython`  
- **API Layer**: Create RESTful APIs to abstract Git operations (`init`, `commit`, `pull`, `push`, `clone`, `log`)  
- **Database**: Minimal use; Git will serve as the data store for project history  
- **Frontend Integration**: JavaScript modules will expose version control buttons and project history views  
- **UI/UX Design**: Simple and educational UI to allow learners to explore version control without complexity  
- **Testing**: Manual and automated tests to ensure stability and correctness  
- **Mockup Plan**: (Optional) Design a visual representation of the version control history with icons and labels

---

## About Me:
I am currently pursuing my MCA at AMC College, Bengaluru. I have worked on several full-stack projects including web apps and Android applications. I have a solid understanding of Git, JavaScript, and backend technologies like Node.js and Express. My academic and personal projects (e.g., a Git-integrated portfolio site and a collaborative To-Do app) show my ability to understand, implement, and document complex backend systems.

- **GitHub**: [https://github.com/Naveen2752](https://github.com/Naveen2752)  
- **Portfolio Projects**: Spotify Clone, To-Do App, Simon Says Game, Hear My Voice (Android app with TTS and translation)

---

## Why Me?
My technical skills, paired with my passion for open-source education, make me a strong candidate. I enjoy making technical tools simple and accessible—a core value of Sugar Labs. I am experienced with Git and backend development, and I have the patience and persistence needed to complete long-term open-source projects. I look forward to learning from mentors and giving back to the community.

---

## Future Work (Optional):
- Integrate social features like commenting on versions  
- Expand Git UI to support diffs and merge conflict resolution visually  
- Use GitHub/GitLab as a remote option for advanced users  

---

## References:
- [Sugar Labs Git Integration Draft](https://drive.google.com/file/d/15G0vtr-1JyzCorwmgjvXE-37vwZMLgJD/view?usp=sharing)  
- [Turtle Blocks](https://turtle.sugarlabs.org/)  
- [Music Blocks](https://musicblocks.sugarlabs.org/)  
