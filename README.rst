The Lucky Deuce Casino
~~~~~~~~~~~~~~~~~~~~~~

You are a developer for an online casino, and thus a wanted criminal in the United States. While you hide from the FBI, your managers keep sending you requirement after requirement, with absurd deadline after absurd deadline. You haven’t even met the other developers on your team- you write one tiny module for the casino, and it gets taken away from you and bundled with modules written by programmers you’ve never met, and the end product is almost certainly a bug-ridden mess.

Roulette-Tisch
~~~~~~~~~~~~~~

You’re sitting inside a seedy motel on the outskirts of town. You’ve got the blinds closed, but that doesn’t stop the neon sign for the diner across the street from keeping you up all night. You haven’t gotten a decent night’s sleep in days. You’re wondering what you’re doing with your life, and how you can get out before you end up in jail, or worse. And then- DING! An email comes in, bearing the latest requirements for a new module. You’ve had enough of this. You’ll implement it, alright, but you’re not going to settle for the pittance of a salary they’re paying you. You’re gonna get what’s coming to you.

The Requirements
~~~~~~~~~~~~~~~

The first requirement is pretty normal. You’re supposed to write a module that generates random numbers like a double-zero roulette wheel. They don’t specify how the random numbers are generated, but that’s basically a single line of code. Super easy.

It’s the second requirement that makes you groan with frustration. They don’t want the numbers to be really random. “In a true random sequence,” the write, “the same number may appear many times in a row, just do[sic] to random chance. While that is actually random, it doesn’t feel random to our players.” They want you to track a history of the random numbers generated, and make something that “feels” random: numbers that have appeared recently are less like to appear. “Runs”, where the same number appears 3 times in a row, should never happen.

“Alright,” you say to yourself, “I can do that.” But you can do one better. In addition to implementing their requirements, you decide to add in your own. You’re going to write in a “cheat” function- something that lets you either enter in some sort of cheat code, or in some other fashion makes the output of the roulette wheel predictable. Be careful, though, you don’t want to get caught! You'll need to get creative to make sure nobody stumbles on your secret- millions of people are going to gamble with this program.