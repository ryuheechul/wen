# Wen

A missing simple date/time widget for seniors.

## Screenshots

English from Windows Tablet (Cropped) ![Screenshot 2023-07-12 144101](https://github.com/ryuheechul/wen/assets/2637709/138a9215-6e3b-4483-88a1-5dfc3b1dec22)

Korean from iPad ![IMG_0185](https://github.com/ryuheechul/wen/assets/2637709/7da7f27e-1df9-4a37-aeb3-239b65e5ef27)

French from iPhone ![image](https://github.com/ryuheechul/wen/assets/2637709/b488715d-a6db-4089-a7c8-163ae3d28572)

Japanese from iPhone ![image](https://github.com/ryuheechul/wen/assets/2637709/156951d2-6d66-4544-ada3-d3fa60571dbb)

Chinese from Android Tablet ![Screenshot_2023-07-12-15-20-41](https://github.com/ryuheechul/wen/assets/2637709/02803f66-49a1-4162-9a84-60a220424bc4)

## Why

Some seniors struggle to keep up with what day/date/time it is right now.

Yes they might have paper calendars at home but nothing is easier than telling
you the answer to your face!

There are great-looking hardware products out there that solve similar problems
(with some keywords like "digital calendar for seniors").

But they can lack language support for your seniors or you might want to set it
up right away and just happen to have an old tablet lying around while you are
waiting for a more permanent solution.

## How It Works

This is [a simple html page](./index.html) that is designed to work (also) with
some older tablets or phones.

Once it's loaded, it just refreshes the date/time every second. There is no
network accessing code.

The dark background and moderately bright text color is hard-coded for now in
mind of:

- preventing disruption by too much bright light
- the screen being on all the time

## Change (and Lock) Screen Rotation

You may want to set the screen orientation for landscape mode for optimal
layout.

## Adjust Font Size

You can change it either with the settings from the device or with the browser's
tab if the default font size is not optimal.

## Make Sure Device Time Is Correct and Synced

The JavaScript code is relying on the system (device) for the correct date and
time. Make sure to check your Android's (or equivalent device's) date/time
settings and ensure it's automatically synced via internet.

## Change Device Language

Does your senior have a preferred language? If you device supports that, change
the language on the device and then it should work.

## Full Screen Toggle

If you tab or click anywhere on the page, it should toggle full screen.

This doesn't work with iPhones. You can
[Add a website icon to your Home Screen](https://support.apple.com/en-ca/guide/iphone/iph42ab2f3a7/ios#:~:text=Add%20a%20website%20icon%20to%20your%20Home%20Screen)
to mitigate it.

## Prevent Screen From Going to Sleep

If you want to keep displaying the date/time without the screen turning off
after some time there should be something you can do about it.

I found a tool like https://github.com/richtr/NoSleep.js/ but I haven't included
this feature yet into the web page directly in order to keep functionality
simple.

However, there might be a solution like
https://f-droid.org/en/packages/com.github.muellerma.coffee/ that would work but
your mileage may vary.

For iOS/iPadOS there is _Settings > Display & Brightness > Auto-Lock > Never_.

You should be aware of the energy consumption of your device and the risks of
having it on all the time (if that's your intention) as your device might not be
designed for such usage.

## Teach How to Recover

It's very possible that seniors could be curious about the screen and start
touching it and cause the toggling of full screen or worse(!), minimize the
browser (assuming you are loading this web page with a browser). In case you are
not around to restore the status yourself all the time, it's a good idea to make
it easy for the intended user to restore it and teach them how to do it
themselves.

For that I would create a shortcut to the home screen and let them practice the
restoring so they can recover by themselves. If they can't do it right away or
forget how to do it later, be patient... rinse and repeat.

## Disclaimer

I'm not endorsing any activity that is written here, I'm only sharing my
knowledge on what's available for certain use cases with my best intentions and
it's up to you to decide what to do with that and which services and settings to
use, and you are responsible for your own actions, proceed at your own risk!
