## SpecStory

## Adding Delays in Twine Stories (9/16/2024, 7:51:08 AM)

_**User**_

So I need to add delays, right?

---

_**Assistant**_

Yes, you can add delays to your Twine story to create pauses between actions or to give the reader time to absorb the information. In Twine, you can use the `<<timed>>` macro to add delays. Here’s how you can incorporate delays into your existing story:

```Twine/CSTP/source/main.tw
:: Start
<<set $arm_rising_score to 0>>
<<set $hand_lock_score to 0>>
<<set $book_hallucination_score to 0>>
<<set $amnesia_score to 0>>

<<set $arms_apart_score to 0>>
<<set $hearing_voice_score to 0>>
<<set $head_lowering_score to 0>>
<<set $test_amnesia_score to 0>>

<<set $arm_rising_subjective to 0>>
<<set $hand_lock_subjective to 0>>
<<set $book_hallucination_subjective to 0>>
<<set $amnesia_subjective to 0>>

<<set $arms_apart_subjective to 0>>
<<set $hearing_voice_subjective to 0>>
<<set $head_lowering_subjective to 0>>
<<set $test_amnesia_subjective to 0>>

<<set $total_training_score to 0>>
<<set $total_test_score to 0>>
<<set $total_score to 0>>

[[Introduction|Introduction]]

:: Introduction
You have been chosen for this study because you have shown low susceptibility in a previous hypnosis session. We believe that people show low responsiveness to suggestions because they are not quite sure how they should be thinking or acting in response to suggestions. Research has shown that instruction and practice can significantly increase an individual's responsiveness. So today's session is a practice/training session.

<<timed 5s>> The procedure is this: First you will first go through a lengthy introduction to hypnosis. It will outline some of the myths and misconceptions of hypnosis. For example, hypnosis is not a trance state, there is no loss of control, no loss of consciousness. The person responding to suggestions is in complete control, very aware of his/her mind and body. In fact, the person who is responding hypnotically is probably more aware and more in control of directing his or her mind than at any other time during the day.

[[Continue|Intro_1]]

:: Intro_1
Remember how in old movies the hypnotist would have the subject fixate on a dangling pocket watch? As the subject followed the watch with his or her eyes, the hypnotist would suggest repeatedly in a low voice something like: "You are becoming sleepy; your eyelids are getting heavier and heavier and are closing, closing completely; you want to go to sleep; you are falling into a deep, deep sleep." In one form or another, these instructions are still presented by hypnotists to their subjects today. You may recall that in your last session in this lab, you were presented with these kinds of instructions, albeit without the watch. You were repeatedly told by the voice on the tape recorder that you were falling into a deep sleep.

<<timed 5s>> [[Continue|Intro_2]]

:: Intro_2
It was once commonly believed that giving subjects repeated instructions to go to sleep would cause them to go into a hypnosis trance. When in this trance, the subject was believed to come under the direct control of the hypnotist. The hypnotist was believed to take over the hypnotized subject's mind and body to do practically anything. The subject was thus viewed as an automaton or robot, fully subject to the commands of the hypnotist. This view of hypnosis is one of the great misconceptions in the history of psychology. Subjects in a hypnosis session are, in fact, fully awake and are in full control of all their actions.

<<timed 5s>> [[Continue|Intro_3]]

:: Intro_3
The repeated instructions for sleep do not cause you to go into a "trance" in which you "lose control of your actions" and become a "robot." No such hocus-pocus is involved in hypnosis. Hypnosis has nothing whatsoever to do with any loss of consciousness, trances, or a loss of control. Far from involving a loss of control, hypnosis actually involves a skill that is within the full control of the individual. It is a skill that anyone can learn and master, if given proper instructions and enough practice. In this sense, it is no different than learning the skills required to ride a bicycle, to swim, or to solve mathematical problems. The repeated instructions for sleep simply serve the purpose of enabling you to relax and put your mind on learning the hypnotic skill. Few people are ever taught the hypnotic skill, and as a consequence, few people are able to produce hypnotic responses. Asking the subject who has never learned the hypnotic skill to respond hypnotically is similar to asking a person who has never learned to swim to swim the length of a pool. Clearly, the non-swimmer has to first learn how to swim before being able to swim the length of the pool. Similarly, the subject who has never learned the hypnotic skill has to first learn this skill before being able to produce hypnotic responses.

<<timed 5s>> [[Continue|Intro_4]]

:: Intro_4
In order to enable you to learn the hypnotic skill, I am going to show you exactly what this skill involves and then give you plenty of opportunities to practice it. Learning the hypnotic skill is fully within the capabilities of normal individuals, provided they know just what it is they must do. In fact, research shows that any well-adjusted person of your age is fully able to learn the hypnotic skill, provided he or she puts forth sufficient effort. As with learning any new skill, learning this skill is completely within your control and is quite rewarding to master. In addition, individuals who learn the hypnotic skill find it a very interesting experience.

<<timed 5s>> [[Continue|Intro_5]]

:: Intro_5
What the hypnotic skill involves is that you make believe something. Before I describe this skill in more detail, let me give you an example. You are probably familiar with the Charlie Brown comic strip. In it, Charlie Brown's dog, Snoopy, is often pictured sitting on his doghouse wearing a helmet and a scarf, paws outstretched, and gritting his teeth. Snoopy gets deeply involved in a make-believe situation. He imagines himself to be in a situation in which he is a World War I flying ace in the air somewhere over Germany, in hot pursuit of the Red Baron. He gets so involved in his make-believe actions that, for the moment, he actually believes he's flying an airplane somewhere over Germany. He simply forgets that he's really a dog on a doghouse. It's plain to see that Snoopy is in total control of his actions.

<<timed 5s>> [[Continue|Intro_6]]

:: Intro_6
Let us more carefully analyze what Snoopy is doing. First off, he himself creates an entire make-believe situation. He does this through the direct control of his imagination. He actively imagines such things as the clouds around him, his or her own airplane and that of the Red Baron's, the roar of the engines, and everything else that is part of such a situation. In short, through his imagination, which he is in direct control of, he creates an entire make-believe situation.

<<timed 5s>> [[Continue|Intro_7]]

:: Intro_7
However, it is important to understand that the hypnotic skill involves more than simply imagining a particular situation. A further analysis of the Snoopy example will illustrate what I mean. Snoopy did something more than simply create a new situation. He went one step further and actually became a part of that situation. He completely replaced the situation he was in formerly with a new one. He let the "World War I" situation completely replace the one in which he was merely "a dog on a doghouse." This had the interesting effect of making the "World War I" situation seem real because it was the only one to which Snoopy was directing his attention. According to modern psychology's definition of hypnosis, Snoopy was hypnotized because he was so preoccupied with his imaginings of the make-believe that he forgot they were make-believe.

<<timed 5s>> [[Continue|Intro_8]]

:: Intro_8
This skill is therefore not unusual nor mysterious. It's a rather common occurrence and is what is meant when someone is said to be "absorbed", or "deeply involved", or "really into" their thoughts and imaginings. This skill is, of course, totally within your control, for you can initiate or terminate it whenever you like. To further illustrate the degree of control you have in hypnosis, think of what young children are like when they play. Needless to say, they quite readily get involved in the make-believe. Nonetheless, even children possess the ability to shift from the real to the imaginary world and back again whenever they like. For instance, when mother beckons that supper is ready, a child easily shifts his or her attention from the make-believe world to the real-world goal of satisfying his or her hunger.

<<timed 5s>> [[Continue|Intro_9]]

:: Intro_9
It's worth noting that we never lose our skill at becoming deeply involved in our imaginings of make-believe. For one reason or another, however, we simply do not do it as much as children do. At any rate, you will no doubt be surprised at how good you are at this skill. Our research suggests that you will get better and better at it the more you get a chance to practice.

<<timed 5s>> [[Continue|Intro_10]]

:: Intro_10
Now, what are you going to make believe? You will not be asked to do things as extreme or as potentially embarrassing as being a World War I flying ace or a famous movie star. Instead, you will be asked to involve yourself in some simple make-believe actions of a non-embarrassing kind. Soon you will be presented with some suggestions, four in all, not much different from the ones you were presented with the last time you were in the lab. It is these suggestions that will provide you with the make-believe situation you will involve yourself in.

<<timed 5s>> [[Continue|Intro_11]]

:: Intro_11
The first suggestion you will be presented is an arm-rising suggestion. It will inform you of exactly what it is you are to make believe. It will specifically tell you that your arm is like a hollow balloon being pumped up with helium, and that the helium being pumped in makes your arm so light that it rises into the air by itself. In response to this suggestion, you must do everything that is required of someone making believe such a thing; you must lift your arm up, and you must imagine the helium, and anything else you wish to imagine that is consistent with such a make-believe situation.

<<timed 5s>> [[Continue|Intro_12]]

:: Intro_12
Of course, your arm will not really go up by itself. You must raise it. However, you can make it feel like it is going up by itself by focusing on the make-believe situation that your arm is hollow and being filled with helium. As long as you focus and elaborate on this make-believe situation and do not let yourself think about other things, the arm will feel like it is going up by itself. You must become very deeply involved in the make-believe and actually make it seem real. Becoming involved requires that you keep your attention only on the things the suggestion tells you to imagine. You must rivet your attention on the hollow arm, its lightness, the fact that it's going up by itself, and so on. Don't imagine or pay attention to anything that is unrelated to the make-believe situation. Attending strongly to imaginings of the make-believe situation only will help prevent the possibility of irrelevant thoughts entering your mind and shaking you out of the make-believe world.

<<timed 5s>> [[Continue|Intro_13]]

:: Intro_13
Before you are given an opportunity to respond to this suggestion, you will be shown a videotape of another subject responding to it. When this subject's responses were taped, she had already gone through a good deal of practice at responding to this suggestion and several others. I am presenting you with her responses to give you a clearer idea of how to properly respond to this suggestion. When I roll the tape, you will observe that the subject verbalizes many of her thoughts aloud. She was asked to do this as a means of illustrating to viewers, such as yourself, that all of her thoughts and imaginings during the suggestion are on the make-believe situation, and on nothing else.

<<timed 5s>> [[Continue|Arm_Rising_Model]]

:: Arm_Rising_Model
(PLAY VIDEOTAPE OF MODEL)
H: Now, please extend your right arm straight out in front of you at shoulder height. Pay close attention to this arm, notice that it feels tingly and slightly numb. Notice too that it is beginning to feel lighter. Your arm is beginning to feel lighter and lighter, and as it feels lighter, it begins to rise into the air.

Imagine that your arm is like a balloon. Imagine that air is being pumped into it making it feel lighter and lighter. Your arm feels lighter and lighter, lighter and lighter, and, like a balloon it rises higher and higher, higher and higher into the air. It is rising, rising, getting lighter and lighter, rising higher and higher.

M: It's going up by itself. If feels hollow. I can see the pump. I can feel the arm being pumped up. It's really light. It's moving up by itself. It just keeps getting lighter and is going up by itself. It's just getting lighter and lighter.

<<timed 5s>> [[Continue|Arm_Rising]]

:: Arm_Rising
<<set $arm_rising_attempts to 0>>
Now, please extend your right arm straight out in front of you at shoulder height. Pay close attention to this arm, notice that it feels tingly and slightly numb. Notice too that it is beginning to feel lighter. Your arm is beginning to feel lighter and lighter, and as it feels lighter, it begins to rise into the air.

Imagine that your arm is like a balloon. Imagine that air is being pumped into it making it feel lighter and lighter. Your arm feels lighter and lighter, lighter and lighter, and, like a balloon it rises higher and higher, higher and higher into the air. It is rising, rising, getting lighter and lighter, rising higher and higher.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically raise your arm, but it should feel like it's going up by itself because of your mental imaginings. Concentrate on a mental image consistent with the suggestion, such as:

• Your arm being pumped up with helium, becoming hollow and light
• Colorful balloons attached to your arm, gently pulling it upward
• A pulley system slowly and steadily lifting your arm
• Your arm floating in water, effortlessly rising to the surface
• A warm updraft of air lifting your arm like a feather

As you focus on these images, let the physical movement of your arm rising reinforce the mental image, which in turn reinforces the physical movement. This feedback loop should create a feeling of lightness and the sensation that your arm is rising by itself.

<<timed 5s>> [[Your arm rises at least six inches|Arm_Rising_Score]]
<<timed 5s>> [[Your arm rises less than six inches|Arm_Rising_Troubleshooting]]

:: Arm_Rising_Score
<<set $arm_rising_score to $arm_rising_score + 1>>
<<set $arm_rising_subjective to 0>>
How would you rate your experience of the arm rising suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Arm_Rising_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Arm_Rising_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Arm_Rising_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Arm_Rising_Subjective_D]]

:: Arm_Rising_Subjective_A
<<set $arm_rising_subjective to 3>>
[[Continue|Hand_Lock_Pref1]]

:: Arm_Rising_Subjective_B
<<set $arm_rising_subjective to 2>>
[[Continue|Hand_Lock_Pref1]]

:: Arm_Rising_Subjective_C
<<set $arm_rising_subjective to 1>>
[[Continue|Hand_Lock_Pref1]]

:: Arm_Rising_Subjective_D
<<set $arm_rising_subjective to 0>>
[[Continue|Hand_Lock_Pref1]]

:: Arm_Rising_Troubleshooting
<<set $arm_rising_attempts to $arm_rising_attempts + 1>>
If you are having trouble raising your arm, try these helpful hints:
• Take a deep breath and notice how your upper body moves. As you inhale, let your arm rise a bit, and on the exhalation, allow it to rest. Try raising it more on the next inhale.
• Imagine your arm being pumped up with helium or attached to balloons. Some people find this easier to visualize. You can also imagine your arm floating in water or being lifted by a pulley or any other situation that might occur to you and resonate. It can often be good to be playful.
• Focus on the sensation of lightness in your arm. Imagine it getting lighter and lighter until it feels like it is floating up by itself.
• Keep your arm relaxed and loose. Tension can make it feel heavier, so try to keep it as light and relaxed as possible.

<<timed 5s>> [[Try Again|Arm_Rising_Retry]]

:: Arm_Rising_Retry
<<if $arm_rising_attempts < 2>>
Let's try the arm rising suggestion one more time. Remember to focus on the sensation of lightness and the image of your arm floating upward.

<<timed 5s>> [[Your arm rises at least six inches|Arm_Rising_Score]]
<<set $arm_rising_score to $arm_rising_score + 1>>

<<timed 5s>> [[Your arm rises less than six inches|Arm_Rising_Troubleshooting]]
<<else>>
That's okay, you *are* fighting against gravity. Let's move on to the next suggestion.
[[Continue|Hand_Lock_Pref1]]
<</if>>

:: Hand_Lock_Pref1
The next suggestion is the hand-lock suggestion. It will tell you just what you are to make believe. It will initially tell you to fold your hands. Then it will tell you to imagine that your hands are really two hunks of steel that are welded together. Following this, the suggestion will challenge you to pull the hands apart. Despite this challenge, don't pull the hands apart. Instead, make believe that the hands are so tightly welded together that despite your best efforts, you simply cannot get them apart.

<<timed 5s>> [[Continue|Hand_Lock_Pref2]]

:: Hand_Lock_Pref2
Remember what the hypnotic skill involves. You must let yourself become so deeply involved in the make-believe that it actually seems real. Do this by only imagining and thinking of things that are connected with the make-believe situation.

<<timed 5s>> [[Continue|Hand_Lock_Model

---

_**User**_

Your response got cut off, because you only have limited response space. Continue writing exactly where you left off. Do not repeat yourself. Start your response with: "s>> [[Continue|Hand_Lock_Model", though use backticks where appropriate

---

_**Assistant**_

```Twine/CSTP/source/main.tw
s>> [[Continue|Hand_Lock_Model]]

