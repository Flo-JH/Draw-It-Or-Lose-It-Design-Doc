# Draw-It-Or-Lose-It-Design-Doc– Software Design Document
Client and Software Requirements
The Gaming Room wanted to expand their game, Draw It or Lose It, beyond Android to a web-based, multi-platform environment. The software needed to support unique identifiers for games, teams, and players while ensuring that only one instance of the game service ran in memory. It also had to be scalable, secure, and compatible with different operating systems.

What I Did Well
I structured the design using a microservices approach with containerization, making it easier to scale and maintain. Security was also a strong focus, with OAuth 2.0, JWT authentication, and data encryption to protect user information.

Helpful Aspects of the Design Document
Writing the design document helped organize the system architecture before coding. It gave a clear view of how each component interacts and ensured that all requirements were met early, reducing potential issues during development.

Revisions and Improvements
If I could revise one part, I’d expand on the distributed systems and networks section. Adding more details on how services communicate and handle failures, along with diagrams, would improve clarity.

Interpreting User Needs
The design focused on scalability, security, and cross-platform compatibility, ensuring the game could handle high traffic while protecting user data. Considering user needs is critical since it leads to a better experience and makes the application more practical and efficient.

Approach to Software Design
I started by understanding the client’s requirements, then chose a cloud-based architecture with modular components for flexibility and scalability. In the future, I’d keep using modular designs while incorporating more user feedback early in the process.
