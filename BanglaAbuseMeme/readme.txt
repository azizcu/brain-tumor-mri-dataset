The 'Images' folder contains all the annotated Bengali memes.

'BanglaAbuseMeme_annotation.csv' contains the annotation details. The CSV file has six columns:
i) 'Ids': the meme file name
ii) 'sentiment': the sentiment associated with the meme {'Negative', 'Neutral', 'Positive'}
iii) 'sarcasm': whether the meme is sarcastic or not {'Yes', 'No'}
iv) 'vulgar': whether the meme is vulgar or not {'Vulgar', 'Not Vulgar'}
v) 'abuse': whether the meme is abusive or not {'Abusive', 'Non-abusive'}
vi) 'target': target associated with the meme {'Political', 'Religion', 'Individual', 'Gender', 'National Origin', 'Social Sub-groups', 'Others', 'None'}
	    -> A meme can have multiple targets; in that case, the targets are joined using '#'. For example: 'target1#target2'

To check out the code, please visit the following GitHub repository: https://github.com/hate-alert/BanglaAbuseMeme