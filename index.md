<!DOCTYPE html>
<html>
<body>


 <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
            embeddedservice_bootstrap.settings.prepopulatedPrechatFields = {
                Chat_to_Case_Config__c: "Prechat_English_Bot",
                Chat_Section__c: "Covid"
            }; //Sets the auto-population of pre-chat form fields
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			embeddedservice_bootstrap.init(
				'00D7Z00000053zg',
				'MIAW_for_Bot_on_Git',
				'https://hsecovax--dev31.sandbox.my.site.com/ESWMIAWforBotonGit1707755430647',
				{
					scrt2URL: 'https://hsecovax--dev31.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://hsecovax--dev31.sandbox.my.site.com/ESWMIAWforBotonGit1707755430647/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
