# Dev Notes
## AP World docs
- [adding games to AP](https://github.com/ArchipelagoMW/Archipelago/blob/main/docs/adding%20games.md)

    Main things that need to be implemented for the game to work with Archipelago:
    - Handle secure and insecure websocket connections
    - Handle reconnecting
    - Change port to connect to
    - Send status updates

    Most of that should be handled by the AP client library below I think

- [APWorld API](https://github.com/ArchipelagoMW/Archipelago/blob/main/docs/world%20api.md)
- [APWorld Network proto](https://github.com/ArchipelagoMW/Archipelago/blob/main/docs/network%20protocol.md)

    I plan on doing some more research into this and probably writing up some basics on how the proto works
    - [Common client impl in python](https://github.com/ArchipelagoMW/Archipelago/blob/main/CommonClient.py)
    - [Proto implemented in C#](https://www.nuget.org/packages/Archipelago.MultiClient.Net)

        This looks like a library, so might be worth just using this if we end up wanting to do full AP impl
- [APWorld Spec](https://github.com/ArchipelagoMW/Archipelago/blob/main/docs/apworld%20specification.md)
- [APWorld Dev FAQ](https://github.com/ArchipelagoMW/Archipelago/blob/main/docs/apworld_dev_faq.md)
