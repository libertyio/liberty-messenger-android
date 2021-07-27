# Liberty Messenger

Send and receive SMS organized into favorites, contacts, and recents.

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
but were rejected. A similar feature was also submitted to Google as feedback to the Messages
app, but was ignored.

However, we felt that the two features were useful and after using them privately for
almost a year, decided that we should make them available to others. These feature are
a great way to solve the spam problem:

When you have all messages from unknown contacts appear in the "recents" tab, and you turn off
all notifications for messages in that category, then you have an SMS app that only notifies you
when you receive messages from people you know. Spam texts no longer steal attention from you
or crowd out texts from people you care about. When you're logging into a website and they send
you a code via SMS, you already know to expect it so open the "recents" tab and wait for that
message to arrive.

## Contributing

If you have a feature or bugfix to contribute which is directly related to organizing conversations
by favorites, contacts, and recents, please open an issue here.

Otherwise, if you have a core feature or bugfix to contribute, please try contributing it first in
[Simple SMS Messenger](https://github.com/SimpleMobileTools/Simple-SMS-Messenger).

In general, we want to keep the fork updated with new features and bug fixes from the upstream
repository. To make this easier, the repositories [Simple-SMS-Messenger fork](https://github.com/libertyio/Simple-SMS-Messenger)
and [Simple-Commons fork](https://github.com/libertyio/Simple-Commons) do not make any changes to the `master` branch
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
