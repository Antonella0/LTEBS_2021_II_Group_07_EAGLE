# LTEBS_2021_II_Group_07_EAGLE
<h3> Group_07: Buquicchio Antonella, Di Liddo Mauro </h3>

<p> This folder contains all the files required for the first assignment. In particular you can find:
<u>
<li> The Library with the new components, TMUX1208 and TCA9546A
<li> The Schematic
<li> The Board
<li> The Design rules
<li> gitignore file </li>
</p>

<h3> Library: Group_07_Library.lbr </h3>
<p> In the library file are contained the two new components which are used in the schematic and in the board. For each device is present the symbol, the footprint and a
briefly description of the device itself. All the information are extracted from the datasheets of Texas Instruments:
<li> TMUX1208: the available package is QFN-16
<li> TCA9546A: the available package is TSSOP-16 </li>
</p>

<p> <b>Note_1</b>: In the TMUX1208, the association between pins of the symbol and pads of the footprint follows the QFN-16 one.</p>

<p> <b>Note_2</b>: The pads of the two components are realized with a rectangular shape without any roundness at the corners. </p>

</p>
<p> The graphical pins disposition of the TMUX1208 and TCA9546A is reorganized with respect to the one provided by the datasheets in order 
to allow an easier connection with the other components in the schematic.
</p>

</p>
<p> In addition to our library, we have used the SparkFun Library (https://github.com/sparkfun/SparkFun-Eagle-Libraries) and the CY8CKIT-059 Library 
(https://github.com/dado93/Cypress-Eagle). </p>

<h3>Schematic: Group_07.sch </h3>
<p> We have created the schematic starting from the given one and the list of components. It is arranged in one page.</p>

<h3>Board: Group_07.brd </h3>
<p> All the components are organized in the top layer. We have used traces width of 10 mils as requested with the exception of the TMUX1208 traces: indeed, the pads 
are very closed each others and, in order to respect the clearance requirements, we have decided to use 8 mils traces. 
</p>

<h3>Design Rules: Group_07.dru </h3>
<p>In order to decide the design rules, we have refered to the requirements of MDsrl (https://www.mdsrl.it/mddesignrules.html).
</p>




