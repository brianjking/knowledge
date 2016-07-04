WordPress
================

Hide Divi Theme details in theme footer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: css

	#footer-info {display:none;}

Style Contact Form7 to match Divi Theme Default Styles
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: css

	.wpcf7-text, .wpcf7-textarea, .wpcf7-captchar {
	background-color: #eee !important;
	border: none !important;
	width: 100% !important;
	 -moz-border-radius: 0 !important;
	 -webkit-border-radius: 0 !important;
	 border-radius: 0 !important;
	font-size: 14px;
	color: #999 !important;
	padding: 16px !important;
	 -moz-box-sizing: border-box;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	}
	.wpcf7-submit {
	color: #2EA3F2 !important;
	margin: 8px auto 0;
	cursor: pointer;
	font-size: 20px;
	font-weight: 500;
	 -moz-border-radius: 3px;
	 -webkit-border-radius: 3px;
	 border-radius: 3px;
	padding: 6px 20px;
	line-height: 1.7em;
	background: transparent;
	border: 2px solid;
	 -webkit-font-smoothing: antialiased;
	 -moz-osx-font-smoothing: grayscale;
	 -moz-transition: all 0.2s;
	 -webkit-transition: all 0.2s;
	 transition: all 0.2s;
	}
	.wpcf7-submit:hover { 
	background-color: #eee; 
	border-color:#eee; 
	padding: 6px 20px !important; 
	}

Style Ninja Forms to Match Divi Default Styles
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: css

	/* START - Divi Ninja Form Styling */
	.ninja-forms-form-wrap input, select{
	background-color: #eee;
	border: none;
	-moz-border-radius: 0;
	-webkit-border-radius: 0;
	border-radius: 0;
	font-size: 16px;
	color: #999 ;
	padding: 16px;
	-moz-box-sizing: border-box;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	}
	.ninja-forms-form-wrap select{
	width: 100% !important;
	height: 50px !important;
	border-radius: 0;
	-moz-border-radius: 0;
	-webkit-border-radius: 0;
	}
	.ninja-forms-required-items {
	display: none;
	}
	textarea.ninja-forms-field{
	background-color: #eee;
	border: none;
	-moz-border-radius: 0;
	-webkit-border-radius: 0;
	border-radius: 0;
	font-size: 16px;
	color: #999 ;
	padding: 16px;
	-moz-box-sizing: border-box;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	}
	*[id^='nf_submit_'] > .ninja-forms-field {
	float: right;
	width: 150px;
	color: #1e73be !important;
	margin: 8px auto 0;
	cursor: pointer;
	font-size: 20px;
	font-weight: 500;
	-moz-border-radius: 3px;
	-webkit-border-radius: 3px;
	border-radius: 3px;
	padding: 6px 20px;
	line-height: 1.7em;
	background: transparent;
	border: 2px solid;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	-moz-transition: all 0.2s;
	-webkit-transition: all 0.2s;
	transition: all 0.2s;
	}
	*[id^='nf_submit_'] > .ninja-forms-field:hover {
	background-color: #eee;
	border-color:#eee;
	padding: 6px 20px !important;
	width: 170px;
	}
	/* END - Divi Ninja Form Styling */
