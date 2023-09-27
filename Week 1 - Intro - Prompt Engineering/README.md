# Prompt Engineering Lab

## Part 1 Define your problem

### Prompt:

Write a screenplay for a new 20 minute long episode of Doctor Who in the style of writer Russel T. Davies with Christopher Eccleston playing the Doctor and Billie Piper playing Rose Tyler.The story should take place in 1960's in the Haight-Ashbury area of San Francisco where aliens are using the counter culture drug scene in some way to carry out their nefarious plot.

### Expectation: 

I expect the output of this prompt to be pretty bad, a far-fetched and silly plot if it has any coherence at all.I wanted to try to push the limits a bit in terms of trying to find something it would struggle to do well, so it would be more interesting to see how it performs.

## Part 2: The Chat interface

### Prompt refinements:

1. Please rewrite the screenplay and this time make the episode 40 minutes long and add more details.Try to make the dialog more realistic, sophisticated and intelligent and don't give away the nefarious plan too quickly.Add some suspense and keep the audience guessing about who the villains are and how the doctor is going to stop them.
2. Please rewrite the screenplay again but this time add a lot more dialog, details about the setting, and more character development.
3. Try rewriting the screenplay one more time in the same style as the following text ###

	[The Tyler's flat]
	
	(Earth, United Kingdom, South London. An alarm clock goes off at 7:30. A young blonde woman gets up, dressed and kisses her mother goodbye. Her mother, who is also...(See [TheDoctorAndRose-RusselTDavies.md](TheDoctorAndRose-RusselTDavies.md) for full text).
	
### Results:

As expected the output was pretty bad.The dialog was odd, juvenile, and predictable, and the plot was not only obvious but they gave it away in the first few minutes.It also was not nearly the length I asked for with no character development and very few details about the setting.It was kind of entertaining anyway to read it and use your imagination to fill in the details but definitely ChatGPT won't be replacing screenwriters any time soon.Clarifying prompts didn't do much to improve upon the original. In fact, adding a portion of an actual screenplay as an example made it worse because it basically just summarized (plagiarized) the text I gave it instead of writing something new in the same style.Full text of the chat is here: [TheDoctorAndRose-RusselTDavies.md](TheDoctorAndRose-RusselTDavies.md). 

###### Note that I did the entire chat twice because after doing the whole thing the first time I discovered that I had asked it to write in the style of *Ray* Davies (lead singer from the Kinks) instead of *Russel T.* Davies (original Dr. Who writer and show-runner) so I started over.Referencing the correct writer only improved the output very modestly though.If you are curious, the original incorrect chat is here: [TheDoctorAndRose-RAYDavies-Mistake.md](TheDoctorAndRose-RAYDavies-Mistake.md)

### New Chat - Final Paper

#### Prompt: 

You are a graduate student with a 4.0 GPA.Write a 5,000–6,000-word seminar paper for a graduate course titled "Data Culture and Society".In it take the theoretical framework from Simone Browne's book "Dark Matters: On the Surveillance of Blackness" and apply it to Native American history using Vine Deloria, Jr. and Clifford M. Lytles's book "American Indians, American Justice" as your main source as well as "Conquest: Sexual Violence and American Indian Genocide" by Andrea Smith, "Education for Extinction: American Indians and the Boarding School Experience" by David Wallace Adams and "In the Spirit of Crazy Horse" by Peter Matthiessen as additional sources as well as any other sources you find relevant. Argue that Native American nations have been subjected to surveillance in the same ways that black people have been as described by Browne and also in other unique ways due in part to their federal legal status as "Domestic Dependent Nations" which codified their surveillance into law. Describe the American Indian Boarding School experience, and modern resistance movements including the pipeline protests on the Standing Rock Reservation and political prisoners such as Leonard Peltier.

#### Refinement:

Please rewrite this paper adding more details and quotes from the sources with citations.

#### ChatGPT's response: 
	
>I'm unable to provide verbatim excerpts from copyrighted texts or specific page numbers for citations. However, I can certainly help in providing more detailed content, incorporating key ideas and concepts from the sources you mentioned, while appropriately citing and paraphrasing them.

#### Results

The paper written by ChatGPT once again was much shorter than what I asked for and was basically more like a long abstract than an academic paper.When I asked it to add more details and quotes with citations it was unable to do that and basically just reworded exactly what it had produced the first time.The writing was very generic and didn't really say very much more than what I had already said in my prompt. It just padded my prompt with some fancy sounding wording.Full text here: [FinalPaper-Part1.md](FinalPaper-Part1.md).

### New Chat - Final Paper Part 2

#### Prompt: 

For part 2 I used the same prompt minus the first sentence, "You are a graduate student with a 4.0 GPA." and followed the prompt with three hashtags
(\###) and then tried 3 different writing samples.

First I tried just putting another shorter paper I had written so that it would emulate my style but it seemed confused by the fact that it was not on the same subject matter as the prompt was asking for and so replied that it couldn't provide any output.

On my second attempt I decided to give it the beginning of the paper that I had written on this subject but I gave it a bit too much so it just finished the paper for me. It wrote a lot more in each section this time but I had to give it half the paper and it still gave pretty generic information. Nothing Earth shattering.Although it might be useful as a starting point for writing but the fact that I had to give it half the finished paper makes it much less useful.

On the final attempt I just gave it one less section of my paper and this time it wrote the whole paper but very shortened and more of a summary than the previous attempt.

The full text of all three attempts is here: [FinalPaper-Part2.md](FinalPaper-Part2.md).

## Part 3: The Playground Interface

### Prompt

I am going on a solo backpacking trip in the Catskills this coming weekend for 3 days and two nights.Write me a packing checklist that includes everything I will need to pack in my backpack and bring in my car.

### Prompt Modification

That's a pretty good list!Thanks!But can you add more detail about what kind of food to bring?

### Impressions Chat Interface vs. Playground

The ChatGPT interface gave a MUCH more complete list that was well organized except for some weird numbering and in general was a pretty darn good checklist.The playground list was wildly incomplete with no food, water, cooking supplies, or toiletries among other missing items on the initial list.Adding the exact same modification text created a similarly incomplete list compared with the ChatGPT interface which produced a pretty great food list.Overall this has been the best use of ChatGPT that I have found so far.

## Part 4: Modifying the Playground

I didn't notice a huge difference with most of the setting changes except for the following two:

1. Turning up the temperature resulted in complete gobbledygook. Completely unintelligible strings of characters.
2. Adding stop words caused it to just fail to write a script.It stopped writing after just one or two lines. 

Overall however the playground seemed to create much more interesting screenplays than the ChatGPT interface.The dialog wasn't quite as juvenile, there was a lot more setting details, and the characters seemed to act more in line with what you would expect. It's still not going to replace writers, but could actually be a good way to generate ideas if I were a writer.I played around with it quite a lot because it was kind of fun reading the scripts and imagining the characters so then I tried removing the requirements for time and place to see what it would do with more leeway for "creativity", but when you remove those constraints it had more tendency to plagiarize, creating scripts that included details straight out of actual episodes.

Full chat text here: [Playground.md](Playground.md)

## Part 5: Common Applications

### Product Name Generator

Generate product names from a description and seed words.

#### SYSTEM

You will be provided with a product description and seed words, and your task is to generate product names.

#### USER

Product description: A backpacking tent

Seed words: lightweight, sturdy, roomy

### Results

The product names generated by the Playground were pretty bad.Not anything I would want to use if I were actually selling a product. The helpful assistant didn't actually generate product names at all but instead created text for a sales brochure or webpage for the product. The only things that changed in the code were the temperature which was reduced to 0.8 and the System instruction which was added. I am not sure how this relates to user behavior and/or user belief.

Full generated output and code here: [ProductNameGenerator.md](ProductNameGenerator.md)

## Part 6: Coding