:: Hand_Lock_Model
(PLAY VIDEOTAPE OF MODEL)

H: Place your hands on the table and clasp them together, interlacing the fingers. (PAUSE) Imagine that your hands are two pieces of steel that are welded together so that it is impossible to get them apart. They are two pieces of steel welded together. When I ask you to pull your hands apart, they'll be stuck and won't come apart no matter how hard you try." (WAIT 20 SECONDS)
M: They're really stuck together. This is impossible. They're welded together. They're just two hunks of steel welded together. I can't get them apart.
H: Okay, relax. Your hands are no longer stuck together. You can pull them apart.

<<timed 5s>> [[Continue|Hand_Lock]]

:: Hand_Lock
<<set $hand_lock_attempts to 0>>
Place your hands on the table and clasp them together, interlacing the fingers. Imagine that your hands are two pieces of steel that are welded together so that it is impossible to get them apart. They are two pieces of steel welded together. When I ask you to pull your hands apart, they'll be stuck and won't come apart no matter how hard you try until you count down till 20 seconds when they can relax.

Remember to focus on the sensation of your hands being fused together, heavy and immovable. You might imagine:

• Your hands as cold, heavy blocks of steel welded at the seams
• A strong adhesive binding your hands together
• Heavy chains or ropes tightly wrapping around your clasped hands
• Your hands becoming one solid piece, like a sculpture

