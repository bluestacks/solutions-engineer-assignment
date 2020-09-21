# solutions-engineer-assignment

Game.tv (https://www.game.tv/) is, at its core, a mobile esports platform. While there are a lot of other esports platforms out there, what differentiates us from most others is the seamless tournament experience that we offer to our users - both players and hosts. This is, in a large part, because of the relationships we have with game developers and the game integrations we are able to set up.

The process of adding a new game usually starts with us sharing an API document with a game developer. The document may have some APIs that we will create and the developer will call, and some that the developer will create and we will call at certain times in the tournament workflow.

A typical tournament workflow looks like this:
1. A tournament host creates a tournament
2. Users register for the tournament.
3. At tournament time, brackets are created and players are told about their matches.
4. At match time, players are asked to play their game.
5. Once a match ends, its results are updated.
6. If a player wins their match, they advance in the tournament, and if they lose, they are out of the tournament.

The goal of the integration is that tournaments run seamlessly for both the players and tournament hosts so they don’t have to do anything manually.

We need you to prepare an API document to support such a workflow. It would help to have a flowchart and/or sequence diagram as well.

Bonus:
1. Design a system diagram for how this integration would work at scale
2. Prepare the API document using a tool like Swagger or Slate

