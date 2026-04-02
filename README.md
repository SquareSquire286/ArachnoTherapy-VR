# ArachnoTherapy VR
![ArachnoTherapy_Banner](Documentation/Misc/ArachnoTherapy_Banner.png)

<h2 align="center">
  <a href="https://youtu.be/1JCVEE52tXU">Click to watch the project video</a>
</h2>

## Overview

ArachnoTherapy VR is a research-driven virtual reality prototype exploring how interactive virtual environments can be used to support exposure-based approaches for spider phobia (arachnophobia).

Exposure therapy often requires in vivo exposure, which can be costly, time-consuming, and difficult to control. Virtual reality (VR) provides an alternative by allowing exposure scenarios to be controlled, repeatable, and adjustable to individual comfort levels. However, many VR exposure experiences lack sufficient degrees of **gradation**: the ability to be customized and fine-tuned to meet individual therapy clients' needs.

This project explores a more adaptable approach to VR exposure by allowing users to observe and interact with spiders of progressively higher fidelity while being guided through the experience step-by-step by a virtual therapist. Initial fidelity levels entail 2D representation, intermediate levels involve interacting with clay figurines and observing a captive spider from afar, and the final level affords interaction with animated spiders who possess realistic behaviour trees.

This project was developed with input from clinical psychology researchers to ensure that the exposure structure and interaction design were informed by established exposure therapy principles such as gradual exposure, user control, and repeatability. Of particular note is the final intensity level's adherence to the adage of "context being everything" -- a person may have no issue seeing a spider in their office, but be terrified when one appears in the bedroom. As such, we included three different environments wherein spiders can be observed and interacted with: a bedroom, a bathroom, and a dimly lit laundry room.

**Note:** This project is a research prototype and is not a clinical tool.

---

## Project Goals

The goals of this project were to:

- Explore how interactive VR systems can support gradual exposure scenarios
- Investigate user-controlled exposure parameters (number of spiders, size, behaviour, distance)
- Provide educational content and coping strategies before exposure begins
- Design a structured exposure progression system
- Create a framework that could be used in future therapist-guided VR exposure sessions

---

## Exposure Design

The experience is structured into multiple stages designed to gradually increase exposure intensity:

1. **Introduction and Orientation**
   - Users are introduced to controls and the structure of the experience.
   - Coping strategies and educational material are presented before exposure begins.

2. **Spider Familiarization**
   - Users can observe spider models and learn about them before exposure to realistic spiders.
   - Audio, video, and written educational tools are available.

3. **Terrarium Exposure**
   - Spiders are first introduced in a controlled, enclosed environment.

4. **Room-Scale Exposure**
   - Users can place spiders in virtual home environments and control their behaviour.

5. **Advanced Interaction**
   - Users may approach, crouch near, or attempt to touch spiders when comfortable.

A key design goal was **user-controlled exposure intensity**, allowing users to progress at their own pace.

---

## System Features

- Interactive spider spawning system
- Adjustable spider size, behaviour, and quantity
- Multiple exposure environments
- Educational content and coping strategy guidance
- Virtual therapist guidance system
- Level-based progression system
- VR interaction using Meta Quest

---

## Technical Implementation

This project was developed in **Unity** for the **Meta Quest** platform.

Key technical systems include:

- VR interaction system
- Spider behaviour system
- Spider spawning interface
- Exposure progression system
- Virtual therapist guidance system
- UI systems for education and exposure control
- Audio integration for guided instruction

---

## Research Context

This project was developed as part of an undergraduate capstone project in software engineering, with guidance from researchers in clinical psychology and human-computer interaction.

The goal of the project was not to create a clinical product, but to explore how VR interaction design can support exposure-based experiences in a controlled and user-driven way.

This project contributed to later research work exploring virtual reality exposure therapy and interactive VR systems for mental health applications.

---

## Limitations

This project is a prototype and was not evaluated as part of a clinical trial.  
It is not a clinically validated therapy tool and should not be used as a substitute for professional treatment.

Future work would involve:
- Collaboration with clinicians
- Formal user studies
- Evaluation of therapeutic outcomes
- Therapist-controlled interfaces
- Data logging for exposure sessions

---

## Installation Instructions

1. Download the APK file here:  
   https://squaresquire286.itch.io/arachnotherapy-vr

2. Load the APK to a Meta Quest headset using SideQuest:  
   https://sidequestvr.com

3. Launch the app from the **Unknown Sources** library.

Additional SideQuest instructions:  
https://learn.adafruit.com/sideloading-on-oculus-quest/install-and-use-sidequest

---

## Team Members & Contributions

- Jacob Sauer (Conceptualization, Interaction Design, Full-Stack Development, Clinical Collaboration)
- Jacob Chapman (Backend Development, Technical Documentation)
- Roxanne Harrison (Frontend Development, Marketing, Design Documentation)

---

## Acknowledgements

We would like to thank the following individuals and organizations for their guidance and support:

- Dr. Craig Gelowitz
- Dr. Timothy Maciag
- Dr. R. Nicholas Carleton
- University of Regina aRMADILo Lab

Their input helped ensure that the exposure structure and project direction were informed by established psychological research and exposure therapy practices.

---

## Disclaimer

ArachnoTherapy VR Copyright (C) 2022  
Jacob Chapman, Roxanne Harrison, Jacob Sauer

This project is a research prototype and is not a clinically proven therapy tool.  
Use at your own risk.
