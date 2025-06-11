<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
	</head>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			embeddedservice_bootstrap.settings.smallCompanyLogoImgURL = "/images/klogo.jpg";
			embeddedservice_bootstrap.init(
				'00Ddu000007a7wb',
				'Salesforce_MIAW_Demo',
				'https://kaplaninternational--nikunjdev.sandbox.my.site.com/ESWSalesforceMIAWDemo1749452853283',
				{
					scrt2URL: 'https://kaplaninternational--nikunjdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://kaplaninternational--nikunjdev.sandbox.my.site.com/ESWSalesforceMIAWDemo1749452853283/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