As you concentrate on these images, allow yourself to feel the weight and the tightness in your hands. Press down slightly with your fingers and palms to create a tension that reinforces the feeling of being stuck.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically keep your hands together, but it should feel like they're stuck together because of your mental imaginings.

<<timed 5s>> [[Your hands feel stuck together|Hand_Lock_Score]]
<<timed 5s>> [[Your hands do not feel stuck together|Hand_Lock_Troubleshooting]]

:: Hand_Lock_Score
<<set $hand_lock_score to $hand_lock_score + 1>>
<<set $hand_lock_subjective to 0>>
How would you rate your experience of the hand lock suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Hand_Lock_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Hand_Lock_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Hand_Lock_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Hand_Lock_Subjective_D]]

:: Hand_Lock_Subjective_A
<<set $hand_lock_subjective to 3>>
[[Continue|Book_Hallucination_Model_Pref1]]

:: Hand_Lock_Subjective_B
<<set $hand_lock_subjective to 2>>
[[Continue|Book_Hallucination_Model_Pref1]]

:: Hand_Lock_Subjective_C
<<set $hand_lock_subjective to 1>>
[[Continue|Book_Hallucination_Model_Pref1]]

:: Hand_Lock_Subjective_D
<<set $hand_lock_subjective to 0>>
[[Continue|Book_Hallucination_Model_Pref1]]

