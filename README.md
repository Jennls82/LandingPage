<html>
<head><!-- Latest compiled and minified CSS -->
	<link crossorigin="anonymous" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" rel="stylesheet"/>
	<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css" rel="stylesheet"/>
	<link rel="stylesheet" id="sparkling-fonts-css" href="//fonts.googleapis.com/css?family=Open+Sans%3A400italic%2C400%2C600%2C700%7CRoboto+Slab%3A400%2C300%2C700&amp;ver=4.3.1" type="text/css" media="all">
	<style type="text/css">/* BEGIN MAFORM Style Overrides */
	body form.maForm {
		padding: 20px;
	}

	body form.maForm label {
		font-weight: normal;
	}

	body form.maForm input {
		height: 37px;
		width: 100%;
		margin-top: 3px;
		background-color: #fafafa;
		font-size: 14px;
	}

	body form.maForm input[type="radio"] {
		height: 17px;
		margin: 2px 7px 2px 4px;
	}

	body form.maForm input[type="checkbox"] {
		float: none;
		position: static;
		opacity: 1;
	}

	body form.maForm select {
		width: 100%;
		height: 39px;
	}

	form.maForm textarea {
		width: 100%;
	}

	body form.maForm .maFormElement:last-of-type {
		text-align: center;
	}

	body form.maForm button {
		font-size: 14px;
		text-shadow: none;
		padding: 10px 15px;
		color: #fff;
		font-weight: 400;
		border: none;
		background-color: #0078e7;
		background-image: none;
		width: 100% !important;
		text-transform: uppercase;
	}

	body form.maForm button:hover {
		border-width: 2px;
		background-color: #ffffff;
		color:#0078e7;
	}

	/* END MAFORM Style Overrides */
	.stripeBlue {
		background-color: #0078e7;
		color: #ffffff;
	}

	.form_container {
		background-color: #ffffff;
		color: black;
		border-radius: 10px;
	}

	body {
		font-family: 'Open Sans', sans-serif;
	}
	</style>
	<title>Landing Page</title>
