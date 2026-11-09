# mBot Neo Robotics Curriculum

A 12 hour, project based robotics course for learners aged 11 to 16, built around the mBot Neo (mBot2) and mBlock 5. Six two hour sessions take students from first movements to a line following robot that also detects obstacles.

| Session | Focus | Final challenge |
|---|---|---|
| 1 | Robot parts, safety, sequences and movement | The Delivery Driver |
| 2 | Events, program end, loops, first sensors | The Security Patrol |
| 3 | Variables and IF / IF-ELSE | The Gear Shifter |
| 4 | Light and ultrasonic sensors, sampling | The Automated Vacuum Cleaner |
| 5 | Logical operators (AND, OR), multiple conditions | The Night Watchman |
| 6 | Line following combined with obstacle detection | Line follower that avoids obstacles |

Each session follows the same structure: recap, new concept, guided practice, a project based challenge and a reflection, with learning outcomes and performance indicators for assessment.

Written by Franco Ferrari-Accardi for the Sovereign House GH robotics programme. Shown with permission of Sovereign House GH.

---

# COURSE SYLLABUS: EDUCATIONAL ROBOTICS WITH mBot Neo (mBot2)

## 1. Course Overview

- **Course Name:** Educational Robotics with mBot Neo (Level 1)

- **Total Hours:** 12 hours (6 sessions of 2 hours each)

- **Target Audience:** Middle/High School Students (Ages 11-16)

- **Hardware Required:** mBot Neo (mBot2) equipped with CyberPi, mBot2 Shield, Ultrasonic Sensor 2.0, Quad RGB Sensor.

- **Software Required:** mBlock 5 (PC, Mac, or Chromebook)

- **Methodology:** Project-Based Learning (PBL). Students will learn by actively engaging in real-world challenges, emphasizing critical thinking, problem-solving, iterative design, and collaborative teamwork.

## 2. Course Objectives

### General Objective

To develop foundational skills in computational thinking, structured programming, and mechatronics by designing, programming, and testing autonomous behaviors using the mBot Neo robot within a Project-Based Learning framework.

### Specific Objectives

By the end of the course, students will be able to:

1.  Understand the rules, safety, and collaborative dynamics of a robotics workshop.

2.  Identify the hardware components of the mBot Neo and understand the basic principles of robotics (Sensors, Processors, Actuators).

3.  Navigate and utilize the mBlock 5 programming environment effectively.

4.  Apply structured programming concepts including sequences, loops, conditionals (IF, IF-ELSE, ELSE-IF), and variables to solve specific challenges.

5.  Extract, sample, and utilize data from digital and analog sensors (CyberPi buttons, Ultrasonic, Quad RGB) to trigger robot behaviors.

6.  Integrate logical operators (AND, OR) to make complex, multi-conditional decisions.

7.  Design and implement a robust line-following algorithm combined with obstacle detection.

## 3. Learning Outcomes & Performance Indicators

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Learning Objective</strong></th>
<th><strong>Performance Indicators</strong></th>
</tr>
<tr class="odd">
<th><strong>1. Recognize the elements that make up a robot</strong></th>
<th><p>- Identifies the characteristics of an autonomous robot.</p>
<p>- Differentiates between sensors (inputs) and actuators (outputs).</p>
<p>- Identifies the electronic components of the mBot Neo (CyberPi, Shield, Motors, Ultrasonic, Quad RGB).</p></th>
</tr>
<tr class="header">
<th><strong>2. Apply structured programming basics</strong></th>
<th><p>- Identifies the phases of a program (start, execution, end).</p>
<p>- Uses the mBlock 5 IDE to connect the robot and transfer code.</p>
<p>- Implements basic movement commands (forward, turn, stop).</p></th>
</tr>
<tr class="odd">
<th><strong>3. Implement control structures</strong></th>
<th><p>- Uses repeat and forever loops to maintain continuous actions.</p>
<p>- Implements IF, IF-ELSE, and ELSE-IF structures for decision-making.</p>
<p>- Uses variables to store and modify data (e.g., counting events).</p></th>
</tr>
<tr class="header">
<th><strong>4. Utilize sensors for environmental interaction</strong></th>
<th><p>- Samples data using the CyberPi screen.</p>
<p>- Programs the robot to start/stop using touch (CyberPi buttons/joystick).</p>
<p>- Uses the Ultrasonic sensor to measure distance and avoid obstacles.</p>
<p>- Uses the Quad RGB sensor to detect light intensity and colors/lines.</p></th>
</tr>
<tr class="odd">
<th><strong>5. Solve complex challenges using PBL</strong></th>
<th><p>- Combines logical operators (AND, OR) to evaluate multiple sensor inputs simultaneously.</p>
<p>- Designs a line-following algorithm.</p>
<p>- Iteratively tests and debugs code to achieve a final mission.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 4. Class-by-Class Detailed Breakdown

