# ESPresense

ESPresense turns inexpensive ESP32 boards into a home-wide indoor positioning system. Mount a few nodes around the house, run the companion service, and Home Assistant can tell which room a phone, watch, or BLE tag is in — accurately enough for per-room automation, fall response, or elopement alerts. Open-source firmware, open-source server, open data.

### Who it's for
- **Homeowners** who want presence-based automation that actually works room-to-room.
- **Home Assistant users** looking to replace flaky GPS/BLE-proximity hacks with real indoor positions.
- **Makers and tinkerers** building on top — custom enclosures, new device classes, accuracy research.

### Flagship repos
- **[ESPresense](https://github.com/ESPresense/ESPresense)** — ESP32 firmware. Flash it on a node, point it at MQTT, and you have a BLE/iBeacon scanner that publishes to Home Assistant's `mqtt_room` integration.
- **[ESPresense-companion](https://github.com/ESPresense/ESPresense-companion)** — Home Assistant add-on / Docker container that fuses readings from multiple nodes into real `(x, y, z)` positions on your floorplan.
- **[ESPresense.com](https://github.com/ESPresense/ESPresense.com)** — source for the [docs site](https://espresense.com/). Setup guides, supported hardware, calibration walkthroughs.
- **[Floorplan-Creator](https://github.com/ESPresense/Floorplan-Creator)** — browser tool that turns a floorplan image into the YAML the companion expects. Skip it and write the YAML by hand if you prefer.

### Need help?
1. **[GitHub Discussions](https://github.com/ESPresense/ESPresense/discussions)** — first stop for setup questions, calibration, "is X supported?", and anything someone else might ask later. Search before posting.
2. **[Discord](https://discord.gg/jbqmn7V6n6)** — faster turnaround, real-time troubleshooting, hardware swaps.
3. **[File an issue](https://github.com/ESPresense/ESPresense/issues)** — once it's confirmed a bug or a concrete feature gap. Include firmware version, board, and what you tried.

### Contributing
PRs welcome across every flagship repo. Start with [`CONTRIBUTING.md`](https://github.com/ESPresense/ESPresense/blob/main/CONTRIBUTING.md) on the firmware repo, then say hi on [Discord](https://discord.gg/jbqmn7V6n6) so we know what you're working on.

### Star History
[![Star History Chart](https://api.star-history.com/svg?repos=ESPresense/ESPresense,ESPresense/ESPresense-companion&type=Date)](https://star-history.com/#ESPresense/ESPresense&ESPresense/ESPresense-companion&Date)
