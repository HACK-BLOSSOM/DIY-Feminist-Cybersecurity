---
title: "Hacking"
bg: purple    #defined in _config.yml, can use html color like '#010101'
color: black  #text color
style: left
fa-icon: crosshairs
---

<h2 class="text-white">Protect your digital accounts.</h2>

Your online accounts are points of access to your life both online and off. From email to social media to shopping, your accounts are crucial for pretty much everything you do through the internet. Spread out across these accounts is a treasure trove of personal data, credit card information, and even the ability to be “you” in online spaces. Unfortunately, hackers and abusers see the value in being able access these accounts: they’re one of the most popular targets for cyber harassment and crime. This section offers a number of ways to make hacking into your online accounts much more difficult. <strong>As with any electronic service, there is no foolproof way to protect against a dedicated hacker (and you should never trust anyone who claims otherwise)</strong>, but adding layers of security gives you much more control over your online identity and information that can deter and prevent many common forms of hacking.

As we outline best practices, useful technologies, and recommended services, the most crucial thing to remember is to be conscious of the risks of any given context. One of the best things to ask yourself is “If this was hacked, how would it impact my life?” Thinking along these lines mean that YOU can dictate the security and privacy of your digital life. You can choose to add more security measures, or fewer. You can choose to use a safer service, or stay with what you have. It's your call!
<hr>
<div id="phishing">
<p>
	<h3 class="text-white">Social Engineering and <strong>Phishing</strong></h3>
</p>
</div>
Believe it or not, the majority of successful hacks do not need advanced technical skills. From government spies to pathetic trolls, malicious hackers frequently rely on surprisingly simple schemes to trick people into giving up their passwords, emails, and other private information. <strong>Social Engineering involves psychological manipulation of targets to reveal sensitive information.</strong> A common example is a hacker calling a customer service or technical support worker at a website: they claim to be an employee or a customer and smooth-talk their way into being given private data about a customer. Another common case is simply contacting a target and pretending to be a representative of a company or service: a hacker can claim to be a utilities worker needing information about your apartment, a healthcare worker asking about your health plan, or any other number of roles in order to steal your information. <strong>Phishing is a very popular form of social engineering where a hacker will send you a professionally designed email pretending to be a website or service, including a website link for you to follow.</strong> When you click the link, it will take you to a seemingly legitimate website that asks for your password, ATM pin, or other information. But in reality, the website is a fake that collects the private data you mistakenly hand over!

So how can you protect yourself against these sorts of attacks? We have a few pointers that will help you out!

<div class="recommend">
<h5 class="text-white">Do not login to websites from a link in an email</h5>
<br>
As a rule of thumb, if an email link directs you to a login screen, you should be suspicious. It's best to simply go to the website yourself in your browser, login normally, and look for the page the email wanted you to browse. An exception is when you reset a password for a site (the website needs to provide a personalized link for you to change your password). In this case just make sure that you explicitly requested a password reset. And use a <a href="#strongpasswords">unique password</a> just to be safe!
</div>

<div class="recommend">
<h5 class="text-white">Always install software updates as soon as possible</h5>
<br>
Hackers often rely on exploitable vulnerabilities in popular software to target their victims. Software developers can quickly become aware of these vulnerabilities and release software updates to fix the issue. It's imperative that you keep your software up-to-date so that your apps have the latest security fixes available to you! This is easy to do too: when your computer notifies you that there are updates to install, just go ahead and do it. Especially make sure to install macOS, iOS, Android, and Windows operating system updates ASAP!
</div>

<div class="recommend">
<h5 class="text-white">Try not to login to websites via Facebook, Twitter, or Google</h5>
<br>
Many websites offer the option of logging in with your social media account rather than having to create an account for the website. Although convenient, this presents a huge security risk: how do you know if this site is legitimate? By encouraging unsuspecting users to use their social media accounts, a malicious website can easily collect valuable names and passwords. It's much safer to just create a new account for the site.
</div>

