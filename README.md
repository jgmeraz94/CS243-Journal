#h1 Moduel Eight Journal

#h3 Reflection:

The Gaming Room wanted to evolve _Draw It or Lose It_ from a single platform Android app into a scalable web based game accessible across desktop and mobile operating systems.
The main requirements includes:
  - Supporting multiple teams and player per game.
  - Enforcing unique names for all games, teams, and players.
  - Maintaining a single game service instance to coordinate all games.
  - Designing a secure, maintainable architecture for cross platform deployment.


#h3 What I Did Well:

I designed a clear, modular software architecture emphasizing object-oriented design principles such as encapsulation, inheritance, and abstraction. The Singleton pattern was effectively used to ensure that only one GameService instance manages all game logic and states. I also maintained consitency and scalability by introducing an Entity base class to unify common attributes like IDs and names.

#h3 Helpful Aspects of the Design Process:

Working through a software design document provided a structured approach to development. Defining requirements, constraints, and architecture early made it easier to visualize relationships between classes and ensure system scalability before any code was written. This process also clarified how client and server components interact within distributed systems, preparing for future implementations.

#h3 Potential Revisions and Improvements:

If I were to revise one section, I would expand the System Architecture View to include a more detailed visual topology diagram showing how clients, servers, and databases communicate across the network. This would make the architecture more transparent to future developers and improve documentation completeness.

#h3 Interpreting and Implementing User Needs:

I translated the user's needs into specific software features and design patterns:
- The Singleton GameService addressed the client's need for centralized control.
- Iteration and validation methods ensured unique naming for all entities.
- The use of object composition (games contain teams, teams contain players) mirrored real world game structure.


#h3 Approach to Software Design and Future Strategies:

My approach centered around:
- Analyzing requirements to define system boundaries and constraints.
- Modeling relationships with UML diagrams to clarify class responsibilities.
- Applying design patters like Singleton and inheritance for maintainability.
- Evaluating platforms (Linux, macOS, Windows, Mobile) for deployment suitability.

In future projects, I would continue using UML modeling, design patterns, and layered architecture. I would also integrate agile design iterations creating early prototypes, gathering used feedback, and refining designs incrementally to better align development outcomes with stakeholder expectations.

