<html title="Salesforce MIAW Live Chat Demo">
	<head>
		<meta name="viewport" content="img-src 'self' width=device-width, initial-scale=1, minimum-scale=1">
	</head>
	<style>
		.container-lg {dislay : none}
	</style>
<body>
	<h2> Salesforce Messaging for In App and Web Demo </h2>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US';
			embeddedservice_bootstrap.init(
				'00Ddu000007a7wb',
				'MIAW_Live_Chat',
				'https://kaplaninternational--nikunjdev.sandbox.my.site.com/ESWMIAWLiveChat1749665278872',
				{
					scrt2URL: 'https://kaplaninternational--nikunjdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
	
<script type='text/javascript' src='https://kaplaninternational--nikunjdev.sandbox.my.site.com/ESWMIAWLiveChat1749665278872/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'>
</script>
</body>
</html>
