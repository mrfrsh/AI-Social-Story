# AI-Social-Story
This repo aims to create a bot that generates social story for autistic kids
## What is a social story 
Social story is a short story designed to prepare people on the autistic spectrum for new 
things that are not part of their regular routine.
For example, we want the child to be prepared to move to a new house, so we will create a social story
with simple sentences and drawings about the child moving to the new home.
[More reading here](https://www.autismparentingmagazine.com/social-stories-for-autistic-children/)

# General Flow of the code
1. Receive as input the following details
   2. Childs name
   3. Social story context:
      4. Waiting in line
      5. Going to the bathroom alone
      6. Going abroad
      7. finishing kindergraden 
2. Go to "prompts folder" and send the proper prompts to ChatGPT over API
3. Create a social story based on the answers
4. Add proper images (should probably be static for now, i.e not AI generated)
5. Generate a PDF(or any other file) file with the story that the parent\professional can print\read out
6. All of the input should be flushed to keep the children privacy, no data should be stored anywhere