### CLASS 1: First Steps into Robotics & Movement

**Topics Covered:** \* \[A\] Introduction to the workshop, its format and rules

- \[B\] Introduction to robotics and the mBot robot

- \[C\] Fundamentals of structured programming and mBot environment

- \[D\] Programming basic movements: moving, turning, stopping

**Class Objectives:** Establish workshop culture, familiarize students with hardware/software, and write the first movement algorithms.

**Time Schedule (120 mins):**

- **00:00 - 00:20 (20m): Welcome & Context \[A, B\]**

  - *Content:* PBL methodology introduction. "In this class, you are engineers solving problems, not just following manuals." Establish rules: teamwork, handling equipment safely, role rotation (programmer vs. robot handler). Introduce the mBot Neo: point out the "brain" (CyberPi), the "muscles" (encoder motors), and the "senses" (sensors).

- **00:20 - 00:45 (25m): The mBlock 5 Environment \[C\]**

  - *Content:* Open mBlock 5. Explain the interface: Stage, Devices, Blocks area, Scripts area. Demonstrate how to add the "CyberPi" and "mBot2 Shield" extensions. Show how to connect via USB/Bluetooth and switch to "Upload Mode".

- **00:45 - 01:15 (30m): Basic Movements \[D\]**

  - *Hands-on:* Introduce the move \[forward\] at \[50\]% power for \[1\] secs block. Discuss the difference between block execution (sequence). Teach turning using tank mechanics (left wheel forward, right wheel backward) and the stop moving block.

- **01:15 - 01:50 (35m): Final Challenge - "The Delivery Driver"**

  - *Challenge:* Map out a simple "city block" using tape on the floor. Students must program their mBot Neo to start at a warehouse, navigate around the block (incorporating straight lines, 90-degree right turns, and 90-degree left turns), and park in a designated delivery zone.

  - *PBL Element:* Students must calculate the time required for a perfect 90-degree turn through trial and error.

- **01:50 - 02:00 (10m): Wrap-up & Reflection**

  - Clean up. Group discussion: What was the hardest part of making a perfect square? How did battery power affect the turning time?

### CLASS 2: Interactivity & Continuous Execution

**Topics Covered:** \* \[E\] Introduction to the touch sensor (CyberPi buttons) to start the programme

- \[F\] Introduction to the concept of programme end

- \[H\] Introduction to sensors (Input concept)

- \[M\] Structured programming: loops (introduced here to enable continuous sensor reading)

**Class Objectives:** Understand event-driven programming, how to trigger programs manually, the concept of loops, and basic sensor inputs.

**Time Schedule (120 mins):**

- **00:00 - 00:15 (15m): Recap & Intro to Sensors \[H\]**

  - *Content:* What is a sensor? Compare robot sensors to human senses. Focus on the CyberPi's built-in inputs (Button A, Button B, Joystick).

- **00:15 - 00:45 (30m): Start and End Events \[E, F\]**

  - *Content:* Introduce event blocks: when button \[A\] is pressed. Discuss why when CyberPi starts up isn't always safe (the robot might run off the table immediately). Discuss program termination: how to ensure the robot safely stops at the end of a script or when a specific "kill switch" (Button B) is pressed.

- **00:45 - 01:15 (30m): The Power of Loops \[M\]**

  - *Hands-on:* Introduce repeat \[10\] and forever loops. Contrast a linear script (move, turn, move, turn) with a looped script. Have students program the robot to drive in a continuous circle or square infinitely until stopped.

- **01:15 - 01:50 (35m): Final Challenge - "The Security Patrol"**

  - *Challenge:* Program the mBot Neo to act as a security guard. It must *wait* until the security guard turns it on (Button A). Once on, it must patrol an area by moving in a continuous geometric pattern (using a forever loop). If the guard presses Button B (or pushes the joystick down), the program must immediately end and the robot must stop moving entirely.

- **01:50 - 02:00 (10m): Wrap-up & Reflection**

  - Discuss the importance of the forever loop in robotics. Why must a robot constantly "loop" its code to remain active?

### CLASS 3: Smart Decisions with Conditionals & Variables

