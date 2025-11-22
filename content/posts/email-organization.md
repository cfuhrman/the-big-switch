+++
title = "Email Organization"
date = "2025-11-22T10:17:08-08:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = "Chris"
authorTwitter = "" #do not include @
cover = ""
tags = ["Email", "GMail", "Duck", "FastMail"]
keywords = ["", ""]
description = "How I break up my email addresses"
showFullContent = false
readingTime = false
hideComments = false
+++

# Email Organization

Currently, I have my main GMail account and another one on
[FastMail](https://fastmail.com), which I use for communicating with friends and
family as well as storing my calendar and contacts.  Since my current GMail
account has become an [unmanageable spam magnet]({{< ref
"posts/why-new-google-account/" >}}),
how to set things up such that I can keep better control of my email?

## Requirements

Here's what I'd like to have:

 1. Personal account for friends and family
 2. Corporate/professional account for businesses and such
 3. An account specific for Google Services such as Photos, Drive, etc.,
 4. A forwarding account that also provides a masking service when I have to
    sign up for email lists and such.  This will be directed to the corporate/
    professional account.

## What I've come up with

For my friends-n-family as well as Calendar and Contacts, I will continue to use
my FastMail accounts.  The nice thing about FastMail is that they allow you to
create email aliases and then you can use their Email Filters to deliver aliased
email to a separate folder.  No change there.

For the corporate/professional account, there is nothing wrong with continuing
to use GMail for this purpose.  It blocks most spam and integrates well with
other services.  But, how to protect the account such that it doesn't become a
Spam-dump again?

### Duck Duck Go

Enter [DuckDuckGo's Email Protection](https://duckduckgo.com/email/) service.
This allows you to create an account in the `@duck.com` domain and then forward
email sent to that address to another email address of your choosing.  Duck Duck
Go will filter out trackers and such from the email before sending it on, giving
you a measure of privacy.

They also offer users the ability to create one or more throwaway email
addresses for organizations that like to sell your data to third-party brokers.
I've found that political organizations like to do this aggressively.  The
organization sells your email address and you start getting all kinds of email
you don't want?  Deactivate it!  You will need to either use Duck Duck Go's
[Browser](https://duckduckgo.com/duckduckgo-help-pages/get-duckduckgo/browser)
or the [Browser
Extension](https://duckduckgo.com/duckduckgo-help-pages/get-duckduckgo/browser-extension)
to manage private email addresses.

Duck Duck Go also offers a [subscription
service](https://duckduckgo.com/duckduckgo-help-pages/privacy-pro) that provides
the following:

 * VPN
 * Duck.AI
 * Personal Information Removal
 * Identify Theft Protection
 
As of the time of this writing, I haven't decided whether to sign up for this
service yet.

### Google Service Account

Finally, I'd like a Google account that's only used for Google-specific
services, such as the Google Worksuite, Photos, Drive, Youtube, etc.,  This way,
I keep my private life separate from my public life.  As for transferring
everything, Google offers a [Takeout Service](https://takeout.google.com/) to
facilitate this.  As of this writing, I've selected a number of services to
export and am waiting for Google to create an archive (this could take hours or
days according to their website).  Once this is done, I'll be sure to write
about the experience.

