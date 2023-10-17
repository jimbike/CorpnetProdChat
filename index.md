<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D3h0000067BmT',
				'Reception_Web_Chat_Test',
				'https://corpnet.my.site.com/ESWReceptionWebChatTes1697518257907',
				{
					scrt2URL: 'https://corpnet.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://corpnet.my.site.com/ESWReceptionWebChatTes1697518257907/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
