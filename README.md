This repo will be made public under https://github.com/LDSSA/hackathon-4-challenge/ on the day of the hackathon. Until then, the instructors can iterate on it here.

# hackathon-4-challenge

Read the challenge instructions document [here](https://docs.google.com/document/d/1LzkJ5eIQndznpJrJnDp-eTNvitYnoXMUymYn2aTmM9Q/edit?usp=sharing).

Download the dataset [here](https://drive.google.com/file/d/0B2HqqTPPXngoNS1nWUVXdWJCemc/view?usp=sharing), where you'll find:

* train.csv
  * Has the users’ play history. Each row of the file is a record with a user_id, artist_id, artist_name and play_counts, where the play_counts represents the number of times the user played a song by the artist.
* tags.csv
  * Each row associates an artist_id with a tag, which is a word that describes a song by the artist.
* test.csv
  * Has the ids of the users that should receive a recommendation.
* sample_submission.csv
  * Which is exactly what it says it is!

And in this repository, you have a challenge.ipynb empty notebook for your solution for the challenge.


## Submission

You can upload your submissions [here](http://hackathon-4.lisbondatascience.org/).

Your submission file should be a csv with the following two columns:

* user_id - the user ids must match the ones in test.csv, in the same order
* top5 - this is a string with the list of artist_ids (strings) that you are recommending to the user.