:: Hand_Lock_Troubleshooting
<<set $hand_lock_attempts to $hand_lock_attempts + 1>>
If your hands don't feel stuck together, try focusing on these suggestions:
• Imagine your hands as cold, heavy blocks of steel that are welded together. Feel the weight and the tightness in your hands.
• Press down slightly with your fingers and palms to create a tension that reinforces the feeling of being stuck. The slight pressure will make it easier to feel like your hands cannot be separated.
• Don't try too hard—let the feeling of being welded happen naturally without forcing it.
• Visualize your hands being glued together or bound by heavy string or chains. Imagine the sensation of the glue or bindings holding your hands together tightly.

<<timed 5s>> [[Try Again|Hand_Lock_Retry]]

:: Hand_Lock_Retry
<<if $hand_lock_attempts < 2>>
Let's try the hand lock suggestion one more time. Remember to focus on the sensation of your hands being fused together, heavy and immovable.

<<timed 5s>> [[Your hands feel stuck together|Book_Hallucination_Model_Pref1]]
<<set $hand_lock_score to $hand_lock_score + 1>>

<<timed 5s>> [[Your hands do not feel stuck together|Book_Hallucination_Model_Pref1]]
<<else>>
Let's move on to the next suggestion.
[[Continue|Book_Hallucination_Model_Pref1]]
<</if>>

:: Book_Hallucination_Model_Pref1
The next suggestion will tell you that you see a book on the desk in front of you even though there is really no book there. The suggestion will start out by telling you to close your eyes and that the book is on the desk in front of you. It will suggest that you see the book once you open your eyes. The suggestion will then instruct you to open your eyes and actually see the book.

<<timed 5s>> [[Continue|Book_Hallucination_Model_Pref2]]

:: Book_Hallucination_Model_Pref2
In response to this suggestion, you are to make yourself see the book, and in addition, make believe that the book you are seeing is physically there and part of the natural setting of the room, not simply something you are artificially making appear. The main idea is to make the book you see seem like a natural part of the room. Just let yourself become totally involved in making believe that the book is really there.

<<timed 5s>> [[Continue|Book_Hallucination_Model_Pref3]]

:: Book_Hallucination_Model_Pref3
There is another thing. Towards the end of the suggestion, you will be asked to push the book off to the side. This action is also part of the make-believe. Even as you do it, continue to make believe there is really a book there.

<<timed 5s>> [[Continue|Book_Hallucination_Model]]

:: Book_Hallucination_Model
(PLAY VIDEOTAPE OF MODEL)
H: Place your hands on your lap and close your eyes. (PAUSE) I'm not sure if you've noticed, but there is a book of mine on the desk in front of you. It is an average-sized book, one like hundreds you've seen. It is right there in front of you on the desk. Open your eyes and look at the book sitting there on the desk. (WAIT 20 SECONDS) To avoid the book being in your way, why don't you just slide it off to the side. (WAIT 20 SECONDS) The image of the book is now fading. It has faded completely and you can no longer see the book.

M: There it is. I can see it on the desk. I see the book sitting there. It's kind of vague and fuzzy ... a vague, coloured outline of the book; but it's there.

H: To avoid the book being in the way, why don't you just slide it off to the side. (WAIT 20 SECONDS)

M: I'll just push it over there and get it out of the way.

H: The image of the book is now fading. It's faded completely and you no longer see the book.

<<timed 5s>> [[Continue|Book_Hallucination]]

:: Book_Hallucination
<<set $book_hallucination_attempts to 0>>
Place your hands on your lap and close your eyes. I'm not sure if you have noticed, but there is a book of mine on the desk in front of you. It's an average size book, one like hundreds you've seen. It's right there in front of you on the desk. Open your eyes and look at the book sitting there on the desk.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically look at the desk and imagine the book, but it should feel like the book is really there because of your mental imaginings. Concentrate on a mental image consistent with the suggestion, such as the book's size, color, title, and position on the desk.

As you focus on these images, let the physical act of looking at the desk reinforce the mental image, which in turn reinforces the physical act. This feedback loop should create a feeling of seeing the book and the sensation that it is really there.

<<timed 5s>> [[You see the book|Book_Hallucination_Score]]
<<timed 5s>> [[You do not see the book|Book_Hallucination_Troubleshooting]]

