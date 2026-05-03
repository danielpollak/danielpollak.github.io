# Tangonogo

### Go/No-go + tango
In the middle of Tango practica, my teacher told a follower not to do a move unless it was led. "It's a go/no-go task" I said under my breath, and then I couldn't focus for the rest of practica.

Go/no-go tasks are the workhorse experimental paradigm for studying decision-making. Much like the concept of decision making itself, these experiments are usually really uninspired. They go like this: if you get a "go" cue, (say a green light), you should operate on your environment by taking some action, like pressing a lever. If you get a "no-go" cue (red light), and you press a lever, you are punished somehow. This is done on everything from mice to rats to monkeys to humans to computer programs.

Examples of Go/no-go cues:
1. green light/red light (color)
2. high pitch beep/low pitch beep (sound)
3. long interval between beep/short interval between beep (time)
4. 135 degree grating / 45 degree grating (orientation)
5. raspberries / bananas (smell)
6. smiling face / confused face (emotion)
7. correct equation (1+6/3=3) / incorrect equation (1+6/2=3) (equivalence)
8. Increase in temperature / decrease in temperature (sign of change)

Examples of rewards/punishments
1. You get money / you lose money
2. You drink juice / you wait to play again for (timeout) 
3. You get to see a bird (you're also a bird) (social reward) / you have to wait to play again for the chance to see a bird (timeout)
4. You get water (thirst alleviation) / You have to wait to play again for water (timeout)
5. Any reward / foot shock (pain)
6. Cocaine (hedonism) / no cocaine

you get the picture

I've never understood the point of decision making as a field. Decision making, as I understand it, is a thing that humans do maybe a few times a day: What should I wear? Should I save some money? Should I go up to that attractive person? Should I speak up? Decisions are hardest, most fulfilling, and challenging when the outcome, the reward, is uncertain, and not immediate.

Usually the threat of negative repercussions is very immediate: you get on the train and realize you're outfit is ugly, you saved too much; not enough for expenses, attractive person is repulsed, you are punished for speaking up.

The upside ranges from zero to incredible. You forget what you're wearing for the rest of the day, or you get complimented by an attractive person on your outfit. You forget you put money away, or you quickly realize you budgeted well this month. The attractive person turns out to have an annoying voice, or you fall in love. Everyone forgets what you said, or you avert disaster with your words.

Repercussions are immediate and severe and rewards are slow and unclear. Why do we keep bothering? What goes into taking such a long term risk?

Compare that with decision making experiments in mice. If a mouse makes a "correct decision", it is immediately rewarded with food. If it makes an "incorrect decision", it is punished with a time-out (exactly what it sounds like, it gets put in time out and has to endure boredom). If it fails to react to a "go" cue, it loses out on an immediate reward. If it heeds the "no-go" cue, it avoids immediate punishment. Why does the mouse keep bothering? Because it has no choice, it's stuck in this stupid experimental chamber until the researcher takes it out.

The go/no-go paradigm does not reflect decision making, it reflects video game play. In video games, you get rewarded immediately for acting correctly, and you get put in time out if you act incorrectly. Videos games take up an inordinate amount of young people's time, so maybe we should learn something about it, but the field is not called "video games for mice", it's called decision making.

I know my neuroeconomics and cognitive psychology friends will decide now is the time speak up for their fields. I will preemptively acknowledge and dismiss their fields, as I am not in it. I am in neuroscience, a field that is supposedly interested in the mechanism underlying decision making, and continuously failing to learn anything about it. There is no reward and no punishment for speaking up about this.

Back to practica. I couldn't focus because, see above, the neuroscience of decision-making as a field sucks. Their go-to task does not have anything to do with real life, but it fulfills the various desiterata of a good neuroscience experiment. 

Desideradum number 1: You can get a ton of trials; you get get a ton of data
- it's true. Mice will do some tasks dozens of times per day

Desideradum number 2: It's easily interpretable
- the interpretation usually lies along the lines of "the mouse learned the task! mice can learn this task!"
- Note: performance rarely goes above 85% in most tasks. Either a mouse knows the task or doesn't, yet there is unexplained variability in most tasks. There have been attempts to understand this issue, but most practitioners proceed without heed.

Desideradum number 2.5: There is a discrete behavior
- The fact remains that even though seconds are universally accepted as the universal building block of time, some things last 1.2 seconds. At the macro scale, the world isn't perfectly binned into lovely discrete packages in space and time (don't @ me physicists, I said macro), and neither is behavior, dang nabbit. That doesn't stop our intrepid neuroscientists from chopping up the mysterious confluence of continuous overlapping experiences, actions, and thoughts that we call consciousness into discrete little packages that fit into a peristimulus time histogram. 
- So it would really be better if we could skip all that messy "being alive and conscious stuff" [1] and invent a behavior that can be repeated and takes the exact some amount of time every time. Enter "go/no-go".

