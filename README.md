# Upkarna — See the Machine. Own the OS.

**Upkarna** is a student-led concept project exploring a more transparent, customisable and accessible smartphone experience.

It combines three ideas:

1. **A transparent flagship phone concept** with a rigid, colour-matched exposed internal core.
2. **Light-based accessibility alerts** that convert calls, alarms and doorbells into visible patterns.
3. **UpkarnaOS**, an Android-first customisation layer with a long-term roadmap toward an independent developer platform.

This repository contains the project documentation, concept assets, research notes and the interactive software proof of concept.

> **Important:** Upkarna is currently a concept-stage project. It is not a working smartphone, a finished operating system, or a commercially available product. The hardware, native operating system, manufacturing plan and developer platform are design targets and future roadmap items.

---
## How to open the proof html?

Click on the “Code” button and then press the download as .zip button. Then extract the .zip and then double click the .html file to open it in a suitable browser on Windows, MacOS or Linux.


## Live proof of concept

The current proof of concept is an **interactive web simulation**. It demonstrates two parts of the Upkarna concept:

- The Transparent Edition lighting interface.
- A basic UpkarnaOS customisation interface.

### What the demo shows

| Demo | What you can try |
|---|---|
| Transparent Edition lights | Choose an internal colour, then test message alerts, charging progress, a music beat, camera countdown, the Core Lamp and sound-to-light accessibility patterns. |
| UpkarnaOS customiser | Change icon shape, grid density, clock weight and theme colours in real time. |

The demo is **software only**. It does not control real phone hardware, does not run on a physical device, and does not represent a completed operating system.

---

## The problem

Modern smartphones are often sealed, difficult to understand and difficult to repair. They also rely heavily on sound and vibration to communicate alerts, which can exclude people who are deaf or hard of hearing.

Upkarna explores four connected problems:

| Problem | Why it matters |
|---|---|
| Phones are sealed and hard to repair | Users often cannot see what is inside, understand failures, or repair devices easily. |
| Alerts depend on sound or vibration | Deaf and hard-of-hearing users may miss calls, alarms or doorbell notifications. |
| Premium specifications are becoming more expensive | Memory and component costs make high-end configurations harder to afford. |
| New mobile platforms struggle with app availability | A new operating system is only useful if important apps and developers are supported. |

---

## The proposed solution

Upkarna proposes a smartphone concept with three connected parts:

### 1. Transparent Edition hardware

The Transparent Edition uses a clear rear panel to make the phone’s engineering visible. The concept includes:

- A rigid, colour-matched exposed internal core.
- A battery, motherboard, shields and heat spreaders secured to an aluminium mid-frame.
- A vapour-chamber cooling structure styled as visible metallic veins.
- A micro-LED lighting matrix around the rear panel.
- A central illuminated “Core Lamp.”
- An isolated camera-module mount to reduce vibration near the camera.

### 2. Light as an accessibility layer

The most important near-term idea is **sound-to-light alerts**.

Instead of relying only on sound or vibration, the phone could show distinct visual patterns for:

- Incoming calls.
- Alarms.
- Doorbell notifications.
- Charging progress.
- Timers.
- Deliveries.
- Camera countdowns.
- Music or audio feedback.

This feature is designed to make alerts more usable for deaf and hard-of-hearing users, while also helping anyone who keeps their phone face-down, silent, or in another room.

### 3. UpkarnaOS

UpkarnaOS is proposed in two tracks:

| Track | Purpose |
|---|---|
| Track A: Android-based UpkarnaOS | Launch with an Android base so users retain access to familiar apps and services. Add Upkarna’s customisation, lighting and design layer. |
| Track B: Native UpkarnaOS | Develop an independent operating system alongside Android, switching only after app coverage, security, performance and stability requirements are met. |

The native OS is a **long-term research and development goal**, not something that exists today.

---

## What is real today

| Area | Status |
|---|---|
| Interactive lighting and OS-customisation simulation | **Working software proof of concept** |
| Transparent-phone design concept | **Design concept** |
| Sound-to-light accessibility concept | **Design concept, demonstrated in simulation** |
| Physical transparent-phone prototype | **Not built yet** |
| Native UpkarnaOS | **Not built yet** |
| Manufacturing partnership | **Not established** |
| Supplier agreements | **None** |
| Patents or licences | **None** |
| Revenue or sales | **None** |


---

## Project roadmap

### Current stage: interactive proof of concept

- [x] Define the core problem and target users.
- [x] Research smartphone design, accessibility and market trends.
- [x] Create the Transparent Edition concept.
- [x] Design the lighting interaction model.
- [x] Build an interactive lighting and OS-customisation simulation.
- [x] Create a source-checked evidence register.
- [x] Create a cost-model and assumptions register.
- [ ] Build a physical LED-back prototype.
- [ ] Test brightness, battery use, heat and durability.
- [ ] Conduct user testing, including accessibility-focused feedback.
- [ ] Develop a mobile app or web interface for custom light patterns.
- [ ] Create a simplified Android-based customisation prototype.
- [ ] Explore a native OS architecture only after the hardware concept is validated.

