# SKAdNetworks

This repository is maintained by Digital Turbine (DT) to support DT FairBid and DT Marketplace publishers integrating [Apple's SKAdNetwork](https://developer.apple.com/documentation/storekit/skadnetwork/configuring_the_participating_apps) for programmatic ad attribution. To participate in SKAdNetwork install validation, the publisher (source) app must include the ad network's ID in its `Info.plist`.

Programmatic ad buying uses the following framework for SKAdNetwork:
* DT's publishers are considered source apps under the SKAdNetwork specification
* DT's Demand Partners register and receive ad network IDs from Apple. Each Demand Partner running app install validation on DT Marketplace will have at least one SKAdNetwork ad network ID

DT's recommended list of SKAdNetwork ad network IDs is available in [JSON](https://raw.githubusercontent.com/DigitalTurbine/skadnetworks/master/docs/skadnetwork.json) and [XML](https://raw.githubusercontent.com/DigitalTurbine/skadnetworks/master/docs/skadnetwork.xml) formats. Feel free to either clone or fork this repository. Alternatively, you can directly download or `curl` the files containing the mentioned data.

Please do not create pull requests into this project as they will be ignored. The data will be updated periodically by DT's engineering team.