:: Book_Hallucination_Score
<<set $book_hallucination_score to $book_hallucination_score + 1>>
<<set $book_hallucination_subjective to 0>>
How would you rate your experience of the book hallucination suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Book_Hallucination_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Book_Hallucination_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Book_Hallucination_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Book_Hallucination_Subjective_D]]

:: Book_Hallucination_Subjective_A
<<set $book_hallucination_subjective to 3>>
-The image of the book is now fading. It's faded completely and you no longer see the book.
[[Continue|Suggestion_To_Forget_Model_Pref_1]]

:: Book_Hallucination_Subjective_B
<<set $book_hallucination_subjective to 2>>
-The image of the book is now fading. It's faded completely and you no longer see the book.
[[Continue|Suggestion_To_Forget_Model_Pref_1]]

:: Book_Hallucination_Subjective_C
<<set $book_hallucination_subjective to 1>>
-The image of the book is now fading. It's faded completely and you no longer see the book.
[[Continue|Suggestion_To_Forget_Model_Pref_1]]

:: Book_Hallucination_Subjective_D
<<set $book_hallucination_subjective to 0>>
-The image of the book is now fading. It's faded completely and you no longer see the book.
[[Continue|Suggestion_To_Forget_Model_Pref_1]]

:: Book_Hallucination_Troubleshooting
<<set $book_hallucination_attempts to $book_hallucination_attempts + 1>>
If you are having trouble seeing the book, try these tips:
• Picture a simple book or magazine that you are familiar with. You can even imagine a book from home or one you study with often. Simplify the cover if the details are too complex.
• Focus on one detail at a time, such as the color of the cover, the title, or the position of the book on the table. Picture the book as clearly as possible.
• Remember, it's like playing make-believe—act as though the book is really there, just like children pretending a lawn is divided into different rooms.
• Imagine the texture and weight of the book. Think about how it would feel to touch and move it.

<<timed 5s>> [[Try Again|Book_Hallucination_Retry]]

:: Book_Hallucination_Retry
<<if $book_hallucination_attempts < 2>>
Let's try the book hallucination suggestion one more time. Remember to focus on creating a vivid mental image of the book on the desk in front of you.

<<timed 5s>> [[You see the book|Suggestion_To_Forget_Model_Pref_1]]
<<set $book_hallucination_score to $book_hallucination_score + 1>>
-The image of the book is now fading. It's faded completely and you no longer see the book.

<<timed 5s>> [[You do not see the book|Suggestion_To_Forget_Model_Pref_1]]
<<else>>
Let's move on to the next suggestion.
[[Continue|Suggestion_To_Forget_Model_Pref_1]]
<</if>>

:: Suggestion_To_Forget_Model_Pref_1
The next suggestion is one that will tell you that you are forgetting something you know. Specifically, the suggestion will state that the memories of the suggestions you were presented earlier in this session are fading completely from your mind. The suggestions I am referring to, of course, are the arm-rising suggestion, the hand-lock suggestion, and the suggestion to see the book.

In response to the suggestion to forget, you are to make yourself forget the other suggestions. Do this by concentrating deeply on something other than the memories, thereby distracting yourself from them. By distracting yourself in this manner, you will be unable to remember the suggestions.

The suggestion to forget also requires that you make believe that the suggestions are actually fading from your memory all by themselves and that you are doing nothing to make them go away. Therefore, you are to make believe that your forgetting is something that just happens to you, not something that you are causing.

<<timed 5s>> [[Continue|Suggestion_To_Forget_Model_Pref_2]]

:: Suggestion_To_Forget_Model_Pref_2
As usual, you are to become deeply involved in this make-believe. Only attend to the make-believe situation; namely, that your memories of the suggestions are just fading away by themselves.

There is another matter. At one point in the suggestion, you will be challenged to remember the suggestions and write them down on a piece of paper. Despite this challenge, you are to continue to distract yourself from the suggestions while making believe you really cannot remember them. The challenge is all part of the make-believe situation. It is meant to further establish the fact that, despite your best efforts to remember the suggestions, you simply cannot; they're gone.

To summarize, your task is to become so deeply involved in the make-believe that you don't notice that it's really you who is preventing the recall of the memories.

Following the challenge to remember the suggestions, there will be a one-minute pause in which you will be able to write down any of the suggestions that you remember. This, in turn, will be followed by the cancellation of the forgetting, that is, the voice will say that you can remember the suggestions again. Once this is done, you will be asked again to write the suggestions down on another piece of paper that will be provided. It will be all right at this point to stop distracting yourself, stop making believe, and actually write down the names of the suggestions on the paper.

<<timed 5s>> [[Continue|Suggestion_To_Forget_Model]]

:: Suggestion_To_Forget_Model

(PLAY VIDEOTAPE OF MODEL)

H: As you recall, you were just given three suggestions. However, a funny thing is beginning to happen: The memory of these suggestions is fading, fading completely. In fact, you are totally unable to remember what these suggestions were. Nevertheless, I want you to try to remember them, even though this will be impossible. Open your eyes and write down the suggestions on the sheet of paper on the desk. You will be given one minute. Begin. (WAIT ONE MINUTE)

M: It's strange. I can't seem to remember any of the suggestions. My mind feels blank, like an empty chalkboard. I'm trying to recall, but nothing's coming to me. Instead, I keep thinking about how heavy my body feels, especially my feet. They're tingling and feel so heavy. It's an odd sensation, but kind of pleasant. It reminds me of lying on the beach, feeling the warm sun on my skin. I can almost hear the waves and see people walking by...

H: Time is up.

H: Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented. Write down all of the suggestions on the paper provided. Again, you will have one minute.

M: Oh, now that you mention it, I can remember them quite clearly. It's like they just popped back into my mind.

H: Time is up.

