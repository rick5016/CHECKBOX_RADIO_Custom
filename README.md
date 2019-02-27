personalized checkbox and Radio button :
- with PNG : http://rick5016.net/projets/CHECKBOX_RADIO_Custom/with_PNG/
- with SVG : http://rick5016.net/projets/CHECKBOX_RADIO_Custom/with_SVG/ (SVG used : http://rick5016.net/projets/CHECKBOX_RADIO_Custom/with_SVG/icons_backup/)

TODO :
- delete picture or svg for uncheck, do that in css : 
border: 2px solid;
content: "";
height: 40px;
left: 0;
position: absolute;
top: 0;
width: 40px;
border-radius: 5px;
- do picture/svg for check (without border) and add that with after selector
- Add border for focus
tips : input:focus + label::before {
    box-shadow: 0 0 0 3px red;
    outline: 3px solid transparent; /* For Windows high contrast mode. */
} (border-radius for radio)
