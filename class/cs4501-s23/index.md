---
permalink: "/class/cs4501-s23/"
layout: single
title:  "Wireless for the Internet of Things"
description: "Wireless for the Internet of Things Course"
sidebar:
  - title: "Course"
    text: "CS/ECE4501
    <br />
    Spring 2023"
  - title: "Lecture"
    text: "M/W, 2:00-3:15pm
    <br />
    Thornton E-316"
  - title: "Instructors"
    text: "Brad Campbell
    <br />
    241 Olsson
    <br />
    bradjc@virginia.edu
    <br />
    <br />
    Nabeel Nasir
    <br />
    nabeeln@virginia.edu"
  - title: "Teaching Assistants"
    text: "Viswajith Govinda Rajan (Vish)
    <br />
    gyx4bw@virginia.edu
    <br />
    <br />
    Lahiru Nuwan
    <br />
    lnw8px@virginia.edu"
  - title: "Office Hours"
    text: "Brad Campbell: Th 4-5pm, Fr 10-11am.
    <br />
    Nabeel Nasir: Tu 2-3pm, Fr 2-3pm
    <br />
    Vish Govinda Rajan: Tu 4-5pm, We 11-noon
    <br />
    Lahiru Nuwan: We noon-1pm, We 4-5pm"
---

<style>
.masthead {
  display: none;
}
</style>



<img src="images/city-iot.jpg" width="23%">
<img src="images/sensor.png" width="23%">
<img src="images/ThreadBluetoothDualRadioDevice.png" width="23%">



Overview
--------

The Internet of Things (IoT) is a computing platform where a large number of
_devices_ form a _network_ to monitor, control, and optimize some physical
system. To be scalable, these devices communicate _wirelessly_, both with each
other and to the Internet at large. But what wireless protocols are available
for IoT devices? How do they work? And why are there so many? This course will
provide a hands-on introduction to the world of wireless in the Internet of
Things. Over the course of the semester we will explore what wireless options we
have available, how they differ and what the tradeoffs are, and how major IoT
wireless protocols work. We will also build networks of devices using real-world
wireless protocols. Our goal is for you to be able to build your own wireless
devices with a wireless protocol that meets your application requirements and
device constraints.

We will look at WiFi, Classic Bluetooth, Bluetooth Low Energy, IEEE 802.15.4,
2G/3G/4G/5G cellular, LTE-M, NB-IoT, LoRa, and Z-Wave. We will also explore some
emerging wireless options, such as visible light communication (VLC), infrared
communication (IR), ultrasonic, wake-up radios, and backscatter.

Projects
--------

The list of [student projects](projects.html) is posted!

<!-- Deliverables
------------

This major deliverables in this course will include:

- labs
- four hands-on assignments
- short in-class quizzes
- homeworks
- a mid-term exam
- a final project -->

Course Objectives
-----------------
By the end of the course, you will be able to...
- explain, analyze, and compare different IoT wireless protocols.
- analyze and model the power draw and spectrum utilization of wireless
  protocols.
- develop hands-on skills using standards-compliant protocols.
- identify requirements for a wireless protocol for a specific application.
- recognize rationale for heterogeneity in wireless IoT protocols and how design
  choices impact both applications and users.
- work effectively in a group to build IoT networks while overcoming challenges.


Grading
-------

- Quizzes: 5%
- Labs: 20%
- Assignments: 30%
- Exam: 15%
- Homeworks: 10%
- Final Project: 20%


Assessments
-----------

- **Quizzes**: These in-class quick formative assessments will help students
  stay accountable to the material and highlight the most important aspects from
  the last lecture/class. Quiz grading is 50% completion and 50% correctness.
  The end-of-semester quiz score is calculated out of 75% of total possible
  points. (approx. 20 quizzes, 5%)

- **Labs**: In-class labs will give students hands-on experience developing and
  debugging wireless networks. Labs will be largely structured and are formative
  assessments. Students will generate some output, such as a plot or paragraph
  description for light grading. (10 labs, 20%)

- **Assignments**: These projects will require students to build various
  wireless networks and leverage the properties of the wireless protocols to
  meet given application requirements. The output will be working code that
  implements the required functionality. Additionally, there may be required
  data collection they must complete. (4 assignments, 30%)

- **Exams**: An in-class exam will assess student learning of key concepts on
  wireless protocols and how they relate to applications. (1 exam, 15%)

- **Homework**: Homework will give students a chance to practice analyzing
  wireless protocols and matching protocols to applications. The homework will
  provide example questions that will be on the exam. (4 homework assignments,
  10%)

- **Final Project**: The final project will have students use wireless protocols
  to develop their own application and device, and measure its performance. (1
  project, 20%)


Honor
-----

We trust every student in this course to fully comply with all of the provisions
of the University's Honor Code. By enrolling in this course, you have agreed to
abide by and uphold the Honor System of the University of Virginia.



Prerequisites
-------------

- CS 2130 (CSO1) OR CS 2150 (Program and Data Representation)
- CS 3130 (CSO2) OR ECE 3430 (Embedded) OR CS 4414 (OS) OR CS 3330 (Architecture) OR ECE 4750 (DSP) OR Instructor Approval