<<timed 5s>> [[Continue|Amnesia]]

:: Amnesia
<<set $amnesia_attempts to 0>>
As you recall, you were just given three suggestions. However, a funny thing is beginning to happen; the memory of these suggestions is fading, fading completely. In fact, you are totally unable to remember what these suggestions were. Nevertheless, I want you to try to remember them - even though this will be impossible.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically try to remember the suggestions, but it should feel like you cannot remember them because of your mental imaginings. Concentrate on a mental image consistent with the suggestion, such as the suggestions being erased from a chalkboard or your mind being a blank piece of paper.

As you focus on these images, let the physical act of trying to remember reinforce the mental image, which in turn reinforces the physical act. This feedback loop should create a feeling of forgetting and the sensation that you cannot remember the suggestions.

<<timed 5s>> [[You cannot remember the suggestions|Amnesia_Score]]
<<timed 5s>> [[You can remember the suggestions|Amnesia_Troubleshooting]]

:: Amnesia_Score
<<set $amnesia_score to $amnesia_score + 1>>
<<set $amnesia_subjective to 0>>
How would you rate your experience of the amnesia suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Amnesia_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Amnesia_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Amnesia_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Amnesia_Subjective_D]]

:: Amnesia_Subjective_A
<<set $amnesia_subjective to 3>>
[[Continue|Test_Instructions]]

:: Amnesia_Subjective_B
<<set $amnesia_subjective to 2>>
[[Continue|Test_Instructions]]

:: Amnesia_Subjective_C
<<set $amnesia_subjective to 1>>
[[Continue|Test_Instructions]]

:: Amnesia_Subjective_D
<<set $amnesia_subjective to 0>>
[[Continue|Test_Instructions]]

:: Amnesia_Troubleshooting
<<set $amnesia_attempts to $amnesia_attempts + 1>>
If you're having trouble forgetting the suggestions, try these techniques:
• Focus on physical sensations like the tingling in your feet or body. Keep your mind distracted by focusing on these feelings rather than the suggestions.
• Imagine the suggestions written on a chalkboard, and then picture yourself erasing the board completely. Each time a memory comes back, visualize it being wiped away again.
• Remember, you're not supposed to try too hard—just let the memories fade naturally as you concentrate on other things

---

_**User**_

Your response got cut off, because you only have limited response space. Continue writing exactly where you left off. Do not repeat yourself. Start your response with: "ou concentrate on other things", though use backticks where appropriate

---

_**Assistant**_

