---
layout: post
date: 2020-08-31 # earlier?
author: Neal
title: Crash Test August Update
slug: 684-crash-tests-august-update
---
Hello Explorers!

Back in June, we mentioned we’d be talking to more of our developers and providing clearer status updates regarding the project. Today is another entry in that, focusing on how the Crash Tests are doing and how we’re looking for Closed Beta.

While this still isn’t a blog post announcing the end of the Crash Tests, we are getting closer! We’ve squashed dozens of bugs that our Crash Testers have found and will continue to do so as we open up Spider Queen, Block Yard and Nimbus Station to testers in the future.

#### Building the Future
Over the past month, we’ve seen bug fixes and scripts implemented across Avant Gardens. Players are no longer limited to the pre-Monument quests and can now proceed all the way up to Spider Queen. This, however, is where we’ve locked progress for now.

The Spider Queen is an interesting situation, given it’s a boss fight that takes place on a property. It’s also a lot more complicated than the other AI we’ve got working; for example, it includes “phases” where the boss will jump away at a certain health percentage and spawn Spiderlings for the player to fight. Our current progress has Spider Queen just using a basic attack and her phase changes, but we’re still investigating her alternate moves to add later. With all that in mind, we’ve gotten to a point where the player can defeat the Spider Queen and claim a Block Yard property.

Block Yard and Nimbus Station are the last two things we’ll need to finish before ending our Crash Tests. While Block Yard is going to require quite a bit of work before we’re ready to release it, Nimbus Station will be a much easier addition. In my playthrough of Nimbus Station, I noted only 2 mission issues in the basic “join a faction” questline.

#### Laying the Foundations
With that bit about Nimbus Station, you might be wondering “well, why does it all work so well without any development focused on it?”. That’s because many of the features and core code we’ve written while working on Avant Gardens have been for underlying features, not “world-specific”. Not everything works on every world, but it gives us a great foundation to work with.

There are, however, things that are “world-specific” such as scripts. Examples of this would be the explosive Maelstrom Chests or Tiki Torches in Gnarled Forest, which are unique cases compared to other objects. These can range from complex (Avant Gardens Survival, Gnarled Forest Shooting Gallery, etc) to simple (Tiki Torches, etc) and will have to be done manually for every world.

#### Looking Forward
We know you’re all excited for Closed Beta and we hope this Developer Diary sheds some light on how close we’re getting to being ready. While we still can’t give out a firm date, know that we’re all trying out best to get there. We’ll talk more after this next Crash Test update is finished! 
