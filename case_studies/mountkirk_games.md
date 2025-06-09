# Mountkirk Games – Case Study

Mountkirk Games develops online, session-based multiplayer games, primarily for mobile platforms. Following a successful migration of their on-premises environments to Google Cloud, they are now expanding to other platforms. Their latest project is a retro-style first-person shooter (FPS) game that allows hundreds of simultaneous players to join geo-specific digital arenas from multiple platforms and locations. A real-time digital banner will display a global leaderboard showcasing top players across all active arenas. ￼ ￼

## 🏢 Company Overview
 - Business Model: Online, session-based multiplayer games.
 - Primary Platform: Mobile; expanding to other platforms.
 - Recent Development: Retro-style FPS game with global multiplayer support.

## 💡 Solution Concept

Mountkirk Games is building a new multiplayer game anticipated to be highly popular. They plan to: ￼ ￼
 - Deploy the game’s backend on Google Kubernetes Engine (GKE) for rapid scaling.
 - Utilize Google’s global load balancer to route players to the nearest regional game arenas.
 - Implement a multi-region Cloud Spanner cluster to maintain a synchronized global leaderboard. ￼ ￼

## 🖥️ Existing Technical Environment
 - Migration: Recently migrated five games to Google Cloud using lift-and-shift virtual machine migrations, with minor exceptions.
 - Project Structure: Each new game resides in an isolated Google Cloud project under a folder that maintains most permissions and network policies.
 - Legacy Games: Low-traffic legacy games have been consolidated into a single project.
 - Environments: Separate environments exist for development and testing. ￼

## 📈 Business Requirements
 - Support multiple gaming platforms.
 - Support multiple regions.
 - Enable rapid iteration of game features.
 - Minimize latency.
 - Optimize for dynamic scaling.
 - Utilize managed services and pooled resources.
 - Minimize costs. ￼ ￼

## 🛠️ Technical Requirements
 - Dynamically scale based on game activity.
 - Publish scoring data on a near real-time global leaderboard.
 - Store game activity logs in structured files for future analysis.
 - Use GPU processing to render graphics server-side for multi-platform support.
 - Support eventual migration of legacy games to this new platform. ￼

## 🗣️ Executive Statement

“Our last game was the first time we used Google Cloud, and it was a tremendous success. We were able to analyze player behavior and game telemetry in ways that we never could before. This success allowed us to bet on a full migration to the cloud and to start building all-new games using cloud-native design principles. Our new game is our most ambitious to date and will open up doors for us to support more gaming platforms beyond mobile. Latency is our top priority, although cost management is the next most important challenge. As with our first cloud-based game, we have grown to expect the cloud to enable advanced analytics capabilities so we can rapidly iterate on our deployments of bug fixes and new functionality.” ￼

## Reference
 - [mountkirk_games](https://services.google.com/fh/files/blogs/master_case_study_mountkirk_games.pdf)