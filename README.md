# ClipperzApp

ClipperzApp is a simple Android app that acts as a shortcut to access the
Clipperz web password manager:
[https://clipperz.is/app/](https://clipperz.is/app/).

Clipperz is an «online vault and password manager that knows nothing about you
and your data.» Clipperz is a great [free and open-source project][1a]. You
can check out the [Clipperz organization][1b] on GitHub. If you use Clipperz,
you should support the project with a [donation][1c].

This app is just a [WebView][2] that visualizes the Clipperz web-app page.

## Disclaimer

While the app is very simple, and the only thing that it does is visualizing
a web page, I have to stress that this is an **UNOFFICIAL** app. I am not
affiliated with the Clipperz project in any capacity, and this app is a
personal project that I have built for my own personal use and convenience.

Seriously, let me stress the point again. I have built this app in an
afternoon following a (lovely) tutorial by Steven Sohcot on Medium:
[«Tutorial for displaying a website in an Andriod app using a WebView component.»][3]

I have written it because I wanted to experiment with Android apps, and I I
needed a shortcut to Clipperz and a native app so that my phone's fingerprint
password manager recognizes it and lets me use my fingerprint for
authentication. I am also aware that biometric authentication comes with
[its own set of problems][4], so if this is a concern for you, you should
stick to using your passphrase and the official Clipperz website.

I have practically zero knowledge of Android app development, and I can not
guarantee that this app is either free of bugs or as secure to use as the
Clipperz official website.

## Installing

To install the app on your device, go to the [releases][4] page and download
the latest version of the `.apk.`  You should enable the possibility to
install apps from _"Unknown Sources"_ in your Settings. This could be a
security risk in principle; you should consider disabling the option when you
are done with installing the app.

## License

ClipperzApp is released under the GPL version 3 or any later version.

ClipperzApp - a simple Android app that acts as a shortcut to access the
Clipperz web password manager.
Copyright (C) 2019 Cristian Consonni

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.

## Contacts

If you have questions, drop me an e-mail at `cristian (at) balist (dot) es`

[1a]: https://clipperz.is/open_source/
[1b]: https://github.com/clipperz
[1c]: https://clipperz.is/donations/
[2]: https://developer.android.com/reference/android/webkit/WebView
[3]: https://medium.com/@stevesohcot/andriod-studio-webview-tutorial-4651701d7d1a
[4]: https://theconversation.com/fingerprint-and-face-scanners-arent-as-secure-as-we-think-they-are-112414
[5]: https://github.com/CristianCantoro/ClipperzApp/releases
