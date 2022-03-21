# topbarCSS
top bar css gnome 
_______________________________________________________________________________
add this to the panel section in your gnome-shell.cs:

border-radius: 9px;
  height: 43px;
  margin-top: 19px;
  margin-right: 250px;
  margin-left: 250px;
  
  
  _____________________________________________________________________________
In effect;

/* Top Bar */
#panel {
  background-color: #131020;
  font-weight: bold;
  height: 32px;
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