---

## Next milestone: physical prototype

The next major milestone is to build a low-cost physical prototype of the lighting system.

A possible prototype would use:

- A transparent acrylic or 3D-printed phone-back shell.
- An ESP32, Arduino Nano, or Raspberry Pi Pico.
- Addressable RGB LEDs or a small LED matrix.
- A rechargeable power bank or safe low-voltage battery.
- A mobile or web interface to trigger light patterns.
- Basic sensors or Bluetooth input for alerts.

The prototype would test:

- Whether users can recognise different alerts from a distance.
- Battery consumption at different brightness levels.
- Heat generated by the LEDs.
- Visibility in daylight and darkness.
- User preference for different light patterns.
- Usefulness for people who cannot rely on sound alerts.

---

## Accessibility commitment

Upkarna treats accessibility as a core design requirement, not an optional feature.

The project aims to explore:

- Distinct visual patterns for different alert types.
- Adjustable brightness, colour and animation speed.
- Reduced-motion options.
- High-contrast themes.
- Larger interface elements.
- Customisable haptic and visual notification settings.
- Regional-language support in future software versions.

Future testing should include feedback from deaf and hard-of-hearing users, accessibility experts, and people with low vision or motor-related needs.

---

## Sustainability and repairability

The Transparent Edition concept is also intended to encourage repairability and longer device life.

Planned design principles include:

- A published repair-price list.
- Available spare parts, including the transparent rear panel.
- Repair guides and diagnostic tools for authorised technicians.
- A clear software-update policy.
- A defined support period for devices that remain on the Android-based track.
- Reduced unnecessary replacement through repairable design.

These are design goals, not completed features.

---

## Economic model

Upkarna’s economic model uses target costing: it begins with a proposed customer price and calculates the maximum allowable cost per unit.

Key assumptions include:

- Indian GST rate: 18%.
- Channel and marketplace cost: 10% of the pre-GST price.
- Target gross margin: 25% of the amount received by Upkarna.
- Exchange rate used for planning: ₹94.5 per US dollar.
- No government incentive is assumed in the base case.

The 24 GB RAM / 1 TB storage configuration is treated as a cost-gated option. It would ship only if supplier quotations allow the project to preserve its price ceiling and margin target.

These figures are planning assumptions, not verified supplier quotes or financial forecasts.

---

## Evidence and research

The project maintains an evidence register that separates:

- **Verified:** A fact or product that already exists and is supported by a named source.
- **Design target:** Something Upkarna intends to build but has not yet built or tested.
- **Assumption:** A planning input chosen for modelling or decision-making.

Examples of corrections made during research include:

- Replacing IP69K with IP68/IP69, because IP69K is primarily a road-vehicle standard.
- Replacing LPDDR6X with LPDDR5X, because LPDDR6X does not exist.
- Removing an unsupported “120 W in 18 minutes” charging claim.
- Correcting the camera specification from a 200 MP main sensor to a 50 MP main sensor plus a 200 MP periscope telephoto.

---

## Intellectual property

Upkarna currently has:

- No incorporated company.
- No patents.
- No trademarks.
- No licences.
- No supplier or manufacturing agreements.
- No revenue or sales.

The project plans to protect original work in the future through:

- Company incorporation.
- Provisional patent filings, where appropriate.
- Design registrations.
- Trademark searches and filings.
- Freedom-to-operate research.

No intellectual-property rights are claimed in this repository beyond original project documentation, design concepts and code created for this submission.

---

## AI use and transparency

AI tools may be used to support research, writing, visualisation, coding and concept development.

However:

- All important claims are checked against sources.
- AI-generated material is reviewed before being used.
- The project clearly separates verified facts from design targets and assumptions.
- The interactive proof of concept is software only and does not represent a working phone or operating system.
- AI-generated code or designs must be reviewed, tested and checked for licensing or security issues before any future product use.

---

## Contributing

This is currently an individual student project, but future contributions may include:

- Hardware prototype design.
- Embedded firmware for LED control.
- Web or mobile interface development.
- Accessibility research and user testing.
- Documentation and translation.
- Industrial design and 3D modelling.
- Market and cost research.

If you would like to contribute, open an issue describing your idea or submit a pull request with a clear explanation of the change.

---

## License

This repository is intended for educational, research and portfolio purposes.

Until a licence file is added, assume that the contents are protected by default copyright rules and may not be reused commercially without permission.

---

## Contact

**Project:** Upkarna  
**Founder:** Darshit Yadav  
**Stage:** Interactive proof of concept  
**Award context:** National Startup Awards 6.0 — Student Innovator / Aspiring Entrepreneur  

For questions, feedback or collaboration ideas, open a GitHub Issue in this repository.