Desiteradum number 3: It's easy to implement
- You get an arduino, a multicolor LED (the cue), a button (the lever), a sugar water port (the reward), and a taser (kidding). Boom, done, all off the shelf. In fact, you can just buy a pre-made box that does it for you.

Except this isn't a real decision. There's no long term stakes. Compare that with partner dancing. 

Desiteradum number 1: You can get a ton of trials
- fulfilled. Literally every beat of music is a trial. The dancers are feeling for anything the other one does, and correct their weight, posture, etc, in real time. For reference, a song has about 200 beats.

Desiteradum number 2: It's easily interpretable. 
- actually, yes. You can play a video of a dance back to a dancer and they can tell you how it felt, beat-by-beat. A reasonably experienced dancer can do the same thing by just watching a video
- What kind of interpretation does this allow? Say two people have never danced together. Over the course of a dozen beats, two experienced dancers can "learn the task". Here, learning the task means inferring multiple go/no-go cues. What is the reward? There's a short term, and a long-term reward. In the short term, you have as many opportunities for rewards as you have trials, and you have at least 200 trials in a single song. The long-term reward is a deepening of your emotional connection with your partner, with the dance, and with the rewards themselves: as you become better at dancing with someone, the steps become more enjoyable.

Desiteradum number 2.5: It's a discrete behavior
- Two high level dancers experience a song, or a sequence of songs, or an evening of dancing, as a temporally sequential experience, but the sequence is hierarchically organized. Experienced dancers experience multiple things in a single beat, as well as a larger scale experience over the course of a measure, over a song, a tanda (four songs played in sequence at tango events called Milongas), and even the composition of tondas over the course of an evening. Thus, a dancer can look back and say how they felt about a single step within a song, as well as a review of an overall tanda. [2]

Desiteradum number 3: It's easy to implement
- You're never gonna believe this. It's easy. Here's how you do it. Get two video cameras, one for capturing a room from two angles. Get two tango dancers. Get two inertial measurement units and stick one on each dancer's left angle.
- Then, play some music. Record the video and the ankle accelerations. Ask the dancers to review the footage and report what went well, what went poorly, what the follower didn't expect, what the follower liked, and what the follower didn't like. Do the same for the leader if you want. 
- Now for the neuroscience. Record EEGs from a few choice locations along the dancers' scalps. While mostly uninterpretable, EEGs do have a few key signals that are large and repeatable enough to do something with. Like, the P300, the surprise signal. What kinds of things signal surprise? Can you decode surprise (ground truth being the step-by-step human report of the dance) based on EEG? How do these signal appear throughout the dance, and what kinds of moves elicit them? In a high-learning paradigm, some signals may appear once or twice, which is risk. But some might be incredibly common. Some event related potentials (ERPs) you could find, and how you might interpret them:

1. P300: a positive deflection 300 ms after an unexpected stimulus, this event might occur in a time-locked manner relative to certain accelerations, either linear or angular.
2. N270: Incongruity signal, may occur in response to a move executed in an unfamiliar or unexpected way
3. N400: Semantic incongruity/meaning. Dances between people are is often described as meaningful. It's an emotionally expressive medium. Emotions are expressed through communication of semantic meaning between people. Maybe dance, at a high level between people, uses language centers.
4. P600: grammatical reassessment. Another of many language related ERPs.

The list goes on. Here's a screenshot of the wikipedia page for P600s. 
<img width="1608" height="642" alt="image" src="https://github.com/user-attachments/assets/9e15370a-df8b-400a-9f6f-e8e226a6571a" />

There's a lot of insights about behavior in general, and human behavior in particular, waiting to for us. I just wish we could look outside the bounds of usual kinds of experiments to apply our frameworks. 


[1] I don't give a solitary shit about the question of consciousness. I just mean that brains do stuff on a continuous spectrum of scales in time, space, and frequency to give rise to behavior, and that's the kind of stuff we should build our experiments around.
[2] By no means am I an experienced tango dancer. I say this about experienced tango dancers based on what such people have shared with me.
