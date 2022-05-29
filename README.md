# topbarCSS

read in raw format for proper formatting 

top bar css gnome 
_______________________________________________________________________________
add this to the panel section in your gnome-shell.cs with a text editor of your choice:

border-radius: 9px;
  height: 43px;
  margin-top: 19px;
  margin-right: 250px;
  margin-left: 250px;
  
  (you can change the values but i find this looks best)
  _____________________________________________________________________________
In effect;

/* Top Bar */
#panel {
  background-color: #131020;
  font-weight: bold;
  color: rgba(217, 224, 238, 0.7);
  font-feature-settings: "tnum";
  transition-duration: 250ms;
  font-size: 10pt;
  border-radius: 9px;
  height: 43px;
  margin-top: 19px;
  margin-right: 250px;
  margin-left: 250px;
}

should work with any theme, make sure to disable blur my shell on the panel if you are using it, as it breaks some stuff usually

**Works on Gnome 42**
