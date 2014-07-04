<div class="row-fluid">
	<div class="span12">
		<ul class="breadcrumb">
  			<li><a href="http://docs.pagelines.com/">Docs</a> <span class="divider">/</span></li>
  			<li><a href="http://docs.pagelines.com/getting-started">Getting Started</a> <span class="divider">/</span></li>
  			<li class="active">Demo Content</li>
		</ul>
	</div>
</div>

# Recreating The Demo #

</p>We are going to import some data to recreate the demo for DMS. You can see the current demo by clicking <a target="_blank"  href="http://themes.pagelines.com/dms/?dobar=1">here</a>.<br />
At the end of this mini tutorial you should have a site looking almost exactly the same making it easier to see how all the cool stuff in DMS works!</p>
<div class="bs-callout bs-callout-info">
	<h4>Plugins needed</h4>
	<p>To fully recreate the demo content you will need to <a target="_blank" href="https://codex.wordpress.org/Managing_Plugins"><strong>install</strong></a> and activate a couple of plugins.
		<ul>
			<li><a target="_blank" href="http://wordpress.org/plugins/woocommerce/">WordPress Importer</a> (needed) This imports all the posts/pages and media needed to recreate the demo.</li>
			<li><a target="_blank" href="http://wordpress.org/plugins/wordpress-importer/">Woocommerce</a> (optional) The excellent ecommerce solution for WordPress, not strictly needed, but if you plan on selling products on your site you can check out what it will look like with the demo data</li>
		</ul>
	</p>
</div>

<h3>Lets get started!</h3>
<p>Now we have the plugins in place its time to get the data imported into your install of WordPress. You will need to download the demo data. The following zips will contain the WordPress XML file and the PageLines JSON files.</p>
<h4>The Demo Content</h4>
<ul>
	<li><a title="Download DMS Demo Content" href="http://themes.pagelines.com/configs/demo-dms.zip">PageLines DMS</a></li>
	<li><a title="Download PinsPro Demo Content" href="http://themes.pagelines.com/configs/demo-pinspro.zip">PinsPro</a></li>
</ul>
<p>Don't forget to unzip the demo data before proceeding</p> 
<h4>Step 1: Import the WordPress Data</h4>
<p>
	<ol>
		<li>In the WordPress menu, click on Tools and Import. You will be presented with a series of importer tools, at the bottom you will see WordPress, thats the one you installed, click that.</li>
		<li>You should see the WordPress Import page with a <strong>'Choose File'</strong> dialog, click the button and navigate to the <strong>xml</strong> file contained in the zip file you downloaded above.</li>
		</li>Now click <strong>'Upload File and Import'</strong></li>
		<li>The importer will now ask you if you want to assign users or create your own. Its safe to just let it do what it wants here, dont worry the user 'Ray' will be created with a random password</li>
		<li>Check the box that says <strong>'Download and import file attachments'</strong> and click <strong>'Submit'</strong></li>
	</ol>
At this point WordPress will download all the media attachments from the demo and import them into your site, takes a few seconds or a couple of minutes depending on the bandwidth available.
</p>
<h4>Step 2: Set Reading Options</h4>
<p>By default WordPress will display your latest posts on the front page of the site, the demo uses a static page and a separate blog page, so lets set that up now.
	<ol>
		<li>Under WordPress Admin, click on Settings and Reading. Here you will be able to setup how the front page of your site is handled.</li>
		<li>Select <strong>'A static Page'</strong> in the radio controls.</li>
		<li>In the Front Page dropdown select <strong>'PageLines DMS Demo - Drag and Drop WP Framework'</strong>, its towards the bottom of the list.</li>
		<li>In the Posts Page dropdown select <strong>'Blog'</strong></li>
	</ol>
</p>
<h4>Step 3: Importing the DMS Data</h4>
<p>The last step is always the easiest!
	<ol>
		<li>If you haven't already done it go ahead and activate DMS and make your way to the frontend of your site</li>
		<li>In the DMS editor at the bottom of your page, click on <strong>'Site Settings'</strong> then <strong>'Import + Export'</strong></li>
		<li>On the right you will see a green button <strong>'SELECT CONFIG FILE(.JSON)'</strong> click it and navigate to the pl-config file contained in the zip you downloaded.</li>
		<li>There will be a slight pause, a refresh and then you should be greeted with the DMS demo in all its glory!</li>
	</ol>
Congrats, you made it! If you have any issues with importing this demo content let us know by posting in the forum or emailing the support desk!<br /><br /> - Simon
</p>