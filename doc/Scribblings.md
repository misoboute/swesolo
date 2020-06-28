**Note**: *As the name suggests, these are random thoughts around the topic of artificial life, software based variants of it, ideas, and what we wish to develop here. So this is NOT a document in the conventional sense.*

The first element in this project is the _swesolo_ daemon. Only one instance of it can run on a single devices. It creates and maintains a local ecosystem on the device. To locate other swesolo ecosystems, especially those closest to it, each running instance of swesolod is also a p2p client using peer discovery protocols such as DHT, Kadmelia, etc.

