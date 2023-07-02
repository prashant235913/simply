    		{{!-- members subscribe --}}
    		{{#if @site.members_enabled}}{{#unless @member}}
    		<div class="footer-items mb-8">
    			<h3 class="mb-5 text-xl">{{t "Join me via Microsoft Teams"}}</h3>

<div class="flex items-center">
				<svg style="box-shadow: 0px 0px 8px 0px; border-radius: 8px; margin: 8px; font-weight: normal;"
					xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-label="Calendar" role="img"
					viewBox="0 0 512 512" width="70px" height="70px">
					<path d="M512 455c0 32-25 57-57 57H57c-32 0-57-25-57-57V128c0-31 25-57 57-57h398c32 0 57 26 57 57z"
						fill="#e0e7ec" />
					<path
						d="M484 0h-47c2 4 4 9 4 14a28 28 0 1 1-53-14H124c3 4 4 9 4 14A28 28 0 1 1 75 0H28C13 0 0 13 0 28v157h512V28c0-15-13-28-28-28z"
						fill="#dd2f45" />
					<g fill="#f3aab9">
						<circle cx="470" cy="142" r="14" />
						<circle cx="470" cy="100" r="14" />
						<circle cx="427" cy="142" r="14" />
						<circle cx="427" cy="100" r="14" />
						<circle cx="384" cy="142" r="14" />
						<circle cx="384" cy="100" r="14" />
					</g>
					<text x="32" y="164"
						style="fill: rgb(255, 255, 255); font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 140px;">Wed</text>
					<text x="256" y="350"
						style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 120px; text-anchor: middle;">8:00
						AM</text>
					<text x="256" y="480"
						style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 96px; text-anchor: middle;">INDIA</text>
				</svg>

    			<svg style="box-shadow: 0px 0px 8px 0px; border-radius: 8px; margin: 8px; font-weight: normal;"
    				xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-label="Calendar" role="img"
    				viewBox="0 0 512 512" width="70px" height="70px">
    				<path d="M512 455c0 32-25 57-57 57H57c-32 0-57-25-57-57V128c0-31 25-57 57-57h398c32 0 57 26 57 57z"
    					fill="#e0e7ec" />
    				<path
    					d="M484 0h-47c2 4 4 9 4 14a28 28 0 1 1-53-14H124c3 4 4 9 4 14A28 28 0 1 1 75 0H28C13 0 0 13 0 28v157h512V28c0-15-13-28-28-28z"
    					fill="#dd2f45" />
    				<g fill="#f3aab9">
    					<circle cx="470" cy="142" r="14" />
    					<circle cx="470" cy="100" r="14" />
    					<circle cx="427" cy="142" r="14" />
    					<circle cx="427" cy="100" r="14" />
    					<circle cx="384" cy="142" r="14" />
    					<circle cx="384" cy="100" r="14" />
    				</g>
    				<text x="32" y="164"
    					style="fill: rgb(255, 255, 255); font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 140px;">Tue</text>
    				<text x="256" y="350"
    					style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 120px; text-anchor: middle;">7:30
    					PM</text>
    				<text x="256" y="480"
    					style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 96px; text-anchor: middle;">Seattle</text>
    			</svg>

</div>

    			<p class="mb-4">{{t "Your email address to access the Microsoft Teams invitation."}}</p>

    			{{!-- Form subscribe --}}
    			<form class="simply-form w-64" data-members-form="subscribe">
    				<input class="footer-form-input" data-members-email type="email" placeholder="{{t " Your email address"}}"
    					aria-label="{{t " Your email address"}}" autocomplete="off" required />

    				<button class="button is-primary w-32 mt-4" type="submit">
    					<span class="button-content">Continue</span>
    					{{> "icons/loader"}}
    				</button>
    				{{!-- <p>No spam. Unsubscribe any time.</p> --}}

    				{{!-- success --}}
    				<div class="message-success p-2 rounded-md mt-4 hidden text-sm">
    					<span class="bg-success w-3 h-3 rounded-full inline-block"></span>
    					{{{t "<strong>Great!</strong> Check your inbox and click the link to confirm"}}}
    				</div>

    				{{!-- error --}}
    				<div class="message-error p-2 rounded-md mt-4 hidden text-sm">
    					<span class="bg-danger w-3 h-3 rounded-full inline-block"></span>
    					{{t "Please enter a valid email address!"}}
    				</div>
    			</form>
    		</div>
    		{{/unless}}{{/if}}




    		{{!-- if already subscribed --}}
    		{{#if @site.members_enabled}}{{#if @member}}

<div class="max-w-xs">
<h3 class="mb-5 text-xl">{{t "Join me via Microsoft Teams"}}</h3>

<a href="https://teams.microsoft.com/l/meetup-join/19%3a75832cabd9c14e298c7dcf64d546d454%40thread.skype/1683079703764?context=%7b%22Tid%22%3a%22abb54c36-485b-4cbf-a587-91295d12cef8%22%2c%22Oid%22%3a%22b6262709-c43e-4508-8315-64d6b19d0d95%22%7d">

<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px"
	y="0px" viewBox="0 0 38 38" style="enable-background:new 0 0 38 38;" xml:space="preserve">

<style type="text/css">
.st0 {
fill: #7B83EB;
}

    	.st1 {
    		opacity: 0.1;
    		enable-background: new;
    	}

    	.st2 {
    		opacity: 0.2;
    		enable-background: new;
    	}

    	.st3 {
    		fill: #5059C9;
    	}

    	.st4 {
    		fill: #4B53BC;
    	}

    	.st5 {
    		fill: #FFFFFF;
    	}

    	.st6 {
    		fill: none;
    	}
    </style>

    <g id="Teams">
    	<g id="Teams_32x" transform="translate(3.000000, 3.000000)">
    		<circle id="Oval" class="st0" cx="17" cy="6" r="4.6669998" />
    		<path id="Path" class="st1" d="M16.6669998,7H12.441l0.0209999,0.0929999v0.0079999
    		c0.007,0.0290003,0.0139999,0.0570002,0.0220003,0.086C13.1217108,9.6077375,15.5547476,11.0950832,18,10.559V8.3330002
    		C17.9978027,7.5977163,17.4022846,7.0021963,16.6669998,7L16.6669998,7z" />
    		<path id="Path_1_" class="st2" d="M15.6669998,8H12.783c0.7725716,1.6288652,2.4142056,2.6671009,4.217,2.6669998V9.3330002
    		C16.9978027,8.5977163,16.4022846,8.0021963,15.6669998,8L15.6669998,8z" />
    		<circle id="Oval_1_" class="st3" cx="27.5" cy="7.5" r="3.5" />
    		<path id="Path_2_" class="st3" d="M30.5,12h-7.8610001C22.2860909,12,22,12.2860899,22,12.6389999v8.1100006
    		c-0.0452347,2.4190674,1.6087532,4.5397263,3.9659996,5.0849991c1.4754944,0.309597,3.0119419-0.0622711,4.1825638-1.0123119
    		C31.3191872,23.8716488,31.9993038,22.4446259,32,20.9370003V13.5C32,12.6715727,31.3284264,12,30.5,12z" />
    		<path id="Path_3_" class="st0" d="M25,13.5V23c0.0020161,3.6198292-2.4283199,6.7893848-5.9246788,7.7267475
    		C15.5789623,31.6641083,11.8890305,30.135376,10.0799999,27c-0.1924124-0.3198261-0.3595858-0.6541748-0.5-1
    		C9.4490976,25.6739311,9.3388786,25.3399353,9.25,25C9.0851278,24.346077,9.0011663,23.6743851,9,23v-9.5
    		c0-0.8284273,0.6715727-1.5,1.5-1.5h13C24.3284264,12,25,12.6715727,25,13.5L25,13.5z" />
    		<path id="Path_4_" class="st2" d="M15.6669998,8H12.783c0.7725716,1.6288652,2.4142056,2.6671009,4.217,2.6669998V9.3330002
    		C16.9978027,8.5977163,16.4022846,8.0021963,15.6669998,8L15.6669998,8z" />
    		<path id="Path_5_" class="st1" d="M18,12v12.6700001c0,0.6211319-0.4330025,1.1582451-1.0400009,1.289999
    		c-0.0940762,0.0279732-0.1918621,0.0414619-0.289999,0.0401077H9.5799999C9.4490976,25.6739311,9.3388786,25.3399353,9.25,25
    		C9.0851278,24.346077,9.0011663,23.6743851,9,23v-9.5c0-0.8284273,0.6715727-1.5,1.5-1.5H18z" />
    		<path id="Path_6_" class="st2" d="M17,12v13.6700001c0.001461,0.0981369-0.0120277,0.1959229-0.0400009,0.289999
    		C16.8282452,26.5669975,16.291132,27,15.6700001,27h-5.5900002c-0.1924124-0.3198261-0.3595858-0.6541748-0.5-1
    		C9.4490976,25.6739311,9.3388786,25.3399353,9.25,25C9.0851278,24.346077,9.0011663,23.6743851,9,23v-9.5
    		c0-0.8284273,0.6715727-1.5,1.5-1.5H17z" />
    		<path id="Path_7_" class="st2" d="M17,12v11.6700001C16.9967155,24.4031734,16.4031734,24.9967155,15.6700001,25H9.25
    		C9.0851278,24.346077,9.0011663,23.6743851,9,23v-9.5c0-0.8284273,0.6715727-1.5,1.5-1.5H17z" />
    		<path id="Path_8_" class="st2" d="M10.5,12C9.6715727,12,9,12.6715727,9,13.5V23c0.0011663,0.6743851,0.0851278,1.346077,0.25,2
    		h5.4200001C15.4031734,24.9967155,15.9967146,24.4031734,16,23.6700001V12H10.5z" />
    		<path id="Rectangle" class="st4" d="M1.3329999,8h13.3339996C15.4031954,8,16,8.5968046,16,9.3330002v13.3339996
    		C16,23.4031944,15.4031954,24,14.6669998,24H1.3329999C0.5968044,24,0,23.4031944,0,22.6669998V9.3330002
    		C0,8.5968046,0.5968044,8,1.3329999,8z" />
    		<polygon id="Path_9_" class="st5" points="11.9729996,12.974 8.9899998,12.974 8.9899998,20.9939995 7.0289998,20.9939995
    		7.0289998,12.974 4.0289998,12.974 4.0289998,11 11.9729996,11 		" />
    		<rect id="Rectangle_1_" class="st6" width="32" height="32" />
    	</g>
    </g>

</svg>
</a>
</div>

<div class="flex items-center">
	<svg style="box-shadow: 0px 0px 8px 0px; border-radius: 8px; margin: 8px; font-weight: normal;"
		xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-label="Calendar" role="img"
		viewBox="0 0 512 512" width="70px" height="70px">
		<path d="M512 455c0 32-25 57-57 57H57c-32 0-57-25-57-57V128c0-31 25-57 57-57h398c32 0 57 26 57 57z"
			fill="#e0e7ec" />
		<path
			d="M484 0h-47c2 4 4 9 4 14a28 28 0 1 1-53-14H124c3 4 4 9 4 14A28 28 0 1 1 75 0H28C13 0 0 13 0 28v157h512V28c0-15-13-28-28-28z"
			fill="#dd2f45" />
		<g fill="#f3aab9">
			<circle cx="470" cy="142" r="14" />
			<circle cx="470" cy="100" r="14" />
			<circle cx="427" cy="142" r="14" />
			<circle cx="427" cy="100" r="14" />
			<circle cx="384" cy="142" r="14" />
			<circle cx="384" cy="100" r="14" />
		</g>
		<text x="32" y="164"
			style="fill: rgb(255, 255, 255); font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 140px;">Wed</text>
		<text x="256" y="350"
			style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 120px; text-anchor: middle;">8:00
			AM</text>
		<text x="256" y="480"
			style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 96px; text-anchor: middle;">INDIA</text>
	</svg>

    <svg style="box-shadow: 0px 0px 8px 0px; border-radius: 8px; margin: 8px; font-weight: normal;"
    	xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-label="Calendar" role="img"
    	viewBox="0 0 512 512" width="70px" height="70px">
    	<path d="M512 455c0 32-25 57-57 57H57c-32 0-57-25-57-57V128c0-31 25-57 57-57h398c32 0 57 26 57 57z"
    		fill="#e0e7ec" />
    	<path
    		d="M484 0h-47c2 4 4 9 4 14a28 28 0 1 1-53-14H124c3 4 4 9 4 14A28 28 0 1 1 75 0H28C13 0 0 13 0 28v157h512V28c0-15-13-28-28-28z"
    		fill="#dd2f45" />
    	<g fill="#f3aab9">
    		<circle cx="470" cy="142" r="14" />
    		<circle cx="470" cy="100" r="14" />
    		<circle cx="427" cy="142" r="14" />
    		<circle cx="427" cy="100" r="14" />
    		<circle cx="384" cy="142" r="14" />
    		<circle cx="384" cy="100" r="14" />
    	</g>
    	<text x="32" y="164"
    		style="fill: rgb(255, 255, 255); font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 140px;">Tue</text>
    	<text x="256" y="350"
    		style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 120px; text-anchor: middle;">7:30
    		PM</text>
    	<text x="256" y="480"
    		style="fill: black; font-family: -apple-system, BlinkMacSystemFont, sans-serif; font-size: 96px; text-anchor: middle;">Seattle</text>
    </svg>

</div>

<div class="flex items-center"><small>Meeting ID: 260 750 922 783</small></div>
<div class="flex items-center"><small>Passcode: KCBqUG</small></div>

<p>See you live.</p>
{{/if}}{{/if}}

extra stuff

    <section>
    	<div id="outerspace">
    	  	<div class="rocket">
    			<div>#1<!-- rocket --></div>
    			<h1>As a fresh grad, scores IAS 3rd rank in India.</h1>

  			</div>
		</div>
	</section>

    <section>
    	<div id="outerspace">
    	  	<div class="rocket">
    			<div>#2<!-- rocket --></div>
    			<h1>Quits and moves to realize the American dream.</h1>

  			</div>
		</div>
	</section>

    <section>
    	<div id="outerspace">
    	  	<div class="rocket">
    			<div>#3<!-- rocket --></div>
    			<h1>Digs out of MBA student debt<br>into a high profile career at Microsoft.</h1>

  			</div>
		</div>
	</section>

    <section>
    	<div id="outerspace">
    	  	<div class="rocket">
    			<div>#4<!-- rocket --></div>
    			<h1>Quits Microsoft to build a successful business helping people like you transform their career in the cloud.</h1>

  			</div>
		</div>
	</section>