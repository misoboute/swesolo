**Note**: *As the name suggests, these are random thoughts around the topic of artificial life, software based variants of it, ideas, and what we wish to develop here. So this is NOT a document in the conventional sense.*

## swesolod
The first element in the project is the _swesolod_ daemon. Only one instance of it can run on a single device. The swesolod daemon consists of multiple modules that run in parallel.

### Local ecosystem
It creates and maintains a local ecosystem on the device. For more info see [Local-Echosystem.md](Local-Echosystem.md).

### P2P module
To locate other swesolo ecosystems, especially those closest to it, each running instance of swesolod is also a p2p client using peer discovery protocols such as DHT, etc. It joins the swesolo p2p network which is the global swesolo ecosystem.

### Bioactivity monitor
This module regularly scans the local ecosystem for signs of biological activity and keeps logs of the activity. It can also trigger notifications on observing various ecosystemic events and activities.

### Visualisation service
Upon receiving a visualisation request from a client, this service creates a visual representation of the local ecosystem or a part of it. This can be used by an external GUI to visually monitor the ecosystem.
