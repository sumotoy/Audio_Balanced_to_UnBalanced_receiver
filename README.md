# Audio_Balanced_to_UnBalanced_receiver
A simple monochannel Audio Balanced to UnBalanced receiver based on rocksolid NE5532 and NE5534 but other ic's are possible, it's a simple board, designed to be easily assembled because no SMD and cheap components, the connector on the bottom can be used for wires or (as it was intended) an angled connector for mount board vertically.
Th board has a trim for change input gain.
This is the first commit and never tested (only on simulator), actually inputs are exposed to overvoltage or DC so if you plan to use in real appliances you need to add input capacitors and/or overvoltage protection extra components.
There's an OSH Park PCB you can order.<br>
![schematic](https://github.com/sumotoy/Audio_Balanced_to_UnBalanced_receiver/blob/master/schem.png)

![boardFront](https://github.com/sumotoy/Audio_Balanced_to_UnBalanced_receiver/blob/master/recFront.png)

![boardBack](https://github.com/sumotoy/Audio_Balanced_to_UnBalanced_receiver/blob/master/recBack.png)
