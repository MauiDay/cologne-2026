
<p align="center"><img style="width: 400px;" src="images/cologne26.png" /></p>

# MAUI Day Cologne
All slides and relevant things from .NET MAUI Day 2026. The event was held on October 23rd, 2026 @ the Microsoft Office in Cologne.

https://mauiday.net/ 

There were no video recordings of the event.


# Sessions
The sessions are in chronological order.  
&nbsp;   


## Building the Next Generation of Apps with .NET MAUI

<img src="images/GeraldVersluis.png" width="120" alt="Gerald Versluis" />

**Speaker:** Gerald Versluis

.NET MAUI continues to evolve as the modern .NET framework for building native, cross-platform apps. With .NET 11 rapidly approaching, this keynote looks at where .NET MAUI stands today, what is coming next, and how it fits into the future of mobile and desktop development.

We'll explore the bigger themes shaping the platform: quality, performance, developer productivity, great native experiences, and the growing role of AI in how we build and use apps. Rather than focusing only on individual features, this session will connect the dots between the current state of .NET MAUI and the opportunities ahead.

Whether you are building consumer apps, enterprise tools, internal productivity apps, or new AI-powered experiences, this session will show why .NET MAUI remains one of the best ways to turn ideas into native apps across platforms.
   
&nbsp;   
  
## .NET MAUI 11: Focused on Perf

<img src="images/SimonRozsival.jpg" width="120" alt="Simon Rozsival" />

**Speaker:** Simon Rozsival

.NET 11 completes a multi-year runtime consolidation: CoreCLR is now the default runtime across all .NET MAUI targets — Android, iOS, macOS, and Windows — and Native AOT is available on all these platforms too. Behind that switch is a lot of platform work: reshaping runtime internals for performance, and making long-standing pieces of the stack compatible with CoreCLR and AOT compilation.

This deep dive comes in two parts. First, what we changed: how core runtime and MAUI components were optimized and made trimming/AOT-safe — from a rebuilt type-map system and reflection-free rewrites of features like HybridWebView, to microbenchmark-driven fixes in MAUI's hot paths. You'll see why your app is likely faster and smaller in .NET 11 without touching your code.

Second, what you can do: the extra steps you can take to squeeze more out of your apps. We'll cover app-specific MIBC startup profiles and how to collect them for your own app, ReadyToRun and the app-size vs. startup trade-off, and how to get your app trim-clean and ready for Native AOT — including the things that commonly break and how to fix them.

You'll leave understanding what's happening under the hood and with a concrete checklist to make your own MAUI app faster and smaller in .NET 11.
   
&nbsp;   
  
## Bulletproof .NET MAUI: Building Apps That Don't Crash

<img src="images/MichałPobuta.jpg" width="120" alt="Michał Pobuta" />

**Speaker:** Michał Pobuta

Every mobile app crashes at some point. The question isn't "whether" — it's "how often" and "whether you even know about it."

In this session, I'll show concrete patterns and tools that make .NET MAUI apps crash significantly less often, and ensure that when they do crash, you know before your users do.

* The most common causes of crashes and ANRs in MAUI — unhandled exceptions, blocking the main thread, async/await pitfalls, memory leaks, race conditions during navigation. Each case shown with an example of bad and good code.
* A global safety net: how to hook into AppDomain, TaskScheduler, and platform handlers (Android/iOS) so no exception disappears silently.
* Production observability — Sentry and Firebase Crashlytics in MAUI, stack trace symbolication, breadcrumbs, device tags. Without this, you're flying blind.
* Crash-resistant patterns — a BaseViewModel with a safe execution wrapper, lifecycle cancellation to prevent operations from firing after navigation, all async operations cancellable via CancellationToken.
* Trimming and AOT as a silent crash factory — why your app works in Debug but blows up in Release, and how to configure CI to catch it before your users do.
   
&nbsp;   
  
## Building with AI at the Edge

<img src="images/DavidOrtinau.jpg" width="120" alt="David Ortinau" />

**Speaker:** David Ortinau

Nobody can really predict what app development will look like in the next weeks and months exactly. The same skills that helped you grow and excel through every technology release and minor or major shift in the mobile race, those skills are what will make you successful today and tomorrow. The pace is just...a bit faster. In this session I'll share how we are using the latest tools and services to build efficiently, effectively, and sustainably.
   
&nbsp;   
  
## One Screen, Every Device: State Triggers and the Visual State Manager in .NET MAUI

<img src="images/AlmirVuk.png" width="120" alt="Almir Vuk" />

**Speaker:** Almir Vuk

Your app looks perfect on the phone emulator. Then someone rotates the device, resizes the desktop window, or opens it on a tablet... and the layout falls apart.

Triggers are .NET MAUI's answer, and they live entirely in XAML. In this session we'll walk through all of them: property triggers, data triggers, event triggers, and multi-triggers. Then we get to the good part: state triggers, which let one screen reshape itself for any window size, orientation, or device, with almost no code-behind.

We'll look at the live code in a single demo app, exploring one trigger type at a time. Along the way, I'll show the gotchas that bite in real projects: why a data trigger silently does nothing, when triggers leak, and when you should just use a behavior or converter instead.

You'll leave knowing which tool to reach for, and when.
   
&nbsp;   
  
## Keep writing code. Stop typing it. Massively distributed live coding with AI

<img src="images/StéphaneDelcroix.jpg" width="120" alt="Stéphane Delcroix" />

**Speaker:** Stéphane Delcroix

Engineers of the MAUI team, present and remotes, will live code an app. You'll see their funky prompting styles, the way they yell at copilot, and what can be achieved in a session. Interact live, or send pull-requests.
   
&nbsp;   
  
## .NET MAUI Q&A Panel

<img src="images/DavidOrtinau.jpg" width="120" alt="David Ortinau" /> <img src="images/GeraldVersluis.png" width="120" alt="Gerald Versluis" /> <img src="images/StéphaneDelcroix.jpg" width="120" alt="Stéphane Delcroix" /> <img src="images/SimonRozsival.jpg" width="120" alt="Simon Rozsival" /> <img src="images/MaddyMontaquila.jpg" width="120" alt="Maddy Montaquila" />

**Speakers:** David Ortinau, Gerald Versluis, Stéphane Delcroix, Simon Rozsival, Maddy Montaquila

This was your chance to put your burning questions to the MAUI team.


<br/>
<hr/>
<p align="center">The .NET MAUI day is in no way endorsed or supported by Microsoft and is not a official Microsoft event.</p>
<p align="center">If you wish to rectify or complement any information send a message to <a href="https://twitter.com/ZeProgFactory">@ZeProgFactory</a> or make a pull request ;-)</p>
