
# Computer Networks — Handwritten Notes

---

## Date: 2/3/26

### TCP / OSI Layer Model

```
Application  |  Presentation  | ← apply encryption
             |    Session     |
IP {         Transmission
             Network
             Datalink
             Physical
             Data → Signal
```

> **Layer Stack (TCP/IP):**
> - Application / Presentation / Session ← *apply encryption*
> - Transmission
> - Network
> - Datalink
> - Physical
> - Data → Signal

---

## Date: 16/3/26

### * Data: information in some form

### * Data Communication: exchange of data.

**Components →**
- o message
- o sender / receivers
- o transmission medium
- o protocol.

---

### * Data Flow Mode

i) **Simplex** — one way

ii) **Half Duplex** — receive and send, but not at same time

iii) **Full Duplex** — simultaneous receive and send

---

### * Communication Types

i) P2P
ii) Multipoint

---

<!-- PAGE RIGHT COLUMN — Page 1 -->

## * Topology

> How the rest network is laid down.

### i) Mesh — every device has dedicated P2P.

![Placeholder: Hand-drawn mesh topology diagram showing 5 nodes (circles) fully interconnected with lines representing dedicated point-to-point links between every device]()

---

### ii) Star — hub connected to each machine.

![Placeholder: Hand-drawn star topology diagram showing a central HUB box connected to 4 nodes (circles) arranged around it]()

---

### iii) Bus — one long cable.

![Placeholder: Hand-drawn bus topology diagram showing a single horizontal long cable (line) with 3 nodes (circles) connected via drop lines/connectors hanging below the cable]()

---

### iv) Ring — P2P with 2 adjacent machines only.

![Placeholder: Hand-drawn ring topology diagram showing 5 nodes (circles) connected in a closed loop/ring formation, each node connected only to its two adjacent neighbors]()

---

### v) Hybrid — Mix of all

![Placeholder: Hand-drawn hybrid topology diagram showing a HUB at the top connected to a bus line below it with multiple nodes (circles with device symbols) attached, and a ring sub-network of circles at the bottom right, with dashes indicating continuation]()

---
<!-- PAGE BREAK -->
---

## Page 2

---

## * Categories —

- **LAN** — privately owned network
- **MAN** — area inside town or city
- **WAN** — large geographic area

---

## OSI Model

![Placeholder: Hand-drawn OSI model label with layers partially visible including Application, Presentation layers, with some scribbled/crossed out text above]()

**→ Physical** — responsible for movement of individual bits.

**→ Data Link** — movement of frames from one hop to next.
> *[Hop to Hop delivery]*

**→ Network** — delivery of individual packages.
> *[End to end delivery]*

**→ Transport** — delivery of a message from one process to another.

---

## Date: 8/4/26

## Transmission Media

| Layer | Scope |
| :--- | :--- |
| Application | |
| Transport | Process to Process |
| Network | Source to Destination |
| Data Link | Hub to Hub |
| Physical | Through transmission medium |

---

<!-- RIGHT COLUMN — Page 2 -->

### Transmission Channel Diagram

```
Sender                        Receiver
[Phy Layer]                 [Phy Layer]
       ↘    Transmission Channel   ↙
              [Trans. Media]
                   /        \
            Guided           Unguided
           (Wired)           (Wireless)
           /    \    \            \
      Twisted  Coaxial  Fibre    Wi/3G/4G
       Pair    Cable    Optic     (air)
       Cable            Cable
```

```mermaid
graph TD
    A[Trans. Media] --> B[Guided / Wired]
    A --> C[Unguided / Wireless]
    B --> D[Twisted Pair Cable]
    B --> E[Coaxial Cable]
    B --> F[Fibre Optic Cable]
    C --> G[Wi/3G/4G - Air]
```

---

### * Propagation Modes ...

- Step index ...
- Graded index ...
- Adv. / Disadv. of optical fibre

---

### Signals

- **Analog / Digital Data**
- **Periodic / Aperiodic Signals**

---