**Topics Covered:** \* \[G\] Structured programming: Simple IF conditional structure, Double IF-ELSE conditional structure, VARIABLES

**Class Objectives:** Introduce memory (variables) and decision-making structures (IF / IF-ELSE) allowing the robot to change behavior dynamically.

**Time Schedule (120 mins):**

- **00:00 - 00:20 (20m): Introduction to Variables \[G\]**

  - *Content:* What is a variable? Explain it as a "box" that stores information. Create a variable called "Speed". Show how changing the variable changes the robot's movement without rewriting multiple blocks.

- **00:20 - 00:50 (30m): Logic and Conditionals (IF / IF-ELSE) \[G\]**

  - *Content:* Explain Boolean logic (True/False). Introduce the IF \[condition\] THEN block. If the condition is true, execute code; if false, skip it. Next, introduce the IF \[condition\] THEN... ELSE... block for two distinct pathways.

- **00:50 - 01:10 (20m): Guided Practice - CyberPi Screen**

  - *Hands-on:* Instead of moving the robot, use the CyberPi screen. Create a variable "Counter". IF Button A is pressed, change Counter by 1. IF Counter \> 5, display "High" on screen, ELSE display "Low".

- **01:10 - 01:50 (40m): Final Challenge - "The Gear Shifter"**

  - *Challenge:* Create a "transmission" for the mBot. Create a variable called "Gear" (starting at 1).

    - Pressing Joystick Up increases Gear by 1. Pressing Joystick Down decreases Gear.

    - Use a forever loop and IF-ELSE structures.

    - IF Gear = 1, move at 25% speed. IF Gear = 2, move at 50%. IF Gear = 3, move at 100%. ELSE (if gear is 0), stop.

  - *PBL Element:* Students must figure out how to stop the variable from going above 3 or below 0 (introducing the need for nested limits).

- **01:50 - 02:00 (10m): Wrap-up & Reflection**

  - How do variables give the robot a "memory"?

### CLASS 4: Seeing the World (Sampling & Proximity)

**Topics Covered:** \* \[I\] Using light (Quad RGB) and ultrasonic proximity sensors

- \[K\] Sensor sampling

**Class Objectives:** Learn to read raw data from sensors, display it for debugging, and use the Ultrasonic sensor to interact with the physical environment.

**Time Schedule (120 mins):**

- **00:00 - 00:20 (20m): Introduction to Ultrasonic & Quad RGB \[I\]**

  - *Content:* Explain how Ultrasonic works (echolocation like a bat). Explain how the Quad RGB sensor detects light intensity and color reflection.

- **00:20 - 00:50 (30m): Sensor Sampling & Telemetry \[K\]**

  - *Content:* "Sampling" means continuously reading data. Teach students how to print the distance of ultrasonic sensor to the CyberPi screen.

  - *Hands-on:* Have students put their hand in front of the sensor and watch the numbers change. Do the same for the light intensity of the Quad RGB sensor. This is crucial for debugging.

- **00:50 - 01:15 (25m): Integrating Sensor Data with Movement**

  - *Hands-on:* Combine Class 3's IF-ELSE with the Ultrasonic sensor. IF distance \< 15cm THEN stop ELSE move forward. Wrap it in a forever loop.

- **01:15 - 01:50 (35m): Final Challenge - "The Automated Vacuum Cleaner"**

  - *Challenge:* Program the robot to behave like a Roomba. It must drive forward continuously. If it detects an obstacle closer than 10cm, it must stop, play a warning sound, reverse for 1 second, turn right for a random amount of time (using the pick random operator), and then resume driving forward.

- **01:50 - 02:00 (10m): Wrap-up & Reflection**

  - Why is sensor sampling (printing data to the screen) important before writing the movement code? (Answer: To know the exact threshold values to use in the code).

### CLASS 5: Complex Logic & Multiple Conditions

**Topics Covered:** \* \[J\] Basic logical operators (AND, OR, NOT)

- \[L\] ELSE-IF conditional structure

**Class Objectives:** Manage complex decision-making scenarios where multiple environmental factors must be considered simultaneously.

**Time Schedule (120 mins):**

- **00:00 - 00:20 (20m): Logical Operators \[J\]**

  - *Content:* Explain AND (both must be true), OR (at least one must be true), and NOT (reverses the truth). Use real-world examples: "If it is raining AND I have an umbrella..."

