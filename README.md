# [:ocean: Laminar](https://github.com/dosyago/laminar)

**Laminar** is the on-prem, downloadable, no phone-home web RPA solution to automate any sequence of interactions in the Chrome browser.

## Completely Open Source

Developed completely in the ocean, using already open-source parts, Laminar is built to be robust, open, and transparent.

## Completely Free

I believe RPA should be available to everyone. The tools exist, it's not that complex, there's no need to pay by the month for what you can do on your own workstations. I see no reason to charge for this software. It's completely free. 

## Completely Comprehensive

Laminar aims to provide an intuitive interface to easily automate *anything* someone can do in a web browser. 

## Secure, Simple and Open

Because you're on your own machine, you can automate your own internal web-based/browser-based apps, without every leaving your intranet. 

Nothing you do, and no data about what you're automating, no credentials, no nothing, is ever sent from Laminar to any 3rd-party servers. 

Laminar does just what you tell it to do, how you tell it to do it, and as many times as you tell it do.

## Downloading

[Get it!](https://github.com/dosyago/laminar/releases)

## FAQ

### Can I save the bots and share them with others?

Yes. Bots are saved as simple JSON text files. You can easily save, and share these with anyone you want.

### What about sensitive data, like credentials, or form fields, are they saved with the bots?

No. Bot files and any data to be input are separate files. Of course you can share the data files with others if you want, but you can also just give them the bot files, and they can provide their own credentials or input data.

### Can I take input data from a Spreadsheet?

Yes but you need to save the spreadsheet to CSV first. Should be easy, right? I know it sounds a little inconvenient, but keeping it in CSV, just makes the app simpler. Supporting all sorts of native spreadhseet format, or import from cloud, would get in the way of the app being simple, and, well, free.

### So bot files don't contain any sensitive data like input data or credentials?

That's right, bot files do not contain any senstiive data like input data or credentials.

### Can I chain bots together, so that the output from one, becomes the input for another?

Yes. It's easy. But you need to make sure yourself that the output format of the former bot, matches the input format of the latter bot. Just keep your CSV columns the same, and you should be good. I know it sounds a bit complex, but this is probably the part that can open up the most errors, and it really is up to you to make sure your formats are compatible. 

### Is it really free? No hidden catches?

No hidden catches. It's bit hard to believe, I know, but it really is free.

### Am I locked in?

No. You can export your bots to other formats, such as Puppeteer scripts. But please note that because Laminar features many advanced capabilities, not everything can be replicated in Pupeteer.

### What about web scraping, where do I save the data?

The data is also saved to your machine, wherever you like. We can save in CSV, so you can import into your spreadsheet application.

## Do you support saving directly to Box, Google Drive, or Dropbox?

Nope. We keep everything local. I know it sounds a bit inconvenient, but when you consider the security, permissions, and all the other managmeent required to allow you to grant us permissions for these apps, then handle the saving, and other features expected along with that, it becomes too complicated for a simple downloadable app. It would get in the way of the security isolation, privacy, simplicity, and well, "Freeness" of the Laminar free downloadable RPA app.

### How will you continue to develop it in future, i.e., how will you make money?

I have a plan in future to open some sort of "Community" in the cloud. Where people can publish and share bots of their choosing. I'm thinking that membership in this community could be based on a monthly fee per person. Also, perhaps organizations could have their own "tenancy", so all their users could sit together and share stuff with each other. Or maybe, it's open, but people can join their organization group, and share some bots with everyone, some bots only with the organization group, and some bots they can keep private to share with nobody. The default is private. And in fact, in thie future vision, I don't want people to be able to upload any bots to such a "Cloud Community" until they choose they want to. 

The idea is that it's a convenience that can help people reduce repetitive work by sharing bots they've already created. The other thing is, I think there could be some sort of chat or forum, so people can help each other discuss about how to make bots. That would also mean instead of me answering people's questions, other people, experienced with the product, can answer questions. 

I'm also thinking that this CLoud Community could allow you to, if you wanted, run your bot in the cloud at scale. Obviously, that seems like it creates some security issues, and tricky aspects, such as, running in the cloud means sharing any credentials with my cloud service, it also means that any private intranet apps could no longer be accessed, unless there was some special SSO sign on portal for that intranet, which again, looks like it would introduce a lot of tricky security issues. So I'm thinking that this Cloud Run for the bots, is probably something people will only want to use for bots where the security is not an issue, such as collecting data from public websites, or when they have sufficient trust in my cloud service that they think it's OK. 

This sort of cloud run is the most complex, because we need to provide things like IP rotation, scalability, reCAPTCHA handling, and so on. It's actually quite complicated to do right and will probably be quite expensive to run. But I'm thinking that, at least initially, it's not our core market (which is mainly RPA, and is not massive data scraping). But if people want a solution for that before we release it they can see something like [Browserless](https://github.com/browserless)

## Development Log

For development notes and progress, see the [issues](@dosyago/laminar/issues), or the [DEVNOTES](DEVNOTES.md)



-------

# *Laminar!*
