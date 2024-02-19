<!DOCTYPE html>
<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D7Z00000053zg',
				'Test_MIAW_Queue_based_Message_Channel',
				'https://hsecovax--dev31.sandbox.my.site.com/ESWTestMIAWQueuebased1708372230006',
				{
					scrt2URL: 'https://hsecovax--dev31.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://hsecovax--dev31.sandbox.my.site.com/ESWTestMIAWQueuebased1708372230006/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
