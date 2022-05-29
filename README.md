# topbarCSS

read in raw format for proper formatting 

top bar css gnome 
_______________________________________________________________________________
add this to the panel section in your gnome-shell.css with a text editor of your choice:

border-radius: 9px;
  height: 43px;
  margin-top: 19px;
  margin-right: 250px;
  margin-left: 250px;
  margin: 5px 5px;
  
  (you can change the values but i find this looks best)
  _____________________________________________________________________________
In effect;

/* Top Bar */
#panel {
  background-color: rgba(42, 40, 39, 0.9);
  font-weight: bold;
  height: 43px;
  color: rgba(221, 199, 161, 1);
  font-feature-settings: 'tnum';
  transition-duration: 250ms;
  font-size: 10.5pt;
  margin: 5px 5px;
  margin-top: 19px;
  margin-right: 250px;
  margin-left: 250px;
  border: 2px solid rgba(221, 199, 161, 0.5);
  border-radius: 19px;
}


should work with any theme, make sure to disable blur my shell on the panel if you are using it, as it breaks some stuff usually, (haven't found a work around to make the panel blurred sadly.)

**Works on Gnome 42**