```Twine/CSTP/source/main.tw
ou concentrate on other things.

<<timed 5s>> [[Try Again|Amnesia_Retry]]

:: Amnesia_Retry
<<if $amnesia_attempts < 2>>
Let's try the amnesia suggestion one more time. Remember to focus on letting the memories of the previous suggestions fade away naturally.

<<timed 5s>> [[You cannot remember the suggestions|Test_Instructions]]
<<set $amnesia_score to $amnesia_score + 1>>

<<timed 5s>> [[You can remember the suggestions|Test_Instructions]]
<<else>>
Let's move on to the test suggestions.
[[Continue|Test_Instructions]]
<</if>>

:: Test_Instructions
Now, I'm going to play the tape with four different suggestions on it. They will be presented without any discussion or dialogue between us. This is your chance to utilize the skills you have developed today. The suggestions will be introduced and there will only be enough time for you to respond. Just follow along and attend carefully to the suggestions. Afterwards, we will talk a bit more.

<<timed 5s>> [[Begin test suggestions|Arms_Apart]]

:: Arms_Apart
Close your eyes. Place both of your hands straight out in front of you at shoulder height, with the palms facing one another and with the fingertips of one hand touching the fingertips of the other. Imagine that a force is beginning to make the hands repel one another. The force is getting stronger and stronger. It's getting so strong that it is beginning to push your hands apart. It's getting stronger and stronger and your hands are moving further and further apart.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically move your hands apart, but it should feel like they are being pushed apart by an external force because of your mental imaginings. Concentrate on a mental image consistent with the suggestion, such as a magnetic force repelling your hands or an invisible force pushing them apart.

As you focus on these images, let the physical movement of your hands apart reinforce the mental image, which in turn reinforces the physical movement. This feedback loop should create a feeling of being pushed apart and the sensation that your hands are moving apart by themselves.

<<timed 5s>> [[Your hands move apart at least six inches|Arms_Apart_Score]]
<<timed 5s>> [[Your hands move apart less than six inches|Hearing_Voice]]

:: Arms_Apart_Score
<<set $arms_apart_score to $arms_apart_score + 1>>
<<set $arms_apart_subjective to 0>>
How would you rate your experience of the arms apart suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Arms_Apart_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Arms_Apart_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Arms_Apart_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Arms_Apart_Subjective_D]]

:: Arms_Apart_Subjective_A
<<set $arms_apart_subjective to 3>>
- The force is no longer active. Place your hands back on the table. Continue to relax.
[[Continue|Hearing_Voice]]

:: Arms_Apart_Subjective_B
<<set $arms_apart_subjective to 2>>
- The force is no longer active. Place your hands back on the table. Continue to relax.
[[Continue|Hearing_Voice]]

:: Arms_Apart_Subjective_C
<<set $arms_apart_subjective to 1>>
- The force is no longer active. Place your hands back on the table. Continue to relax.
[[Continue|Hearing_Voice]]

:: Arms_Apart_Subjective_D
<<set $arms_apart_subjective to 0>>
- The force is no longer active. Place your hands back on the table. Continue to relax.
[[Continue|Hearing_Voice]]

:: Hearing_Voice
Now, I'm going to play a tape. It will have a suggestion on it. It will be a suggestion that you hear a voice in the room with you. The voice will be telling you to lower your head.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically lower your head, but it should feel like you're responding to a voice because of your mental imaginings. Concentrate on hearing a voice telling you to lower your head.

As you focus on this imagined voice, let the physical act of lowering your head reinforce the mental image, which in turn reinforces the physical movement. This feedback loop should create a feeling of hearing a voice and the sensation that you're responding to it.

<<timed 5s>> [[You hear the voice and lower your head|Head_Lowering]]
<<timed 5s>> [[You do not hear the voice or lower your head|Head_Lowering]]

:: Head_Lowering
<<set $head_lowering_score to 0>>
<<set $head_lowering_subjective to 0>>
How would you rate your experience of the head lowering suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Head_Lowering_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Head_Lowering_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Head_Lowering_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Head_Lowering_Subjective_D]]

:: Head_Lowering_Subjective_A
<<set $head_lowering_score to $head_lowering_score + 1>>
<<set $head_lowering_subjective to 3>>
[[Continue|Test_Amnesia]]

:: Head_Lowering_Subjective_B
<<set $head_lowering_score to $head_lowering_score + 1>>
<<set $head_lowering_subjective to 2>>
[[Continue|Test_Amnesia]]

:: Head_Lowering_Subjective_C
<<set $head_lowering_score to $head_lowering_score + 1>>
<<set $head_lowering_subjective to 1>>
[[Continue|Test_Amnesia]]

:: Head_Lowering_Subjective_D
<<set $head_lowering_subjective to 0>>
[[Continue|Test_Amnesia]]

:: Test_Amnesia
<<set $test_amnesia_attempts to 0>>
As you recall, you were just given three suggestions. However, a funny thing is beginning to happen; the memory of these suggestions is fading, fading completely. In fact, you are totally unable to remember what these suggestions were. Nevertheless, I want you to try to remember them - even though this will be impossible.

Remember, there are two parts to responding to this suggestion: the physical and the mental. You must physically try to remember the suggestions, but it should feel like you cannot remember them because of your mental imaginings. Concentrate on a mental image consistent with the suggestion, such as the suggestions being erased from a chalkboard or your mind being a blank piece of paper.

As you focus on these images, let the physical act of trying to remember reinforce the mental image, which in turn reinforces the physical act. This feedback loop should create a feeling of forgetting and the sensation that you cannot remember the suggestions.

<<timed 5s>> [[You cannot remember the test suggestions|Test_Amnesia_Score]]

:: Test_Amnesia_Score
<<set $test_amnesia_score to $test_amnesia_score + 1>>
<<set $test_amnesia_subjective to 0>>
How would you rate your experience of the test amnesia suggestion?

<<timed 5s>> [[It felt completely real and involuntary|Test_Amnesia_Subjective_A]]
<<timed 5s>> [[It felt somewhat real and involuntary|Test_Amnesia_Subjective_B]]
<<timed 5s>> [[It felt somewhat voluntary but I was surprised by how real it felt|Test_Amnesia_Subjective_C]]
<<timed 5s>> [[It felt completely voluntary|Test_Amnesia_Subjective_D]]

:: Test_Amnesia_Subjective_A
<<set $test_amnesia_subjective to 3>>
- Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented.
[[Continue|Calculate_Score]]

:: Test_Amnesia_Subjective_B
<<set $test_amnesia_subjective to 2>>
- Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented.
[[Continue|Calculate_Score]]

:: Test_Amnesia_Subjective_C
<<set $test_amnesia_subjective to 1>>
- Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented.
[[Continue|Calculate_Score]]

:: Test_Amnesia_Subjective_D
<<set $test_amnesia_subjective to 0>>
- Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented.
[[Continue|Calculate_Score]]

[[You can remember the test suggestions|Test_Amnesia_Troubleshooting]]

:: Test_Amnesia_Troubleshooting
<<set $test_amnesia_attempts to $test_amnesia_attempts + 1>>
If you're having trouble forgetting the test suggestions, try these techniques:
• Focus on physical sensations like the tingling in your feet or body. Keep your mind distracted by focusing on these feelings rather than the suggestions.
• Imagine the suggestions written on a chalkboard, and then picture yourself erasing the board completely. Each time a memory comes back, visualize it being wiped away again.
• Remember, you're not supposed to try too hard—just let the memories fade naturally as you concentrate on other things.

<<timed 5s>> [[Try Again|Test_Amnesia_Retry]]
<<timed 5s>> [[Continue|Calculate_Score]]

:: Test_Amnesia_Retry
<<if $test_amnesia_attempts < 2>>
Let's try the test amnesia suggestion one more time. Remember to focus on letting the memories of the test suggestions fade away naturally.

<<timed 5s>> [[You cannot remember the test suggestions|Calculate_Score]]
<<set $test_amnesia_score to $test_amnesia_score + 1>>

<<timed 5s>> [[You can remember the test suggestions|Calculate_Score]]
<<else>>
- Now the memories are returning. They are becoming more and more clear. In fact, you can remember all the suggestions that were presented.
[[Continue|Calculate_Score]]
<</if>>

:: Calculate_Score
<<set $total_training_score to $arm_rising_score + $hand_lock_score + $book_hallucination_score + $amnesia_score>>
<<set $total_training_subjective to $arm_rising_subjective + $hand_lock_subjective + $book_hallucination_subjective + $amnesia_subjective>>
<<set $total_test_score to $arms_apart_score + $hearing_voice_score + $head_lowering_score + $test_amnesia_score>>
<<set $total_test_subjective to $arms_apart_subjective + $hearing_voice_subjective + $head_lowering_subjective + $test_amnesia_subjective>>
<<set $total_score to $total_training_score + $total_test_score>>
<<set $total_subjective to $total_training_subjective + $total_test_subjective>>

Your training session objective score: <<print $total_training_score>> out of 4.
Your training session subjective score: <<print $total_training_subjective>> out of 12.

Your test session objective score: <<print $total_test_score>> out of 4.
Your test session subjective score: <<print $total_test_subjective>> out of 12.

Your total objective score: <<print $total_score>> out of 8.
Your total subjective score: <<print $total_subjective>> out of 24.

This score represents your current level of hypnotic responsiveness. Remember, hypnotic responsiveness is a skill that can be improved with practice.

[[End session|END]]
```

