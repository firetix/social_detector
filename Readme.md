# social_detector

Inspired by http://www.tomanthony.co.uk/blog/detect-visitor-social-networks/

## Usage

Simplest usage

```html
<script src="social_detector.js"></script>
<script>
	social_detector({
		facebook: 'facebook_app_id'
	});
</script>
```
## Options

```
facebook - Facebook appId. Required if you want detect login status for facebook.com
ga - Google analytics site's ID. If you set it, it will load GA script, set `_setAccount` and `_trackPageview`.
callback - Callback function. Set it if you don't want to report to GA, but process it manually
```
## Platform supported

```
facebook, twitter, tumblr, google, google_plus
```
## TODO

  - add detection of another social networks
