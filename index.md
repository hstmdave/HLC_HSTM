<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWL000002dfgT',
				'HLC_Messaging',
				'https://healthstream--hstm.sandbox.my.site.com/ESWHLCMessaging1741632889089',
				{
					scrt2URL: 'https://healthstream--hstm.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://healthstream--hstm.sandbox.my.site.com/ESWHLCMessaging1741632889089/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
