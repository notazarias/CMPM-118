What I did this week
Made a lot of progress this week — almost fully caught up on Rustlings and currently working through Chapter 9 of the Rust book. I also read up on Arrakis and spent some time trying to get a better understanding of how that operating system works.

What piqued my interest
Two things stood out this week. Learning about lifetimes and traits in Rust was genuinely interesting they're some of the more unique parts of the language and they're starting to click the more I work with them. Reading about Arrakis was cool too, it was interesting to start understanding the ideas behind it and see how it connects to what we're working toward in the class.

What I plan to do next week
I want to push through to Chapter 14 in the Rust book and keep building on the momentum from this week.


arrakis summary: 
Arrakis is an operating system that is designed to remove the OS kernel from the IO data path. The goal of Arrakis was to allow applications to be able to communicate with hardware while also still maintaining protection from other apps. 
Contributions 
  Moves I/O handling into user space.
  Uses hardware virtualization features to maintain security.
  Reduces kernel overhead and context switching.
Strengths

Strengths 
Provides impressive performance gains and makes better use of modern hardware.

Weaknesses:
Depends on specialized hardware support and may be harder to deploy broadly.
