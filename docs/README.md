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

If [Dk Network](https://dknetwork.drayker.org) is the network, OSDK is how something that is not a computer gets onto it. The universal coupler connects every device to the network and gives things immediate application. The point of a universal coupler is that a device should not need a bespoke integration, a vendor SDK or a gateway product to participate. It needs one way in.

That one way in is also how the platform itself travels. The coupler is a super app in its own right: OSDK adapted to run as an app on other operating systems — multiplatform kernel coupling and virtualization — so the Drayker platform can be mounted inside other environments, including super apps (DkApps), instead of each one needing its own integration.

The coupler injects and runs the [BSDK](https://bsdk.drayker.org) base structure in a compatible system until the structure gathers its compatibility modules and scans the available resources. It can be a normal program for an existing operating system or a program at firmware level. It can delimit a space shaped by its pre-modules, as a standard application (a DkApp), or serve as the installer of a native OSDK; both carry pre-modules for a specific purpose and general-purpose base modules, and different combinations can be designed for different purposes.

The rest of the ecosystem depends on this reaching far. The [Dk](https://dk.drayker.org) intelligence integrates what devices sense and do through its API; the network carries them as first-class participants; and because identity and consent are the entry conditions of everything in Drayker, a connected thing joins the same attributable system a person does. OSDK shares the same requirements as the other [Dk](https://dk.drayker.org) components: modular protocol, separation of layers, fault tolerance, and compatibility with [Living Cryptography](https://lc.drayker.org).

## How it is meant to work

Its first form is a virtual machine for the DFM language, coupled through an interpreter or a compiler: a program that couples the parent function of BSDK directly to the machine language of a specific device and integrates an adaptive kernel through which the machine's resources communicate with the fundamental modules. Integrators complement it: programs that translate and adapt existing platforms and algorithms, including models already trained, to the DFM architecture, optimize them and evaluate them on the test network.

When OSDK is installed on a machine, Dk starts by recognizing the device and its hardware and optimizing its connection to the network; then the use of the device is defined and the modules for that use are loaded. The base is light enough for almost any device, including special-purpose chips that accelerate the network. Like every platform integrated with Dk, it evolves and adapts while it runs, making the most of whatever hardware it is on, within the permissions and the use. Dk can manage distributed memory and processing from a minimum of three points, and a device can be configured to serve as one of them.

A native OSDK runs the applications built within the system. Programs from outside the network, such as a browser, run inside a specific kind of virtual machine on top of OSDK. These virtual machines are entirely external to the Dk network: they use only the resources of the machines where the person or entity is authorized, on an external network connected to the classic internet, and cannot use the network's resources. An entity can also host sites on the classic web from its own servers this way.

OSDK is meant to be the base of the equipment Drayker and its partners produce, such as identification devices and the computers given to volunteers, of public computers where each person authenticates and uses the platform securely, and of support servers where network and computing resources are scarce. In its final version, a newly built device — a robot, for instance — can be inspected through OSDK: everything that can be controlled is recognized, and each control is tested to abstract its function and organize possible uses. A member who connects their home installs OSDK and the connection app on their devices and takes control of them and of their data; what Dk learns from that environment follows the same rule as any personal context: raw context stays at its origin, and only what the person authorizes rises to the network ([ethical code](https://dk.drayker.org/ethos)).

## State of this documentation

This page describes the purpose of the coupler and its two forms, a practical example, how it fits the whole and the requirements it shares with the other Dk components, and, from the founding design notes, its first form as a virtual machine for the DFM language, its start-up on a device, the virtual machines that keep external programs apart from the network and the equipment it is meant to be the base of. These are design descriptions, not a specification. No specification is published yet of the interface between the coupler and a device, of how a device describes its capabilities, authorisation and communication requirements, or of which classes of device a first version supports. There is no implementation: no released device adapter and no published OS.

All proposed resolutions presented here are solutions to the requirements of Dk and the Drayker platform, and only those requirements are final. The definitive architecture is expected to come from research organized through [DFMP](https://dfmp.drayker.org).

The layer is referenced from the [ecosystem map](https://drayker.org/eco/) and connected in the [Dk](https://dk.drayker.org) page, but it has no published specification yet — deciding how much of the coupler is architecture and how much is early idea is itself a useful piece of work.

## Contributing

Open an issue. Issues small enough for one person to finish carry the `open-function` label and appear on the board at [drayker.org](https://drayker.org/fn/).

English is the canonical language of this documentation; read other languages through automatic translation. Native translation and localization are planned for the Drayker sites.

---

Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