### Helpful Resources

While there is no textbook for this course, there are some references that are
helpful for getting up to speed with C in an embedded context.

- [Introduction to C Programming](http://cs.yale.edu/homes/aspnes/classes/223/notes.html#c)
- [C Programming: Memory and Pointers](https://github.com/kalpak92/System-Programming/blob/master/2.%20Introduction%20to%20C%20Programming/C%20Programming%20-%20Part%203.md) (ignore anything with malloc())
- [C Programming: Standard Library](https://github.com/kalpak92/System-Programming/blob/master/2.%20Introduction%20to%20C%20Programming/C%20Programming%20-%20Part%205.md)
- [C Pointers and Registers](https://hackaday.com/2018/04/04/the-basics-and-pitfalls-of-pointers-in-c/)
- [Endianness](https://embetronicx.com/tutorials/p_language/c/little-endian-and-big-endian/)


Related Courses
---------------

- ECE 4784 (Wireless Communications): Focuses on the physical layer, including
  signaling and modulation.
- ECE 4501 (Low Power Wireless Transceivers for IoT): Focuses more on radio
  hardware, as well as emerging techniques and research.
- CS/ECE 4457 (Computer Networking): Focuses on the layered network stack and
  protocols used in the internet.



Schedule
--------

| Date                                     | Topic(s)                  | Before Class | Due |
|---|---|---|---|
| W 01/18                                  | Introduction and Overview [[slides](slides/01-intro.pptx)] |  |  |
| M 01/23<br>How do computers communicate? | Networking Fundamentals   [[slides](slides/02-networking.pptx)] |  |  |
| W 01/25                                  | Wireshark Lab             [[slides](slides/03-wireshark.pptx)] [[prelab](resources/wiot-lab1-prelab.pdf)] [[lab](resources/wiot-lab1.pdf)] [[postlab](resources/wiot-lab1-postlab.pdf)] |  | HW1 |
| M 01/30<br>Wireless: magic?              | Wireless Fundamentals     [[slides](slides/04-wireless.pptx)] |  |  |
| W 02/01<br>What is Bluetooth Low Energy? | BLE Intro                 [[slides](slides/05-ble-intro.pptx)] |  |  |
| M 02/06                                  | BLE Advertisements        [[slides](slides/06-ble-adv.pptx)] |  |  |
| W 02/08                                  | BLE Advertisement Lab     |  |  |
| M 02/13                                  | BLE Connections           [[slides](slides/08-ble-connections.pptx)] |  |  |
| W 02/15                                  | BLE Connections Lab       [[slides](slides/09-ble-connections-lab.pptx)] |  |  |
| M 02/20<br>What other network types are there? | IEEE 802.15.4 Intro [[slides](slides/10-802.15.4-intro.pptx)] |  |  |
| W 02/22                                  | IEEE 802.15.4 Packets     [[slides](slides/11-802.15.4-packets-mac.pptx)] |  |  |
| M 02/27                                  | IEEE 802.15.4 Networks    [[slides](slides/12-802.15.4-mesh.pptx)] |  |  |
| W 03/01                                  | IEEE 802.15.4 Lab         |  | A2, HW2 |
| M 03/06                                  | No Class: Spring Break    |  |  |
| W 03/08                                  | No Class: Spring Break    |  |  |
| M 03/13<br>Can Samsung and Google agree? | Thread + Routing          [[slides](slides/14-thread.pptx)] |  |  |
| W 03/15                                  | Thread Lab                |  |  |
| M 03/20<br>What about WiFi?              | WiFi                      [[slides](slides/16-wifi.pptx)] |  |  |
| W 03/22                                  | WiFi Lab                  |  | A3 |
| M 03/27<br>Ok enough short range. Can we cover long distances? | LPWAN + LoRa [[slides](slides/18-lpwan-lora.pptx)] | |  |
| W 03/29                                  | LoRa Lab                  |  |  |
| M 04/03<br>Is a smartphone IoT?          | Exam Review               |  |  |
| W 04/05                                  | Exam                      |  | A5 |
| M 04/10                                  | 4G/5G, Discuss Final Projects [[slides](slides/22-cellular.pptx)]  |  |  |
| W 04/12                                  | Matter/LTEM/NBIoT         [[slides](slides/23-celliot-backscatter-matter.pptx)] |  |  |
| M 04/17<br>What's next?                  | Guest Speaker: VLC        [[slides](slides/April2023_VLCCourse_UVATemplatev1.pdf)] |  |  |
| W 04/19                                  | Guest Speaker: Everactive [[slides](slides/Everactive-WIoT.pdf)] |  | A6, HW4 |
| M 04/24                                  | Lab: Final Projects       |  |  |
| W 04/26                                  | Guest Speaker: Alef       |  |  |
| M 05/01                                  | Lab: Final Projects       [[slides](slides/28-wrapup.pptx)]  |  |  |
| Th 05/04                                 | Class Demo Day            [[projects](projects.html)]|  | Final Project |


Attendance Policy
-----------------

This class heavily centers on group work and in-class hands-on practice to help
you learn the course material. For this to be valuable, attendance is required.

Late Work Policy
----------------

There are various deliverables in this class. We expect you to complete each
deliverable by its due date, but we realize that is not always possible. Some
assignments can be turned in late.

- Pre-labs: These are always due at the start of the lab session they are
  assigned for. It is critical that these are completed in advance to make the
  lab productive and increase the benefit of the lab to you. Pre-labs cannot be
  submitted late.
- Labs: Labs are due one week after the corresponding lab session. You may
  submit up to one week late for a 50% score penalty. After that it will not be
  accepted.
- Assignments: Your group has 5 late days to use throughout the semester for
  assignments. You may use up to 3 late days on any one assignment. We will
  automatically apply the late days if you submit the assignment late. After 3
  days late (or if you run out of late days) there will be a 10% reduction for
  one day late and a 20% reduction for two days late. After that the assignment
  will not be accepted.
- Homework: You may submit one day late for a 10% score penalty or two days late
  for a 20% score penalty. After that the homework will not be accepted. This
  ensures we can release the solutions promptly.
- Quizzes: quizzes are due immediately after they are given and will not be
  accepted late.

Honor/Academic Integrity Policy
-------------------------------

The School of Engineering and Applied Science relies upon and cherishes its
community of trust. We firmly endorse, uphold, and embrace the University's
Honor principle that students will not lie, cheat, or steal, and we expect all
students to take responsibility for the System and the privileges that it
provides. We recognize that even one Honor infraction can destroy an exemplary
reputation that has taken years to build. Acting in a manner consistent with the
principles of Honor will benefit every member of the community both while
enrolled in the Engineering School and in the future.

If you have questions about your Honor System or would like to report suspicions
of an Honor offense, please contact the honor system representatives.

Specific directions for this course:
- In-class labs are done in teams of three and are highly collaborative. You are
  not only allowed to talk with other teams during the lab, you are explicitly
  encouraged to. One rule: hands on your own keyboards, no typing for anyone
  else.
- The pre-labs and lab reports must be done by your group with all your own
  work.
- For the assignments, each team must write and submit their own code, reports,
  and analyses. Consulting with the internet or other written resources is
  acceptable and encouraged.
- Exams must be done individually. Studying in groups is encouraged.
- Homework must be done individually.
- Quizzes must be done individually.

Accessibility
-------------

The University of Virginia strives to provide accessibility to all students. If
you require an accommodation to fully access this course, please contact the
Student Disability Access Center (SDAC) at (434) 243-5180 or sdac@virginia.edu.
If you are unsure if you require an accommodation, or to learn more about their
services, you may contact the SDAC at the number above or by visiting their
website at
https://www.studenthealth.virginia.edu/student-disability-access-center/faculty-staff.


Your Wellbeing
--------------

The Computer Science Department and SEAS aims to promote their students'
wellbeing. If you are feeling overwhelmed, stressed, or isolated, there are many
individuals here who are ready and wanting to help. If you wish, you can make an
appointment with me and come to my office to talk in private.

Alternatively, there are also other University of Virginia resources available.
The Student Health Center offers Counseling and Psychological Services (CAPS)
for its students. Call 434-243-5150 (or 434-972-7004 for after hours and weekend
crisis assistance) to get started and schedule an appointment. If you prefer to
speak anonymously and confidentially over the phone, call Madison House's HELP
Line at any hour of any day: 434-295-8255.

If you or someone you know is struggling with gender, sexual, or domestic
violence, there are many community and University of Virginia resources
available. The Office of the Dean of Students, Sexual Assault Resource Agency
(SARA), Shelter for Help in Emergency (SHE), and UVA Women's Center are ready
and eager to help. Contact the Director of Sexual and Domestic Violence Services
at 434-982-2774.


Diversity
---------

It is the instructors’ intent that students from all diverse backgrounds and
perspectives be well served by this course, that students’ learning needs be
addressed both in and out of class, and that the diversity that students bring
to this class be viewed as a resource, strength and benefit. It is my intent to
present materials and activities that are respectful of diversity: gender,
sexuality, disability, age, socioeconomic status, ethnicity, race, and culture.
Your suggestions are encouraged and appreciated. Please let me know ways to
improve the effectiveness of the course for you personally or for other students
or student groups.


Religious Accommodations
------------------------

It is the University's long-standing policy and practice to reasonably
accommodate students so that they do not experience an adverse academic
consequence when sincerely held religious beliefs or observances conflict with
academic requirements. Students who wish to request academic accommodation for a
religious observance should submit their request in writing directly to me by
email as far in advance as possible. Students and instructors who have questions
or concerns about academic accommodations for religious observance or religious
beliefs may contact the University's Office for Equal Opportunity and Civil
Rights (EOCR) at UVAEOCR@virginia.edu or 434-924-3200. Accommodations do not
relieve you of the responsibility for completion of any part of the coursework
missed as the result of a religious observance.
