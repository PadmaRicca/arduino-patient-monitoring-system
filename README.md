# Arduino-Based Patient Monitoring and Alert System

**Project Level:** Intermediate Undergraduate

**Author:** Padma Michela Ricca  
**Institution:** Middlesex University London  
**Degree:** BEng (Hons) Biomedical Engineering  
**Module:** PDE2401 (Design Engineering Projects 2)  
**Academic Year:** 2nd (2023/2024)  
**Assessment Outcome:** First Class (Distinction)  
**Overall Module Mark:** 5 (Upper Second Class, Merit)  
**Project Type:** Arduino programming, electronic circuit design and physical prototyping project

## Project Overview

Designed and constructed an Arduino-based prototype exploring how electronic sensing and alert mechanisms could assist nursing staff in a simulated hospital environment. The project involved integrating multiple electronic components and programming patient-specific responses using C++ in the Arduino IDE.

The design incorporated four patient rooms and a separate nurses' station, with patient-specific monitoring and alert mechanisms: a nurse-call system with a manual reset function for bedridden patients; distance-based alerts for patients with Chronic Obstructive Pulmonary Disease (COPD); light-sensitive monitoring for patients with neurological disorders or migraines; force-sensitive detection near a Percutaneous Endoscopic Gastrostomy (PEG) feeding tube for patients in a coma. An additional servo-operated mechanism was developed to demonstrate automatic door control.

The system was developed and demonstrated as an academic proof of concept rather than a clinically validated medical device.

## Contributions

- Developed patient-specific monitoring and alert mechanisms, considering differences in patient mobility, environmental sensitivity and risks associated with medical equipment.
- Assembled and wired breadboard circuits integrating pushbuttons, ultrasonic sensors, light-dependent and force-sensitive resistors, LEDs, a servo motor, a vibration motor and a buzzer.
- Programmed Arduino sketches in C++, implementing analogue and digital input processing, conditional logic, sensor thresholds and automated output control.
- Developed a nurse-reset alert mechanism to maintain an emergency signal until acknowledgment, alongside distance-dependent visual alerts and servo actuation.
- Used serial communication and dedicated `Serial.print()` debugging routines to monitor sensor readings, check individual components and investigate circuit behaviour through the Arduino IDE.
- Documented component connections, voltage and current requirements, programming logic and system operation through annotated code and flowcharts developed using draw.io.

## Skills Demonstrated

- **Arduino and C++ Programming:** Practical experience with embedded programming, structured control logic, sensor readings and hardware input/output management using the Arduino IDE.
- **Electronic Circuit Design and Prototyping:** Integration of electronic components, breadboard assembly, electrical measurements and understanding of component operating requirements.
- **Hardware Debugging and Testing:** Using serial communication, sensor readings and component-level checks to investigate functionality and troubleshoot electronic circuits.
- **Patient-Centred Engineering:** Applying critical thinking to different patient conditions and developing tailored alert concepts based on specific monitoring requirements.
- **Engineering Documentation:** Representing system logic through flowcharts, documenting electrical specifications and communicating technical design decisions.

## Report Availability

The original academic code, flowcharts and prototype photographs are currently withheld from public access to uphold academic integrity.

This repository provides an overview of the project's objectives, electronic design approach, programming methodology and skills demonstrated.

Further technical documentation may be shared upon request, in accordance with the University's policy.
