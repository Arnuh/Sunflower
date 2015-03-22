![Sunflower](https://i.imgur.com/RMeFNAq.png)
#Sunflower
Sunflower intends to be the light for Minecraft server implementations.
It is a clean room, API and server agnostic, open source, free Minecraft runtime server bridge.

Instead of hard coding APIs or even servers, Sunflower acts as a mediator between an implementation of a Minecraft server and an API using mappings.

The mappings will translate methods to and from Sunflower with the API, or even APIs, and a second set of mappings will translate methods to and from Sunflower to a single server implementation.

Note: Sunflower is currently **not** in the development stage, and is in planning. We hope to see the community support us and expand on it more than we could ever dream.

Another note: Sunflower is not competing with Sponge or other APIs. Using a Sponge mapping, you would be able to use SpongeAPI and Bukkit together. However, Sunflower is technically competing with server implementations, as servers will have to be adapted for Sunflower as the idea stands, although we have plans to do runtime tricks to use Sunflower on the vanilla server or servers implementations not made for Sunflower.
