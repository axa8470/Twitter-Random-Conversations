# Twitter-Random-Conversations

This dataset was collected for the project "Twitter Users' Behavioral Response to Toxic Replies" (https://arxiv.org/abs/2210.13420).

The dataset represents a random sample of Twitter conversations collected from August 14th to September 28th, 2021, that includes 79.8k Twitter conversations. Additionally, we tracked the online behaviors of users who were involved in these conversations in terms of tweet deletion, account deactivation and account privatization. Their behaviors can be found in the folder /behaviors.

random_conversations.csv:
AuthorTweet represents a conversation id, so all the tweets in Tweet column that have the same AuthorTweet belong to the same conversation. Note that replies collected include both direct replies to main tweet as well as replies to replies. Score represents a Severe Toxicity score obtained by passing the tweet text to the Google's Perspective API. The dataset contains a total of 528,041 tweets, posted by 328,390 unique users.

If you use this dataset, please cite our paper:

@article{aleksandric2022twitter,

  title={Twitter Users' Behavioral Response to Toxic Replies},
  
  author={Aleksandric, Ana and Roy, Sayak Saha and Nilizadeh, Shirin},
  
  journal={arXiv preprint arXiv:2210.13420},
  
  year={2022}
}