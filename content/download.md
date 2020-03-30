+++

date = "2017-09-09T13:41:00+01:00"
title = "Download the lastest version of ZPLDesigner"
author = "Cédric HUMBERT"
draft = false
type = "page"
[menu]
     [menu.main]
        name = "DOWNLOAD"
        weight = 4
        identifier = "Download"
+++

<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.9</h3>
		<h5>2020-03-30</h5>
		<h4>New features</h4>
		<lu>
			<li>Create your own "Label Format" in In, Mm or Cm.</li>
	    	<li>Keep the last selected "Label Format" instead of resetting to "None".</p></li>
		<li>Keep the last selected "Zoom" instead of resetting to "100%".</li>
                <li>Keep "ZPL Command" panel width on fullscreen.</li>			
		</lu>
	    	<br>
	    	<h4>Bug correction</h4>
		<lu><li>Assistant generate wrong ZPL code for some command.</li>
                <li>Preferences/Variable End string populated false.</li>			
		</lu>
		<br>
	    	 <h4>Other</h4>
	<p> Thanks to Stewe W., Ralf and Alexandre D. for their bug reports and suggestions</p> 
		<br>
        <p><a href="https://sourceforge.net/p/zpldesigner/"><img alt="Download ZPLDesigner" src="https://sourceforge.net/sflogo.php?type=17&group_id=3020659" width=200></a>
		<a href="https://sourceforge.net/projects/zpldesigner/files/latest/download"><img alt="Download ZPLDesigner" src="https://img.shields.io/sourceforge/dt/zpldesigner.svg" ></a></p>
	    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
<input type="hidden" name="cmd" value="_donations" />
<input type="hidden" name="business" value="4HZKLD4GF734Q" />
<input type="hidden" name="item_name" value="ZPLDesigner" />
<input type="hidden" name="currency_code" value="EUR" />
<input type="image" src="https://www.paypalobjects.com/en_US/FR/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_FR/i/scr/pixel.gif" width="1" height="1" />
</form>

    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
	   <img class="feature-img" src="/img/0.9_download.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>



<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.8</h3>
		<h5>2019-11-30</h5>
		<h4>New features</h4>
		<lu>
		<li>Preview windows can be unpin on another windows/screen.</li>
	    	<li>Print on local Zebra (USB, LPT1, COM) with Labelary.</li>
		<li>Add ^CF, ^CW, ^FL, ^HT and ^LF command.</li>
		<li>New desgin for ZPL Assistant.</li>
		</lu>
	    	<br>
	    	<h4>Bug correction</h4>
		<lu><li>^B4 command parameters was wrong.</li>
		</lu>
		<br>
        <p><a href="https://sourceforge.net/p/zpldesigner/"><img alt="Download ZPLDesigner" src="https://sourceforge.net/sflogo.php?type=17&group_id=3020659" width=200></a>
		<a href="https://sourceforge.net/projects/zpldesigner/files/latest/download"><img alt="Download ZPLDesigner" src="https://img.shields.io/sourceforge/dt/zpldesigner.svg" ></a></p>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
	   <img class="feature-img" src="/img/assistant2.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>


<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.7</h3>
		<h5>2019-01-10</h5>
		<h4>New features</h4>
		<lu>
		<li>Variables substitution feature.</li>
	    <li>Add status bar.</li>
		<li>Add <i>? / Help</i> menu.</li>
		<li>General performance optimisation.</li>
		</lu>
		<br>
		<h4>Bug correction</h4>
		<lu><li>Out of memory message when preview from a Zebra printer.</li>
		<li>ZPL Help for a command was sometimes updated when not needed.</li>
		</lu>	
		<br>
        <p><a href="https://sourceforge.net/p/zpldesigner/"><img alt="Download ZPLDesigner" src="https://sourceforge.net/sflogo.php?type=17&group_id=3020659" width=200></a>
		<a href="https://sourceforge.net/projects/zpldesigner/files/latest/download"><img alt="Download ZPLDesigner" src="https://img.shields.io/sourceforge/dt/zpldesigner.svg" ></a></p>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
	   <img class="feature-img" src="/img/0.7.gif">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>

<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.6</h3>
		<h5>2018-12-10</h5>
		<h4>New features</h4>
		<lu>
	    <li>Label size can now be customized using cm, mm or inch with <a href="http://www.labelary.com" target="_blank">labelary.com</a> or a local zebra.</li>
		<li>Support <i>Open with</i> from Windows explorer right click.</li>
		<li>Autocrop label image.</li>
		<li>Add <i>File/Preferences</i> menu to customize ZPL code editor (font, size, color and variable start/stop string).</li>
		</lu>
		<br>
		<h4>Bug correction</h4>
		<lu><li>Label rotation work now correctly when submiting a previously rendered ZPL code.</li>
		<li>^B7 assistant run now correctly.</li>
		<li>Label size was sometime not correctly displayed when rendering from a local zebra.</li>
		<li>Error message from <a href="http://www.labelary.com" target="_blank">labelary.com</a> are now fully displayed.</li>
		</lu>	
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/0.6.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>
<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.5.1</h3>
		<h5>2018-11-18</h5>
		<h4>New features</h4>
		<lu>
	    <li>Add ZPL commands ^ML, ^MD, ^MN and ^MT.</li>
		<li>Support ZPL code that doesn't generate any labels (example: <i>^XA^FOI^XZ</i>).</li>
		</lu>
		<br>
		<h4>Bug correction</h4>
		<lu><li>Label detection (start with <i>^XA</i>, end with <i>^XZ</i>) work now correctly.</li>
		</lu>	
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/no_label.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>
<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.5</h3>
		<h5>2018-10-26</h5>
		<h4>New features</h4>
		<lu>
		<li>Support several labels on code editor.</li>
        <li>Choose your ZPL render engine: a local Zebra printer or <a href="http://www.labelary.com" target="_blank">labelary.com</a> webservice.</li>
		</lu>
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/0.5.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>
<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.4</h3>
		<h5>2018-09-12</h5>
		<h4>New features</h4>
		<lu>
        <li>Check for update at startup.</li>
		<li>ZPL command parameters are now display more clearly.</li>
		<li>ZPL command can now be sorted by name or category (Barcode, Text, Graphic,...).</li>
		<li>A search box is now available on ZPL command list.</li>
		<li>An assistant will help you to use ZPL command.</li>
		</lu>
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/zplAssistant.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>
<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.3</h3>
		<h5>2018-08-16</h5>
		<h4>New features</h4>
		<lu>
        <li>Show ZPL command help depending on carret position.</li>
		<li>Convert image to ZPL code by using Insert / Image menu.</li>
		</lu>
		<br>
		<h4>Bug correction</h4>
		<lu><li>Http 400 error when using character '=' in ZPL code</li>
		</lu>		
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/0.3.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>

<div class="gray-box">
  <div class="row gutters">
    <div class="col col-6 item">
        <h3 class="boxtitle">Release version 0.2</h3>
		<h5>2017-02-06</h5>
		<h4>Initial Release</h4>
		<br>
    </div>
    <div class="col col-6 item">
      <div style="width: 100%; text-align: right;">
        <img class="feature-img" src="/img/0.3.png">
      </div>
    </div>
  </div>
</div>

<div class="empty-sep"></div>



