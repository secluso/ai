# Secluso AI

Home of our custom trained models.

The following are being worked on in a separate private repository. We will release open-source versions of these as they come about in the form of **weights**. 

1) **"Sight"** - Person / pet / vehicle detection. We currently use NanoDet-Plus for this, and while that works decently, we've made significant strides in developing a custom implemnetation. We've successfully achieved higher efficiency and better accuracy doing this ourselves.

2) **"Flow"** - Activity understanding over time. "Approaching the door", "walking across the room", "pacing"

3) **"Story"** - A human readable summary (NLP) of a video clip. "A person walked up to the front door carrying a package and remained there briefly"

4) **"Echo"** - Detect meaningful sound-related events (barking, glass breaking, alarm, knocking..)

5) **"Presence"** - Reason about familiarity / recurrence of people or entities. Essentially, determine whether someone appears familiar. Outputs: "familiar visitor", "unknown visitor", "recurring person"

6) **"Signal"** - Decide how important an event is. Example: unknown person at night > familiar person in daytime

7) **"Frame"** - Understand the scene itself. Classify the broader environmental context (indoor/outdoor), (wide-room vs close-up), (living room / porch / hallway)... 

All of these will work together in a pipeline. 

These will not all work natively on a Raspberry Pi due to hardware constraints.
- Some may only work on our custom board we've been working on with an edge AI processor.
- Some may only work on our future AI hub product.
- We will support self-hosting if you happen to have a local machine with a powerful GPU handy.

More to come soon.