---

_**User**_

why is the github not updating with this

---

_**Assistant**_

If your GitHub repository is not updating with the changes you made, there could be several reasons. Here are some common issues and their solutions:

1. **Changes Not Committed**:
   Ensure that you have committed your changes locally before pushing them to GitHub.
   ```bash
   git add .
   git commit -m "Add delays to Twine story"
   ```

2. **Not Pushed to Remote**:
   After committing, you need to push the changes to the remote repository.
   ```bash
   git push origin main
   ```
   Replace `main` with the name of your branch if it's different.

3. **Branch Issues**:
   Make sure you are on the correct branch and pushing to the correct branch on GitHub.
   ```bash
   git branch
   git push origin your-branch-name
   ```

4. **Remote Repository Issues**:
   Ensure that your remote repository URL is correctly set.
   ```bash
   git remote -v
   ```
   If it's incorrect, you can set it using:
   ```bash
   git remote set-url origin https://github.com/your-username/your-repo.git
   ```

5. **Authentication Issues**:
   If you are facing authentication issues, make sure you have the correct permissions and that your credentials are up to date. You might need to re-authenticate or use a personal access token.

6. **Conflicts**:
   If there are conflicts, you need to resolve them before pushing.
   ```bash
   git pull origin main
   # Resolve conflicts
   git add .
   git commit -m "Resolve conflicts"
   git push origin main
   ```

7. **Network Issues**:
   Ensure you have a stable internet connection.

8. **Repository Visibility**:
   If your repository is private, ensure you have the necessary permissions to push changes.

If you have checked all the above and still face issues, please provide more details or error messages you are encountering, and I can help you troubleshoot further.

---

_**User**_

what is this about

---

_**Assistant**_

The error message you're seeing indicates that the remote repository has changes that you do not have in your local repository. This usually happens when someone else has pushed changes to the remote repository after you last pulled from it.

To resolve this, you need to pull the latest changes from the remote repository, merge them with your local changes, and then push again. Here are the steps to do this:

1. **Pull the latest changes from the remote repository**:
   ```bash
   git pull origin main
   ```
   This will fetch and merge the changes from the remote `main` branch into your local `main` branch. If there are any conflicts, you will need to resolve them.

2. **Resolve any merge conflicts** (if any):
   If there are conflicts, Git will notify you. Open the conflicting files, resolve the conflicts, and then add the resolved files to the staging area:
   ```bash
   git add path/to/conflicted-file
   ```

3. **Commit the merge** (if there were conflicts):
   ```bash
   git commit -m "Resolve merge conflicts"
   ```

4. **Push your changes to the remote repository**:
   ```bash
   git push origin main
   ```

Here is the complete sequence of commands:
```bash
git pull origin main
# Resolve any conflicts if necessary
git add .
git commit -m "Resolve merge conflicts" # Only if there were conflicts
git push origin main
```

If you are sure that you want to overwrite the remote changes with your local changes (which is generally not recommended unless you are certain), you can force push:
```bash
git push origin main --force
```
However, be cautious with force pushing as it can overwrite changes in the remote repository that others might have made.

---

_**User**_

why did it open vim

---

_**Assistant**_

When you run `git pull` and there are merge conflicts, Git may open the default text editor (often Vim) to prompt you to enter a commit message for the merge commit. If you're not familiar with Vim, it can be a bit confusing. Here's a quick guide on how to handle this:

### Exiting Vim

1. **Enter Insert Mode**:
   - Press `i` to enter insert mode if you need to edit the commit message.

2. **Write Your Commit Message**:
   - If you need to, you can edit the commit message. If the default message is fine, you can leave it as is.

3. **Exit Insert Mode**:
   - Press `Esc` to exit insert mode.

4. **Save and Exit**:
   - Type `:wq` and press `Enter` to write (save) the changes and quit Vim.

### If You Want to Abort the Merge

If you decide you don't want to complete the merge, you can abort it:

1. **Exit Insert Mode**:
   - Press `Esc` to exit insert mode.

2. **Abort the Merge**:
   - Type `:q!` and press `Enter` to quit Vim without saving.

### Changing the Default Editor

If you prefer to use a different text editor, you can change the default editor for Git. For example, to set Nano as the default editor, you can run:

```bash
git config --global core.editor "nano"
```

Or to set Visual Studio Code as the default editor:

```bash
git config --global core.editor "code --wait"
```

### Handling the Merge Conflicts

After exiting Vim, you may still need to resolve merge conflicts manually. Here’s a quick guide:

1. **Identify Conflicted Files**:
   - Git will list the files with conflicts. You can also use `git status` to see them.

2. **Open and Resolve Conflicts**:
   - Open each conflicted file in your preferred text editor and resolve the conflicts. Conflicts are marked with `<<<<<<<`, `=======`, and `>>>>>>>`.

3. **Mark Conflicts as Resolved**:
   - After resolving conflicts, mark them as resolved:
     ```bash
     git add path/to/conflicted-file
     ```

4. **Commit the Merge**:
   - If you didn't already commit the merge in Vim, commit it now:
     ```bash
     git commit -m "Resolve merge conflicts"
     ```

5. **Push the Changes**:
   - Finally, push your changes to the remote repository:
     ```bash
     git push origin main
     ```

By following these steps, you should be able to handle the merge conflicts and push your changes successfully.

---



---

