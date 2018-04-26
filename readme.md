## jquery.socialshare
A jQuery social sharing plugin (facebook, twitter, google+, linkedin, email, and more to come).

## Motivation
A fast way for developers to make custom social share links functional.

## Installation

Simply import the "jquery.socialshare.js" file to your project after your jQuery library has been imported.
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script src="path to your file/jquery.share.js"></script>
```

## Usage

More documentation coming soon.

Instatiate the socailshare object for your elements which will trigger the share
```
var options = {
	'targetBlank': false, //false is default, share window will be a popup
	'siteDomain' : 'github.com' //default is read from your window location
}
$('.sshare').socialshare(options);
```

Add HTML elements for sharing, with the following attributes

Twiiter
```
<a href="#" class="sshare" data-sshare="twitter" data-url="http://github.com" data-twitter-message="Insert message here">Twitter</a>
```

Facebook
```
<a href="#" class="sshare" data-sshare="facebook" data-url="http://github.com">Facebook</a>
```

Linkedin
```
<a href="#" class="sshare" data-sshare="linkedin" data-url="http://github.com" data-linkedin-title="Insert Title Here" data-linkedin-summary="Insert summary here." data-linkedin-source="Insert source here">Linkedin</a>
```

Google+
```
<a href="#" class="sshare" data-sshare="google+" data-url="http://github.com">Google+</a>
```

Email
```
<a href="#" class="sshare" data-sshare="email" data-url="http://github.com" data-email-subject="Insert email subject here" data-email-body="Insert email body here">Email</a>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License
MIT © [Sade Smith](http://sadesmith.com)