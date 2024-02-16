# Subtheme Sentimental Analysis
So I used Bert model to analysis the subtheme and their sentiment.
BERT, or Bidirectional Encoder Representations from Transformers, is a powerful pre-trained natural language processing (NLP) model developed by Google. It revolutionizes language understanding by training on vast amounts of unlabeled text, allowing it to capture context and meaning from both left and right directions in a sentence. BERT's bidirectional attention mechanism enables it to grasp intricate relationships within sentences, making it a cornerstone for various NLP tasks such as sentiment analysis, named entity recognition, and question answering. Its transfer learning capabilities have led to widespread adoption in diverse applications, showcasing its effectiveness in comprehending and generating human-like language representations.

BERT is advantageous for sentiment analysis because it understands context well, leverages pre-trained linguistic representations, supports transfer learning for task-specific fine-tuning, handles ambiguity effectively, offers multilingual support, and has demonstrated state-of-the-art performance in various NLP tasks.
I used Google Colab as my IDE, as frameworks like tensorflow are discontinued in windows
First I preprocessed the data into a structured form so it is easy to work with. 
After that, Trained the Bert model, with some tweaking, on that data, used Adam as optimizer.