<div class="recommend">
<h5 class="text-white">Do not trust emails asking for personal information, survey data, or anything else that could reveal info about you, no matter how professional they look</h5>
<br>
The vast majority of websites do not need your personal data to provide their services, so be suspicious if they ask for it (besides, who cares what they want? It's not your responsibility to give them <em>anything</em>). If you think the request is legitimate, do not follow their supplied link: you should be able to do whatever you have to do by navigating their website in your browser. If you can't, they clearly have shitty security practices and you should be suspicious of them in general!
</div>

<div class="recommend">
<h5 class="text-white">Use HTTPS connections whenever possible</h5>
<br>
In the <a href="#anonymity">Anonymity section</a>, we talked about the value of using the <a href="#httpseverywhere">HTTPS Everywhere</a> extension. When you connect to a website using HTTPS, your browser ensures the site is not a fake by verifying the site's HTTPS certificate is legitimate. Because fake sites cannot replicate the expected HTTPS certificate, your browser could give you a warning that a fake site is insecure. <strong>Trust your browser!</strong> By installing the <a href="#httpseverywhere">HTTPS Everywhere</a> extension, your browser will try to use HTTPS whenever possible, thus offering an easy first-line of defense against phishing scams.
</div>

<div class="recommend">
<h5 class="text-white">Beware public wifi</h5>
<br>
When you are on a wifi network, anyone else using that network can watch or intercept your web traffic (even if it's a password-protected network). So an easy phishing scheme could be sitting in a coffee shop and intercepting all requests to facebook.com so everyone sees a fake phishing site instead, thus collecting many people's passwords. The absolute best protection is to use a <a href="#vpn">Virtual Private Network</a> to seamlessly encrypt your web traffic so it cannot be intercepted. A great alternative is to use the <a href="#tor">Tor Browser</a> to send your browsing over the Tor network, thus anonymizing you while encrypting your data (although it will be slower than using your normal browser). If you're on a phone, try to only use your regularly installed apps for using websites rather than logging in through a browser (since phone browsing is <a href="#phones">much less secure</a>).
</div>

<hr>
<div id="fakeemail">
<p>
	<h3 class="text-white">So do you <em>really</em> need to give out your personal info? (...no)</h3>
</p>
</div>
Quite frequently a website or service will want more than just an email address and a password: they may want your name, your location, and other juicy marketable data. Well, fuck ‘em! Who says you have to tell them the truth? <strong>A good rule of thumb is to only give personal information that is absolutely necessary. Don’t be afraid to make things up! </strong>You can always give a fake name, a fake address, and all sorts of other made-up information. Unless you’re buying something, rarely is this personal information ever really crucial. By providing fake data, you lower the risk of a compromised account being linked to other accounts by shared data, as well reducing the possibility of a malicious person finding out more about you in real life.
<br>
<br>
(<em>By the way, email addresses don’t need to be real either. If you’re just registering quickly to use a site once or twice, use a disposable email address! This is especially handy if you need to do something online anonymously. We like using <a href="https://www.sharklasers.com/">Sharklasers.com</a> because sharks are neato, but there are many similar services out there.</em>)

<hr>
<div id="strongpasswords">
<h3 class="text-white">Strong Passwords: <strong>“Ugh”</strong></h3>
</div>
To quote xkcd, “Through 20 years of effort, we've successfully trained everyone to use passwords that are hard for humans to remember, but easy for computers to guess.”

The vast majority of online accounts can be accessed through a password and email address/username. As we all know, a good password is essential in ensuring that hackers can’t get into our shit. However, the ways we create and remember passwords tend to be very easy to hack: common words and phrases can be programmatically exploited when trying to access an account. As the first and frequently only line of defense to accessing your account, strong passwords are key!

Here are a few general rules to follow for creating good, strong passwords:
<div>
<br>
<ol>
	<li>A mixture of random letters, numbers, and special characters is best.</li>
	<li>The longer, the better. 12 characters or more!</li>
	<li>DON’T RE-USE PASSWORDS ACROSS MULTIPLE SITES.</li>
	<li>DON’T RE-USE PASSWORDS ACROSS MULTIPLE SITES.</li>
</ol>
</div>
<br>
Memorizing passwords that follows these rules can be a total pain, especially when you have so many. Luckily, xkcd <a href="https://xkcd.com/936/">has a wonderful approach</a>: <strong>When creating passwords, use passphrases of three or four random words.</strong> Not only are these passwords far easier to remember, they're far more difficult to hack because they're so long! Here's a few examples:
<br>
<ol>
	<li>correcthorsebatterystaple</li>
	<li>sillyredkitchenplant</li>
    <li>librarypantherseatvanilla</li>
</ol>


<hr>
<div id="passwordmanager">
<h3 class="text-white">Password Managers: <strong>“Cool!”</strong></h3>
</div>
As you can guess, making strong passwords sucks. When you have dozens of accounts across many sites, it’s practically impossible to be perfect about creating and remembering all these unique passwords. Not to mention that sometimes sites are terrible about storing passwords: they get hacked, but -you- have to change your password. There are tools to help you though! A password manager is an online service that can generate and store all your passwords for you so that you don’t have to know them by heart.

<code>Lifehacker has a <a href="http://lifehacker.com/5529133/five-best-password-managers">useful guide</a> detailing some of the most popular password managers out there.</code>

You’re probably suspicious: isn’t it dangerous to have all your passwords in one place? And you’d be right to think so, because it is! That’s why it’s important to evaluate how a given password manager actually manages the passwords and what protections are in place. Ultimately, you have to decide for yourself how you balance the risk of bad passwords, spread out across your accounts, against the risk of good passwords centralized in one location.

<div class="recommend">
<h5 class="text-white"><strong>LastPass</strong></h5>
<br>
Given how hard it is to remember safe, unique passwords, we still recommend a password manager, specifically the service <strong>LastPass</strong>.<br>
<br>
LastPass uses a combination of browser extensions, phone apps, encryption, two-factor authentication, and a multitude of other technologies to ensure your passwords are stored safely and accessibly (for only you!). It can also randomly generate -extremely- strong passwords for you to use. We especially like LastPass because all of your passwords are encrypted when saved in LastPass’ cloud: even if they were hacked, a hacker could not use them unless they knew your LastPass password (which is never stored by LastPass). Needless to say, if you decide to use LastPass, make sure your password to access LastPass is the strongest password you’ve ever had! You won’t have to remember your passwords anymore, so this should be a bit easier to do.<br>
<br>
You can get started with LastPass at their <a href="https://lastpass.com/">official site</a>.<br>
<br>
As we keep our minds on risk mitigation, we recommend that you do not use LastPass for your email, bank, or healthcare accounts. Although LastPass is a very secure service, it’s still a company subject to mistakes and vulnerabilities. By separating out your most crucial passwords, you have a bit of protection by not having ALL your eggs in one basket. The important eggs are worth storing in their own basket!<br>
<br>
A few good rules of thumb for using LastPass:<br>
<br>
<ul>
	<li>Use password generation for lengthy, complicated passwords. At least 16 characters with letters, numbers, and symbols is good.</li>
	<li>Make sure to enable Two-Factor Authentication for LastPass.</li>
	<li>Always require your master password for entering passwords for important accounts.</li>
	<li>Once you have logged-in to LastPass from your phone and/or tablet, from your vault page on the LastPass website, go to Settings, and under the “Mobile Devices” tab, make sure to check “Restrict mobile devices to the specific UUIDs listed as enabled below”. This way only these specific devices can be used to login to your LastPass.</li>
</ul>
</div>

<hr>
<div id="twofactor">
<h3 class="text-white">Two-Factor Authentication: <strong>“Yay!”</strong></h3>
</div>
One of the absolute best things you can do for your online accounts is enable two-factor authentication (2FA) whenever it’s available. Essentially, rather than only needing a password to login, you need to enter a second piece of data as well. This is typically a short code sent to you in an email, a text, or generated by an app on your phone. 2FA is a wonderful piece of security because it means that even if your password(s) were hacked, a hacker would still need access to your email, phone, or app in order to get into your account.

You should definitely enable 2FA for any of your crucial accounts that offer it. Most big tech services like Google, Facebook, Dropbox, and Twitter have this option available, as do popular password managers like LastPass. Typically you just need to dig around in your account settings on a given site to find the instructions on how to enable it. <a href="https://www.google.com/landing/2step/">Here</a> is a useful guide from Google if you would like to know more about how Two-Factor Authentication works.

<div class="recommend">
<h5 class="text-white"><strong>Authy</strong></h5>
<br>
When you use a site or service that offers Two-Factor Authentication (2FA), you often have the option to generate a QR code or numeric code that you enter into a 2FA app on your phone. From then on, when you log into a site and service and are prompted for a 2FA code, you just have to look in the app for a generated code to use with that account. This is more secure than receiving a code via text or email, as it is much more difficult for a hacker or surveillance to get access to. While there are many 2FA apps that offer this functionality, we recommend an app called Authy.<br>
<br>
Authy is a neat app that will automatically generate your two-factor authentication codes offline anywhere you have the Authy app installed. Authy can be installed on any phone or desktop, with all your 2FA code-generating accounts backed-up on a single Authy account. This means that if you were to lose a phone, or get a new laptop, all you have to do is install Authy and login with your Authy account info (have a very strong password!!) and your 2FA codes are still being generated seamlessly. Your 2FA accounts are encrypted in the cloud too, meaning that if Authy’s servers were ever hacked, your Authy data would be unusable! And because these codes can be generated offline, you do not need internet or cell service to access them.<br>
<br>
Available for free in the iTunes and Google Play stores, also as a chrome extension<br>
Guides for installing can be found on <a href="https://www.authy.com/users">Authy's website</a>
</div>

<hr>
<h3 class="text-white">So... how do I know if I've been <strong>Hacked</strong>?</h3>
Private companies have some of the worst security practices imaginable. Your passwords can be stored in their databases in plaintext, associated to your email and mailing addresses, sometimes even with credit card information attached. <strong>There are no regulations that force companies to take your security seriously, so very few do. As a consequence, corporate hacks and leaks are becoming increasingly common and will only continue to be more prevalent as big data mines and sells vast quantities of personal data</strong>. You probably hear about corporate hacks in the news, but they rarely make waves and are quickly forgotten. Unfortunately, this private data does not disappear with time: it is aggregated across the internet and stored indefinitely, sometimes by hackers, sometimes by security professionals. Thus, if you are not aware of a company leaking your data, or simply forget about it, you can still very much be at risk for targeted hacking (they have your personal information, after all).

<code>Check out <a href="https://haveibeenpwned.com/">haveibeenpwned</a> to see if your email or username has ever been compromised in a major data breach. Your only course of defense is to use <strong><a href="strongpasswords">strong, unique passwords</a></strong> and <strong><a href="#twofactor">two-factor authentication</a></strong> for all of your important accounts.</code>
