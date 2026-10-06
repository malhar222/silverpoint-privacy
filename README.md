# Silverpoint — Privacy Policy & Support site

Static site for the Silverpoint iOS app (privacy policy and support pages).

**Don't edit the HTML by hand.** It's generated from the app's bundled policy
(`CreatorCRM/Resources/PrivacyPolicy.md` in the app repository) so the website
always matches the in-app copy:

```sh
python3 Scripts/build_privacy_site.py ../silverpoint-privacy
```

Pages:
- `privacy/` — Privacy Policy (App Store Connect "Privacy Policy URL")
- `support/` — Support (App Store Connect "Support URL")

This repository is private until launch. Publishing it with GitHub Pages
(free plan) requires making it public; see the app repository README.