</head>
<body>
<div class="container-fluid">
	<div class="row">
		<div class="col-sm-12">
			<!----------------------------Add your logo by changing the img attribute src to your image's absolute path, the width attribute can be changed as needed-->
			<div id="logo" style="padding: 10px;">
				<img src="https://s3.amazonaws.com/ma-assets/5/images/your-logo-here-27.png" width="75"/>
			</div>
		</div>
	</div>
	<div class="row stripeBlue" style="padding: 20px;">
		<div class="col-sm-8">
			<!------------------------------Personalize this section by changing the text in the h1 tag below-->
			<h1>Add a tag line for your business here
			</h1>
			<p style="text-align: left; padding-top: 20px; padding-bottom: 20px;">
				<!------------------------------Personalize this section by changing the text in the p tag below-->
				Add content to generate interest in what you have to offer
			</p>
			<!----------------------------Add an image by changing the img attributes for alt, src, and title to your own content-->
			<div class="heroImage" style="padding: 20px;">
				<img alt="Screenshot: Net-Results software" class="vc_single_image-img " height="auto" src="https://dxzzmu04exx2j.cloudfront.net/wp-content/uploads/2015/08/showcase-macbook-ipad-iphone-900x406.png"
					 title="Net-Results Dashboards" width="100%" style="padding-left: 20px; padding-right: 20px;"/>
			</div>
		</div>
		<div class="col-sm-4">
			<div class="form_container">
				<div class="form head">
					<!----------------------Personalize the form CTA by changing the text in the h3 tag below-->
					<h3 style="text-align: center; padding: 20px 0px 0px 0px;">Your CTA
					</h3>
				</div>
				<!--********************************** how should this be presented w/out a live form? ***********************************************-->
				<!---------------------This is where the form is specified and called to the page, to change the form the id variable must be changed to the formId you want to call-->
				<div class="MAform" id="MAform-ed6061a0-e365-4279-b385-bb553897559e" style="margin-top: -25px;">
					<script type="text/javascript">(function () {
						var $__MAForm;
						($__MAForm = function () {
							if (typeof($__MA) == 'undefined') {
								return window.setTimeout($__MAForm, 50);
							} else {
								$__MA.addMAForm('ed6061a0-e365-4279-b385-bb553897559e', 'forms.net-results.com');
							}
						})();
					})();
					</script>
				</div>
			</div>
		</div>
	</div>
	<div class="row">
		<div class="col-xs-12" style=" padding: 20px;">
			<!----------------------------------Personalize this section by changing the text in the h1 and h4 tags-->
			<h1 style="text-align: center;">Add a selling point or benefit about your business
			</h1>
			<h4 style="text-align: center; margin: 20px;">content to support point or benefit
			</h4>
		</div>
	</div>
	<div class="row" style="margin-bottom: 50px;">
		<div class="col-xs-12 col-sm-4">
			<div class="three_x_one_benefit_wrapper">
				<div class="three_x_one_benefit_image text-center">
					<div class="benefit_x_icon_container round_image" style="background-color: #ffffff; border-width: 0; border-color: #f6f6f6;">
						<!--------------------------change icons using the library for font awesome https://fortawesome.github.io/Font-Awesome/icons/-->
						<i class="fa benefit_x_icon fa fa-gears" style="color: #0078e7; font-size: 100px; margin-top: 40px; margin-bottom: 20px;"></i>
					</div>
				</div>
				<div class="three_x_one_benefit_heading text-center">
					<!----------------------------------Personalize this section by changing the text in the h3 tags-->
					<h3>business benefit (e.g.: features of business)
					</h3>
				</div>
				<!----------------------------------Personalize this section by changing the text in tag below-->
				<div class="three_x_one_benefit_description text-center">a sentence with
					detailed information on this benefit
					<br>
					more information if needed
				</div>
			</div>
		</div>
		<div class="col-xs-12 col-sm-4">
			<div class="three_x_one_benefit_wrapper">
				<div class="three_x_one_benefit_image text-center">
					<div class="benefit_x_icon_container round_image" style="background-color: #ffffff; border: 0 #f6f6f6; font-size:50px; margin: 20px;">
						<!--------------------------change icons using the library for font awesome https://fortawesome.github.io/Font-Awesome/icons/-->
						<i class="fa benefit_x_icon fa fa-users" style="color: #0078e7; font-size: 100px; margin: 20px;"></i>
					</div>
				</div>
				<div class="three_x_one_benefit_heading text-center">
					<!----------------------------------Personalize this section by changing the text in the h3 tags-->
					<h3>business benefit (e.g.: support team information)
					</h3>
				</div>
				<!----------------------------------Personalize this section by changing the text in tag below-->
				<div class="three_x_one_benefit_description text-center">a sentence with detailed information on this
					benefit
					<br>
					more information if needed
				</div>
			</div>
		</div>
		<div class="col-xs-12 col-sm-4">
			<div class="three_x_one_benefit_wrapper">
				<div class="three_x_one_benefit_image text-center">
					<div class="benefit_x_icon_container round_image" style=" background-color: #ffffff; border: 0 #f6f6f6;font-size:50px; margin: 20px;">
						<!--------------------------change icons using the library for font awesome https://fortawesome.github.io/Font-Awesome/icons/-->
						<i class="fa benefit_x_icon fa fa-usd" style="color: #0078e7; font-size: 100px; margin: 20px;"></i>
					</div>
				</div>
				<div class="three_x_one_benefit_heading text-center">
					<!----------------------------------Personalize this section by changing the text in the h3 tags-->
					<h3>business benefit (e.g.: product pricing)
					</h3>
				</div>
				<!----------------------------------Personalize this section by changing the text in tag below-->
				<div class="three_x_one_benefit_description text-center">a sentence with detailed information on this
					benefit
					<br>
					more information if needed
				</div>
			</div>
		</div>
	</div>
	<div class="row stripeBlue">
		<div class="col-xs-12">
			<div class="quote" style="padding:60px;">
				<p style="text-align: center; font-size: 1.3em; padding-top: 0;padding-right: 0;padding-left: 0;padding-bottom: 0;">
					<span style="font-family:monospace,serif,sans serif; font-size:2em; line-height:0; vertical-align:middle">&ldquo;</span>
					<!---------------------------Add a quote by replacing the text below-->
					Quote about how amazing your business
					is<span style="font-family:monospace,serif,sans serif; font-size:2em; line-height:0; vertical-align:middle">&rdquo; </span>
				</p>
				<p style="text-align: right; padding: 20px;">&ndash;
					<!--------------------------Credit the quote by changing the text below-->
					Happy Customer
				</p>
			</div>
		</div>
	</div>
	<div class="row" style="text-align: center; background-color: #222; padding: 75px; color: #bbb;">
		<div class="col-sm-12">
			<!----------------------------Add your logo by changing the attribute src to you image path, the width attribute can be changed as needed-->
			<a href="/" title="title here"><img src="https://s3.amazonaws.com/ma-assets/5/images/your-logo-here-27.png" width="50px"/></a>
		</div>
		<div class="copyright col-sm-12" style="margin-top: 10px;">
			<!----------------------------------make the icons link to your social media by changing the <a> tag's hrefs to the appropriate paths-->
			<a href="https://twitter.com/" target="_blank"><i class="fa fa-twitter"></i></a>
			<span class="nav-links-divider"> / </span>
			<a href="https://www.linkedin.com/company/" target="_blank"><i class="fa fa-linkedin"></i></a>
			<span class="nav-links-divider"> / </span>
			<a href="http://www./facebook" target="_blank"><i class="fa fa-facebook"></i></a>
			<span class="nav-links-divider"> / </span>
			<a href="http://google.com/" target="_blank"><i class="fa fa-google-plus"></i></a>
		</div>
		<!----------------------------------Personalize this section by adding you address and phone number-->
		<div class="copyright col-sm-12">123 Main Street<span class="nav-links-divider"> / </span>Suite
			#<span class="nav-links-divider"> / </span>Anytown, USA
			80202<span class="nav-links-divider"> / </span>USA<span class="nav-links-divider"> / </span><a href="tel:">+1
				(555) 555-5555</a>
		</div>
		<div class="copyright col-sm-12">
			<!----------------------------------Add you copyright here-->
			&copy; 2016 Your Copyright Here
		</div>
	</div>
</div>
</body>
</html>
