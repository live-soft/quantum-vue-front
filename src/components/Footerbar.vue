<template>
	<div class="footer-copyright teal accent-4">
		<div class="container">
			<div class="row">
				<div class="col s12 l10 footer-text">
					© 2018 - {{ new Date().getFullYear() }} Quantum PHP Framework
				</div>
				<div class="col s12 l2 footer-text">
					<a href="https://quantum.softberg.org" target="_blank" class="white-text">{{ $t('message.learn_more') }}</a>
				</div>
			</div>
		</div>
	</div>
</template>