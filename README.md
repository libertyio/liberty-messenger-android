# Liberty Messenger

**Send and receive SMS organized into favorites, contacts, and recents.**

<img alt="Logo" src="app_icon_96x96.png" width="96"/>

## Overview

[Liberty Messenger](https://github.com/libertyio/Simple-SMS-Messenger) is an open source fork of [Simple SMS Messenger](https://github.com/SimpleMobileTools/Simple-SMS-Messenger), which was available with a [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.html) at the time of the
fork.

Liberty Messenger adds the following major features:

* organize conversations into favorites, contacts, and recents
* separate notification settings for favorites, contacts, and recents

Liberty Messenger removes or disables the following features:

* annoying popups to rate the app, donate, etc.
* ability to choose the color scheme for the app
* link to purchase the "Simple Thank You" app

## Background

The features to organize conversations and separate notifications by favorites, contacts,
and recents were initially proposed in Simple SMS Messenger [issue #75](https://github.com/SimpleMobileTools/Simple-SMS-Messenger/issues/75)
and contributed in [PR #87](https://github.com/SimpleMobileTools/Simple-SMS-Messenger/pull/87),
but were rejected. A similar feature was also submitted to Google as feedback for the Messages
app, but was ignored.

However, we felt that the two features were useful and after using them privately for
almost a year, decided that we should make them available to others. These feature are
a great way to solve the spam problem so you can stay in touch with people you care about.

Liberty Messenger is the first SMS app that enables you to organize your texts into
favorites, contacts, and recents, preventing spam texts from stealing attention from you
or crowding out texts from people you care about.

## How to use Liberty Messenger

The app shows three tabs at the top: favorites, contacts, and recents.

Messages to and from people in your favorites will appear in the favorites tab.

Messages to and from people in your contacts will appear in the contacts tab.
Your favorites are also in your contacts so they will appear in the contacts tab also.

All messages will appear in the recents tab. Messages from your favorites and contacts
will appear in the recents tab, and also messages from unknown senders will appear there.

You can choose different notification settings for favorites, contacts, and unknown senders.

To customize notifications, open or return to the main activity with the list of conversations
(what you see when you open the app), tap the three vertical dots
in the top right corner to open the menu, tap "Settings", then "Customize notifications".

If you don't want any notifications from unknown senders, you could simply uncheck the box
next to "Unknowns". Alternatively, you could disable the sound and vibration, and choose
whether or not they pop on screen, and whether you see a notification dot.

By disabling or quieting notifications from unknown senders, you can easily ignore whatever
spam arrives in the "recents" tab. If you're expecting a text with a temporary code, or you
just met someone new and they are texting you their contact info, you can switch to the
"recents" tab and find these texts at the top when you're looking for them.

With the spam neutralized, there's no need to waste your time individually blocking all the
telephone numbers of unknown senders. In fact, you shouldn't do that because eventually one
of those telephone numbers might be assigned to a real person who will not be able to text you
and you'll have another hassle at first with the miscommunication, and later when you try
to find their number in your long list of blocked senders in order to unblock them.

Enjoy your freedom from spam!

## Android Permissions

Liberty Messenger uses the following permissions:

**Contacts**

* read your contacts

The contacts permission is important for sorting messages into favorites, contacts, and recents.

**Phone**

* read phone status and identity

Used to recognize your own phone number, and to keep track of conversations when the phone has
multiple SIM cards.

**SMS**

* read your text messages (SMS or MMS)
* send and view SMS messages
* receive text messages (SMS)
* receive text messages (MMS)

Android requires that only one app be used to receive SMS and MMS messages, so we need
all these permissions for the app to work because it has to be able to receive, view, and
send SMS and MMS messages.

**Other**

* prevent phone from sleeping

This is used to ensure messages are properly received and stored.

## Contributing

If you have a feature or bugfix to contribute which is directly related to organizing conversations
by favorites, contacts, and recents, please open an issue here or in the forked repositories:

* [Simple-SMS-Messenger fork](https://github.com/libertyio/Simple-SMS-Messenger)
* [Simple-Commons fork](https://github.com/libertyio/Simple-Commons)

Otherwise, if you have a core feature or bugfix to contribute, please try contributing it first in
Simple Mobile Tools:

* [Simple SMS Messenger](https://github.com/SimpleMobileTools/Simple-SMS-Messenger)
* [Simple Commons](https://github.com/SimpleMobileTools/Simple-Commons)

In general, we want to keep the fork updated with new features and bug fixes from the upstream
repository. To make this easier, the forked repositories do not make any changes to the `master` branch
except for the `README.md` file.

The `liberty_main` branch of each fork is where we keep the customizations and from which we build the customized app.

When creating new long-term branches for work in progress, use `liberty_main+{branch}` as the branch name
to keep things organized.

## Credits

Many thanks are due to [Tibor Kaputa](https://github.com/tibbi), the author of Simple SMS Messenger,
and the other contributors to Simple SMS Messenger,
for writing a decent open source replacement for Google Messages, and publishing with the GPLv3 license.

## Copyright

Portions of the code are copyright (C) 2021 Liberty Infrasystems, LLC.

Please see [Simple SMS Messenger](https://github.com/SimpleMobileTools/Simple-SMS-Messenger) and
[Simple Commons](https://github.com/SimpleMobileTools/Simple-Commons) for the original
code and copyright notice for that code.

## Trademark

The name Liberty Mesenger and the Liberty Messenger logo are trademarks of Liberty Infrasystems, LLC.
