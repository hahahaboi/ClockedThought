<h1 align="center">ClockedThoughts</h1>

<p align="center">
  Time your thoughts. Keep your focus.
</p>

<p align="center">
  A lightweight macOS menu bar app for capturing distracting thoughts and revisiting them later.
</p>


[!WARNING]
Since ClockedThoughts is currently distributed outside the Mac App Store and is not yet notarized by Apple, macOS may display warnings such as:

* “ClockedThoughts was downloaded from the Internet.”
* “Move to Bin” / “Move to Trash”
* “ClockedThoughts can’t be opened because it is from an unidentified developer.”

This is expected for the current release.

To open the app:

1. Right-click ClockedThoughts.app and select Open, then click Open again.
2. Or go to System Settings → Privacy & Security → Open Anyway.

After the first launch, ClockedThoughts will open normally.

Have you ever sat down to work on something important, only to suddenly find yourself 30 minutes later doing something completely unrelated?

You start with one task, a thought pops into your head, you decide to quickly check it, then another thought appears, and before you know it, you’ve drifted far away from what you originally intended to do.

ClockedThoughts was built to solve exactly that problem.

Instead of fighting every distracting thought or trying to keep everything in your head, ClockedThoughts lets you “clock” your thoughts and schedule them for later. Capture the thought in seconds, get back to work, and let the app remind you when it’s time to revisit it.

The goal isn’t to suppress your curiosity or ideas—it’s to prevent them from hijacking your focus when you’re trying to get something done.

A Rapp for ClockedThoughts

No way to fight them.
No way to solve this.
ADHD-like workflow,
Thoughts again and again.

Distraction deceiver,
Focus holder,
Worry aligner,
A simple timer.

Time your thoughts,
Work needs the effort.

No attention?

Don’t fight it, just write it.
Don’t shout it, recite it.

Keep on the work,
Leave the thoughts behind it.

Features

* Schedule thoughts to resurface later through timers
* Organize related thoughts into structured Thought Trains
* Lightweight macOS menu bar application
* Keyboard shortcut support
* Minimal and distraction-free design

Thought Types

ClockedThoughts keeps things simple with two types of thoughts:

■ Random Thoughts

Random thoughts are represented by a square icon.

These are standalone thoughts that can be scheduled using a custom timer. They are not connected to any train and will appear independently at the time you choose.

● Thought Trains

Thought Trains are represented by a circle icon.

Thought Trains allow related thoughts to stay connected and appear in a structured order instead of becoming a random collection of reminders.

Thought Trains

Not every thought is random.

Sometimes multiple thoughts are related and should appear in a specific order. Instead of manually calculating reminder times for every thought, ClockedThoughts allows you to create a Thought Train.

A Thought Train is a chain of connected thoughts where each new thought is scheduled relative to the previous thought in the train.

When a train does not yet exist, the first Train Trail thought attaches itself to the most immediate existing thought, regardless of whether that thought was created using a custom timer or another reminder.

Once a train exists, future Train Trail thoughts attach to the end of that train rather than to unrelated thoughts.

For example:

* You have a thought scheduled to appear in 5 minutes.
* You create a Train Trail thought with a 5-minute delay.
* The Train Trail thought will appear 5 minutes after that existing thought.

Now a train has been created.

If you create another Train Trail thought with a 6-minute delay, it will attach to the end of the train and appear 6 minutes after the previous Train Trail thought—not 6 minutes from the current time.

This allows you to build a structured sequence of reminders where related thoughts naturally appear one after another without requiring you to manually calculate exact reminder times.

New Train

Sometimes your current train becomes very long.

For example, you may already have a train containing several thoughts, with the final thought scheduled 40 minutes in the future.

If you continue using Train Trail, every new thought will attach to the end of that train and won’t appear until all earlier train thoughts have been shown.

That’s where New Train becomes useful.

New Train starts an entirely new train and creates a new train head.

For example:

* You create a New Train thought with a 5-minute timer.
* That thought becomes the head of a new train.
* Any future Train Trail thoughts will attach to that new train instead of the older one.

If you then create another Train Trail thought with a 5-minute delay, it will appear 5 minutes after the New Train thought.

This allows you to maintain multiple independent chains of related thoughts while ensuring new, more urgent ideas don’t get buried behind older trains.

If no thoughts currently exist, Train Trail and New Train behave the same way because both create the first thought in a train.

Keyboard Shortcuts

Shortcut	Action
Option + =	Show or hide the ClockedThoughts bubble
Option + Control + =	Open the ClockedThoughts popup menu
Command + C	Copy the currently displayed thought

Installation

1. Download the latest release from the Releases page.
2. Extract the ZIP file.
3. Move ClockedThoughts.app to Applications.
4. Open the application.

Feedback

If you encounter a bug, have a feature request, or have ideas for improving the app, feel free to open an Issue on GitHub.
