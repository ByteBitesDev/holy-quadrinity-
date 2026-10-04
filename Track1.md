https://d8it4huxumps7.cloudfront.net/uploads/attachements/files/50b1e524-c089-4e8a-96ef-b6b00e7e0490.pdf <br>

<ins>This link is for the pdf regarding all details of Track 1 Topics </ins>

<h1 align="center">PROJECT IO SUDOKU</h1>           
<p>A process plant has thousands of field instruments: transmitters, switches, valves, motors. Each one sends or receives one electrical signal, carried to the control room in multi-pair cables of 24, 12, 6 or 2 pairs. Before the DeltaV control system can use them, an engineer must give every signal an exact home: a CHARM slot, on a baseplate, under a CIOC, inside a cabinet. This must follow project rules: keep related signals together, separate duty and standby equipment, use the right CHARM and leave spare room. <ins>Today this is done by hand in Excel for 10,000+ signals, and every customer revision means reworking it and tracing the impact again.</ins> <strong>Can a tool do it from rules the engineer defines, and raise TQs where the data conflicts?</strong> </p><br>

<h2> Understanding the Terms of the problem:- </h2><br>
1) A <b>process plant</b> is a large industrial facility where raw materials are processed into something useful.<br>
2) A <b>field instrument</b> is a physical device installed out in the plant that either:<br>
-measures something<br>
-detects something<br>
-sends information<br>
-receives a control signal<br>
-or helps control a process<br>
3) A <b>transmitter</b> measures something and sends that measurement to a control system.<br>
4) A <b>switch</b> usually tells you whether something has crossed a particular condition.<br>
5) A <b>valve</b> controls the flow of something through a pipe.<br>
6) A <b>Motor</b> converts electrical energy into mechanical movement.<br>
Each of these field instruments communicate with the control room using electrical signals in pairs.(Every pair has a different instrument with different combinations)<br>
<b>•Signal → CHARM slot → Baseplate → CIOC → Cabinet</b><br>
<b>•CHARM is essentially a configurable I/O module used in Emerson's DeltaV system.</b><br>
>CHARM = a place where a field signal gets connected to the DeltaV system.<br>
each charm module is a position.<br>
<b>•A baseplate is the physical structure that holds the CHARM modules.</b><br>
<b>•CIOC = CHARMs I/O Card,think of it as the controller/interface that manages the CHARM I/O system.<br>
>A CIOC can be associated with one or more baseplates.</b><br>
<b>• A cabinet is a large enclosure in the control room that contains equipment such as:<br>
-CIOCs<br>
-Baseplates<br>
-CHARM modules<br>
-power supplies<br>
-wiring/termination equipment<br>
-other control-system hardware</b><br>
<h2>Project Rules:-</h2><br>
1. "Keep related signals together" (For efficient and faster management)<br>
2. "Separate duty and standby equipment" (Have a backup system ready in case some equipment in 1st fails)<br>
3."Use the right CHARM" <br>
4. "Leave spare room" <br>

