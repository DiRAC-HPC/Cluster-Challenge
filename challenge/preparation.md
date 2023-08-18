# Preparation for the cluster challenge


## Student preparation

We circulated details of the recommended training to all of the registered participants and strongly encouraged them to ensure they were familiar with the Linux command line and the basics of how to submit jobs to the UCL Myriad cluster, as well as having some knowledge of Python. 

We asked people to pre-register for the Myriad cluster (using the standard self-service UCL research computing account application form) to speed things up on the day. These training accounts were removed at the end of the challenge.

As all of the registered participants were from UCL, we strongly recommended that they should attend in person rather than online, emphasising that they would have a better experience if they did so; however, we did provide a Teams link for someone that requested to join online because they were out of the country at the time, and also circulated the link via Eventbrite on the morning of the first day of the challenge so that anyone who was unable to attend in person at the last minute due to illness, etc. could still join. We deliberately did not do this too far in advance to discourage people from thinking that this was a “webinar-style” event. (We also emphasised in publicity communications and on the registration site that this was a hands-on challenge).

We decided to allocate people into teams on the day, and that if some of the teams were more advanced than the others, we could potentially award both a novice team and an experienced team prize.


## Hardware setup

We reserved 4 general CPU nodes and a large GPU node (with 4 GPUs) which were dedicated for the 2 days of the challenge. The user accounts were then added to the access control list for the dedicated “training” queue we used (this system of nodes being reserved for usernames that have been granted access to a training queue is an established process which is also used for the UCL HPC Carpentry workshops). 


## Classroom setup

On the morning of the first day of the event, we had set up a welcome desk with pre-packed goody bags (rucksacks containing notebook, pen, coffee mug, all branded with the Kickstart HPC logo) and lanyards/name badges ready for all the participants and tutors, as well as coffee/tea/water and cookies. We had asked people to pre-register their UCL username for a Myriad account and most had managed to do so, but for those who hadn't, we had someone from the research computing support team on hand to help them with this and add the usernames to the dedicated training queue. 

The “classroom” we used was an informal breakout area of the ARC offices, which had tables for people to work on, power sockets in the floor, and 2 large “surface hub” screens to provide video display for the hybrid event. To work on the challenges in the afternoon, the students could also choose to move to another area with dedicated desks, including height adjustable (one of the participants had a requirement for this, which we did not actually know until the day – a question had also been asked about accessibility needs on the registration form, but should probably be asked again in the reminder email sent just before the event). 

We used Teams to allow 3 remote participants to follow the taught sessions; unfortunately, one of them experienced internet connectivity problems and dropped out completely, with another not choosing to attempt the challenges. The third participant joined in-person on the second day. For this reason, we would not recommend running a hybrid event, although fully remote could work.

Interim informal feedback was collected during day 1 using green (positive) and red 
(negative) post-it notes placed on a whiteboard, and a paper feedback form was circulated on day 2, along with the day 2 reward (a Kickstart HPC branded power bank).

Tea, coffee and lunch were provided in the classroom to allow for a more compressed schedule.


## Teaching preparation

We decided to include a taught element in the morning of each day, followed by an afternoon hands-on programming challenge. It was felt that this taught element would be beneficial because undergraduate students in particular would not be likely to have any parallel programming or GPU programming expertise; we also wanted to make the challenge open to all domains and to encourage rather than discourage by making the challenges impossible for those without a high level of pre-existing knowledge. We had asked several questions about HPC and programming experience/languages known on the Eventbrite registration form, and used this feedback (as well as the results of a poll run during the Careers Day event) to make the decision to create the challenges in Python rather than C++. Although C++ is more heavily used in HPC, we felt that Python was more likely to either be a language the students had some knowledge of, or could pick up in the lead up to the event. This was confirmed by the fact that only 3 of those who registered for the event had experience in C++. Most people who signed up said they had some programming experience, and all of them listed Python (only one said they had no programming experience at all). All the people who attended the event said they did have some prior experience of Python.

See challenge details for links to the teaching material we used.

Two meembers of ARC staff each taught one of the sessions, with the other acting as an assistant/demonstrator for the hands-on sessions. We also had an additional 2 helpers on on standby so that each team could benefit from a dedicated advisot, although in the event this was not needed as we only had two teams rather than the four teams we had anticipated (we set the maximum team size as 5 students).

A [HackMD](https://hackmd.io/X_-hIee7SvavFqFa4rK_BQ) was set up for use on the day.

## Schedule

The approximate schedule was as follows:

### Day 1

- 10-12 - Introduction to parallel programming in Python (taught)
- 12-1 - Lunch
- 1-5 - CPU challenge

### Day 2

- 10-12 - Introduction to GPU programming in Python (taught)
- 12-1 - Lunch
- 1-5 GPU challenge


## The challenge competition

The 6 participants were split into 2 teams of 3 (one female and 2 males in each team, with one person (a postgraduate student) in each team having a limited amount of prior HPC experience. 3 of the 6 were postgraduate students, with 3 undergraduate students. Neither of the teams managed to complete the second day’s GPU challenge, although they did manage to complete the first one (parallelisation of the code on a CPU). 

For the last hour of the challenges, a countdown was clock displayed on the screen at the front of the classroom. When the time was up, each team's code was checked and run by one of the tutors. The results were close, with the winning team’s code taking 26 seconds and the runner-up taking 30 seconds. In view of this, we decided to award a winner and a runner-up prize (we had discussed this earlier on). The results were announced immediately (followed by a short social event) and prize vouchers were emailed to the participants a few days later.

## Feedback from the event

Although the number of attendees was disappointing (6 out of the 20 who had registered), it was heartening to learn from the (paper, circulated on the last afternoon of the event) feedback forms that those who participated were not only enthusiastic about the event itself, but all of them wanted to learn more about careers in HPC and 4 of the 6 were interested in participating in the CIUK cluster challenge in December, if UCL organised a team (the other 2 were due to leave UCL before then). We had some very positive comments about the teaching and the atmosphere of the event, with several mentioning how much they had enjoyed themselves and how much they had learned. Negatives mainly concerned the perceived lack of advertising, and one person found the variety of training resources confusing (although someone else commented on how useful they were). Suggestions for improvement were mainly requests for more demos, examples, and hands-on time; this would mean extending the event to 3 days but is certainly something to consider for future challenges. We got the impression that everyone was quite tired at the end of the second day!


