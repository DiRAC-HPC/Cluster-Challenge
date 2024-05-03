# Pre-requisites


## Careers Day


We chose to run an additional online event – an HPC Careers Day webinar hosted on Zoom - to highlight both the wide range of research domains and industries currently using HPC, and the corresponding opportunities that are available, with the aim of reaching students who may not previously have considered HPC as a potential career path. The Careers Day event included 11 speakers with 2 panel sessions, chaired by ARC Associate Directors (see the [agenda for the day](https://github.com/DiRAC-HPC/Cluster-Challenge/blob/main/examples/Agenda%20for%20Careers%20Day.pdf) for details; recordings of the [morning](https://mediacentral.ucl.ac.uk/Play/83787) and [afternoon](https://mediacentral.ucl.ac.uk/Play/83804) sessions are also available). Speakers in the morning session talked of how they have used HPC in their research or other careers, and why it is an increasingly important resource. Speakers in the afternoon presented more detail on their careers in HPC, to demonstrate the opportunities in different sectors. Questions from attendees were collected using the [Sli.do](https://sli.do) platform, and at the end of the morning and afternoon sessions the speaker panels answered these. Sli.do was also used to survey participants on programming expertise; the feedback from this poll validated our decision to use Python for the cluster challenges, as this was by far the most commonly-used language. Feedback forms were also sent to the attendees - see the [examples folder](https://github.com/DiRAC-HPC/Cluster-Challenge/tree/main/examples) of this repository.


## Training

We discussed pre-requisites but decided on strong recommendations for training (specifically, an [HPC Carpentry workshop](http://github-pages.ucl.ac.uk/2022-03-07-ucl-online-hpcc/) that we ran after the Careers Day in March 2022) rather than deterring inexperienced people from taking part. However, we were surprised that the participants struggled so much with the first of the two challenges and did not complete the second one, especially in view of the fact that all of them said they had done most, if not all, of the recommended pre-learning. 

Although most of the participants had at least some command line experience, only two had any prior experience of using a compute cluster and clearly this lack of hands-on experience was a problem. To deal with this we would suggest making it a requirement to attend an HPC Carpentry workshop, The [DiRAC Foundation HPC-Skills](https://dirac.ac.uk/courses/hpc-skills-training/) online course or similar hands-on introductory course, instead of doing the equivalent self-paced learning (unfortunately, almost all of the participants had chosen this route rather than attending the workshop). 

See the [list of recommended training resources](https://www.ucl.ac.uk/advanced-research-computing/cluster-challenge-training-resources) we used.

For participants with significant experience, another approach would be to develop a quiz to test their existing knowledge, similar to the [DiRAC Foundation HPC-Skills assessment](https://dirac.ac.uk/courses/hpc-skills-assessment/). This would give them confidence if they passed, as well as highlighting any areas of weakness/need for further reading or training.


## Hardware

The [UCL Myriad cluster](https://www.rc.ucl.ac.uk/docs/Clusters/Myriad/) was used for the hands-on cluster challenge.  4 standard CPU nodes and a large GPU node (with 4 GPUs) were reserved for the challenge using a dedicated training queue, to make sure that  participants’ jobs were able to run within a reasonable timescale. A further consideration is accessing the cluster remotely; Myriad is behind a firewall, so remote participants would have needed to connect via VPN or ssh from another UCL server.


## Promotion/Registration

- Consider running a Careers Day webinar to help generate interest.

- Make it very clear that the cluster challenge itself is an in-person event and not a webinar. We would not recommend a hybrid event for the hands-on cluster challenge due to the difficulty of hybrid teams working together, although a fully remote team might work.

- Consider having a prize (we gave Amazon vouchers) and/or some collateral items (we had backpacks, notepads, pens, lanyards, mugs, power banks). You can see some [images](https://github.com/DiRAC-HPC/Cluster-Challenge/tree/main/examples/images) of the collateral items in the [examples](https://github.com/DiRAC-HPC/Cluster-Challenge/tree/main/examples) folder.

- Enlist the assistance of course tutors and academic supervisors to help advertise the challenge. Most of those who attended the hands-on challenge mentioned that they had heard about the event from their undergraduate or MSc course tutor or PhD supervisor; an endorsement from them seems to be a major factor in encouraging attendance.

- Overbook by at least 25-30% to allow for no-shows and drop-outs.
- We used Eventbrite for registration - see [the event page](https://www.eventbrite.co.uk/e/kickstart-your-hpc-journey-student-cluster-challenge-registration-240429670617).


