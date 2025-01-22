# Prompt format is as follows
#attribute_brief

#attribute_details

#coding_labels

#prompt_instruction

#output_format

## Example
<p style="color:#45de8c">#attribute_brief</p>
Carriageway Label record a carriageway label for each section of the road to distinguish which carriageway is being coded. <br><br>

<p style="color:#45de8c">#attribute_details</p>
Undivided vs. divided carriageways. Divided (dual) carriageways are surveyed in both directions, but undivided (single) carriageway roads are recorded in one direction only, even if the traffic is two-way. What is considered divided and undivided depends on the median type and its length:
• Divided carriageways are those that physically separate opposing traffic flows by either a barrier or a wide physical median continuously* for 400m or more. (*This can include gaps in the median at intersections, but not other gaps in the median). 
• An undivided carriageway has no physical separation between opposing traffic flows or physically separates traffic for a section of less than 400m. How do I code a one-way street? One-way roads must be coded as undivided and the ‘Median type’ set to one-way.<br><br>

How do I code a service road? Service roads must be coded separately from the main carriageways. Code service roads the same way as standard roads. How do I code a bus or transit lane? If a bus or transit lane is part of the main carriageway, code it as part of the carriageway (see instructions on coding transit lanes under ‘Number of lanes’). Where there is a dedicated, separated carriageway for buses, these should be coded as divided or undivided carriageways separate from the main carriageway.

<p style="color:#45de8c">#coding_labels</p>
The codding for the Carriageway Label is as follows: 
1. Divided carriageway in one direction. 
2. Divided carriageway in the opposite direction (to carriageway in carriageway 1).
3. Undivided carriageway (in both directions or in one way)
4. Segregated motorcycle paths adjacent to the main carriageway.<br><br>

<p style="color:#45de8c">#prompt_instruction</p>
According to the provided codding details, what is the carriageway type codding for the road in the image? You should select one codding item from the codding list. <br><br>

<p style="color:#45de8c">#output_format</p>
only write the item index, no explanation needed.