- **00:20 - 00:50 (30m): The ELSE-IF Structure \[L\]**

  - *Content:* Explain that sometimes we have more than two pathways. Instead of nesting many IF-ELSE blocks, we use the IF... ELSE IF... ELSE logic. (Note: in mBlock, this is often achieved by stacking IFs or nesting IF-ELSE, teach the visual structure).

- **00:50 - 01:10 (20m): Guided Practice - Smart Headlights**

  - *Hands-on:* Use the Quad RGB ambient light reading. IF ambient light is low, turn on the CyberPi LED headlights. Use AND to ensure headlights only turn on IF light is low AND the robot is moving.

- **01:10 - 01:50 (40m): Final Challenge - "The Night Watchman"**

  - *Challenge:* The robot patrols an area.

    - Condition 1: IF it detects an obstacle \< 10cm AND the ambient light is dark -\> The robot must stop, flash red and blue LEDs like police lights, and sound an alarm.

    - Condition 2: ELSE IF obstacle \< 10cm AND light is bright -\> It just turns around and continues.

    - Condition 3: ELSE -\> It patrols forward normally.

- **01:50 - 02:00 (10m): Wrap-up & Reflection**

  - Review how logical operators make code more efficient and behaviors more lifelike.

### CLASS 6: The Ultimate Challenge (Line Following)

**Topics Covered:** \* \[N\] Line-following algorithm using a sensor

- \[O\] Review of content

**Class Objectives:** Understand and implement a continuous feedback loop (hysteresis/line tracking algorithm) and demonstrate mastery of all course concepts in a final comprehensive project.

**Time Schedule (120 mins):**

- **00:00 - 00:20 (20m): The Theory of Line Following \[N\]**

  - *Content:* How does a robot follow a line? Introduce the Quad RGB sensor's line-tracking capabilities (L1, L2, R1, R2 probes). Explain the algorithm: IF left sensor sees black, turn left (to get back on the line). IF right sensor sees black, turn right. ELSE (both see white), drive forward.

- **00:20 - 00:50 (30m): Basic Line Follower Implementation**

  - *Hands-on:* Students use mBlock's built-in Quad RGB blocks (or raw analog values if advanced) to create the basic IF-ELSE-IF structure for line following. Test it on a simple oval track.

- **00:50 - 01:00 (10m): Review of Course Mechanics \[O\]**

  - *Content:* Quick whiteboard recap. How do we start the program safely? (Buttons). How do we detect obstacles? (Ultrasonic). How do we make decisions? (IF-ELSE).

- **01:00 - 01:50 (50m): THE FINAL GRAND CHALLENGE - "The Autonomous Factory Transport"**

  - *Challenge:* Combine everything. The robot must:

    1.  Wait for Button A to be pressed to start the shift.

    2.  Follow a complex black line track (curves and straights).

    3.  Use the Ultrasonic sensor simultaneously (AND / IF conditions inside the main loop). If an obstacle (a "worker" or "box") is placed on the line, the robot must stop, turn its LEDs Yellow, and wait.

    4.  When the obstacle is removed, the LEDs turn Green and it resumes following the line.

    5.  Pressing Button B safely stops all motors and ends the program.

- **01:50 - 02:00 (10m): Final Presentation & Course Wrap-up**

  - Students demonstrate their final algorithms. Award certificates/acknowledgments.

## 5. Developer Notes for Creation of Educational Materials

When using this curriculum to develop your student workbooks, slide decks, and teacher guides, adhere to the following guidelines based on the provided methodology:

1.  **Slide Decks:**

    - Every class slide deck must start with the **"Challenge of the Day"** to immediately frame the learning context (PBL).

    - Include high-quality screenshots of the mBlock 5 interface, specifically highlighting where to find extension blocks (like CyberPi and mBot2 Shield).

    - Use flowcharts for Classes 3, 5, and 6 to visually explain IF-ELSE and logical operators before showing the block code.

2.  **Student Workbooks:**

    - Include a "Telemetry Log" section in Class 4 where students manually write down the values they sample from the sensors (e.g., Room Light level, Shadow level, Distance to hand).

    - Provide debugging checklists: (1. Is the robot turned on? 2. Is it connected via Bluetooth/USB? 3. Are the sensors plugged into the correct ports?).

3.  **Teacher Guide:**

    - Emphasize *not* giving students the final code for the challenges. The guide should contain the "Solution Code," but teachers should only provide guiding questions.

    - Note common pitfalls: Forgetting to put an IF statement inside a forever loop; placing the Ultrasonic sensor check *after* a long move forward for 5 seconds block (which blocks the code from reading the sensor).
