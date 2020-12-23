# Going All in on the Mac App Store

With the announcement of the [App Store Small Business Program](https://developer.apple.com/app-store/small-business-program/), I've stopped selling Unbound directly via the web site. I thought it would be worth explaining how I came to that decision.

The original motivation for selling the app directly was simple: Apple took a 30% cut of sales, whereas [Paddle](https://paddle.com), the payment processor & authentication tool I was using to sell directly only took [*not-publicly-disclosed-but-substantially-less-than-30*]%. With the drop in Mac App Store fees, that gap has shrunk considerably... to the point that it's no longer worth keeping Paddle around.

## 1. Direct sales are a worse experience for customers.

From a customer's perspective, every direct sale is its own little special snowflake, and you have to figure out how to get your license key, where in the app to enter it, etc. 

For the most tech-savvy users, this is pretty much a non-issue (until, of course, you migrate to a new computer and have to dig through your email to find your product key—good luck!). But a substantial percentage of users had trouble with this, and it was the #1 source of support requests for me.

In contrast, virtually *every* Mac user is familiar with the Mac App Store. (And even if they aren't, it can't be a *worse* experience than trying to figure out a third-party platform!) Moving installs between machines is a non-issue, and there's no such thing as an activation problem. 

## 2. Direct sales increase the overhead of each release.

Unbound is not my day job, and revenue-wise, it probably doesn't have any conceivable path to become my full-time income. That means I can only work on it during nights & weekends—a rather limited amount of time.

For that reason, I want to maximize the time I actually spend shipping new features. Selling directly meant that I had to cut two builds, and go through two release processes, every time I wanted to ship an update. (And of course I've already mentioned the support burden of direct sales—support takes time directly away from development!)

## 3. Direct sales are a security and privacy liability.

If Paddle suffered a data breach, suddenly *I* would be on the hook for exposing people's emails or (God forbid) credit card data. While this has *not* happened, and I have no reason whatsoever to think Paddle is anything but competent, I'm still much happier trusting Apple's security practices than *any* third party. (And if *Apple* has a security breach, I feel like I'm unlikely to take the blame from customers—the vast majority of them have done business with Apple directly in the past, whether for their computers, phones, or even just iTunes purchases.)

Even apart from a data breach, removing all third parties from the equation is a privacy win for customers—I can proudly tell people the app collects *no* data whatsoever, whereas Paddle had to "phone home" to validate product keys.

## It's just not worth it any more.

Given all that, the math just doesn't work out in support of doing direct sales any more. Even if I moved sales to accepting credit cards directly, a 3.5% fee with all those downsides is substantially worse for both me and my customers than a flat 15%.

Onward and upward!

-- Tyler

Let me know what you think—find me on Twitter [@TylerAYoung](https://twitter.com/TylerAYoung) or email me at my first name at unboundapp.com.


