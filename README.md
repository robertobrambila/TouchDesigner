# TouchDesigner
Please feel free to use, abuse and share these components/project files in any way you see fit. 

### hex_rgb_constant1
(TD v099) Converts hex values to normalized rgb (0-1) as TD currently only accepts those or hsv for color values. Set the value in the component's OPTIONS page. Outputs a Constant TOP as well as a CHOP with red, green and blue channels (e.g. connect a Select CHOP to it's Out to read the three channels). 


### glsl_transition
(TD v099) Ported select transitions from GL-Transitions.com. Requires a TO and FROM TOP as inputs. PROGRESS value (0-1) is a float number for the transition progress value. TRANSITION drop down menu is used to select the GLSL transition type. For select transitions, further adjustable parameters exist within the glsl_transitions base so make sure to dive within that OP if you want to make refinements.
