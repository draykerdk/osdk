> A shared interface between devices and the Drayker network.

OSDK proposes a common way for devices to describe their capabilities and connect to Drayker. It concerns the boundary between physical equipment, network services and applications.

A public coupling interface would describe capabilities, authorisation and communication requirements so applications can work with compatible equipment.

Clear device contracts would help shared intelligence reach physical activities while making the limits of each connection visible.

## A practical example

A community project could discover a permitted sensor, understand the measurements it provides and use them through a documented interface. This is an illustration of the proposed design.

## Why this exists

OSDK is how things outside the network get to join it without each one being a special case.

The argument in full is on the [manifesto](https://drayker.org/manifesto/). The [economy page](https://drayker.org/economy/) states plainly what contributing here earns and what it does not.

## How it fits the whole

If [Dk Network](https://dknetwork.drayker.org) is the network, OSDK is how something that is not a computer gets onto it. The point of a universal coupler is that a device should not need a bespoke integration, a vendor SDK or a gateway product to participate. It needs one way in.

That one way in is also how the platform itself travels. The coupler is a super app in its own right: OSDK adapted to run as an app on other operating systems — multiplatform kernel coupling and virtualization — so the Drayker platform can be mounted inside other environments, including super apps (DKApps), instead of each one needing its own integration.

The rest of the ecosystem depends on this reaching far. The [Dk](https://dk.drayker.org) intelligence integrates what devices sense and do through its API; the network carries them as first-class participants; and because identity and consent are the entry conditions of everything in Drayker, a connected thing joins the same attributable system a person does. OSDK shares the same requirements as the other [Dk](https://dk.drayker.org) components: modular protocol, separation of layers, fault tolerance, and compatibility with [Living Cryptography](https://lc.drayker.org).

## State of this documentation

A single sentence of intent. There is no specification of what the coupler couples, which classes of device are in scope, or what "instant application to things" means concretely.

All proposed resolutions presented here are solutions to the requirements of Dk and the Drayker platform, and only those requirements are final. The definitive architecture is expected to come from research organized through [DFMP](https://dfmp.drayker.org).

The layer is referenced from the [ecosystem map](https://drayker.org/eco/) and connected in the [Dk](https://dk.drayker.org) page, but its specification is still a single sentence of intent — deciding how much of the coupler is architecture and how much is early idea is itself a useful piece of work.

## Contributing

Open an issue. Issues small enough for one person to finish carry the `open-function` label and appear on the board at [drayker.org](https://drayker.org/fn/).

Other languages: [Português](./README.PT.md) · [Español](./README.ES.md). Both currently behind this English version.

---

Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
