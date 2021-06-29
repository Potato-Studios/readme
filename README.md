# Structure
We use plugins as a building block for our challenges. We add as many plugins as we need to a server, and all plugins must listen to the chat message `toggle` (do not cancel the event afterwards, this may stop other plugins from being activated).
