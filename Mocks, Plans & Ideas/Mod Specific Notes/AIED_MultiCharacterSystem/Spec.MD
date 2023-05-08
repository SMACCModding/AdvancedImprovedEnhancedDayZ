Using the concept provided from the developer of server Bastion-RP create an offline system to store and reapply information registered within the `Player_Base` class.

Each compatible mod will have the opportunity to register any information to be stored and reloaded on the selection and loading of a character.

This mod should be treated as a "Hard Copy" of the variables within side the `Player_Base` class.

The primary difference between vanilla and this mod, is its ability to handle many `Player_Base`'s at the same time.
Storing the information within JSON files titled with the Steam 64 ID and containing JSON dat with auto generated "Character" IDs & required data for reach "Character".

In Phase 2 of this deployment, the creation, update, respawn & other sections of character creation should be expanded to provide a "full package".